# ☁️ IT School Weather Application

This is the final project for the Frontend Development course, displaying current weather and a 5-day forecast for selected cities.

---

## 🚀 Live Demo

You can access the live, deployed version of the application here:

[Netlify Link]
**(PLACE YOUR NETLIFY LINK HERE)**

---

## ✨ Project Features (Principalele Funcționalități)

The application includes the following key features:

* **Scroll-to-Top Button:**
    * A button featuring a **Material Symbol icon** (`upload`) that is initially hidden.
    * It appears only when the user scrolls **past half of the viewport height** (`window.innerHeight / 2`), as required by the assignment.
    * Provides a smooth animation back to the top of the page on click.

* **Location Management:**
    * Extended the city selection list to include **Arad** and **Sibiu**.
    * Implemented event listeners to display weather data for **Arad** and **Sibiu** upon selection.
    * The default city upon first load is set to **București**.

* **Core Weather Display:** Displays current weather details, a 5-day forecast, and uses `localStorage` to remember the last selected city.

---

## 🔑 Installation and Use

To run this project locally, simply open the `index.html` file in your web browser.