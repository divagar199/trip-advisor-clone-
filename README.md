# 🌍 TripAdvisor Clone (Chennai Focus)

This is a responsive frontend clone of the TripAdvisor interface, specifically showcasing destinations, activities, hotels, and restaurants around Chennai (Madras), India. The project focuses on replicating the key layout and user experience features of a major travel booking platform.

## 🌟 Key Features

* **Responsive & Fixed Header:** The header dynamically adjusts for different screen sizes. On mobile, the logo and search bar are fixed to the top of the viewport for continuous access while scrolling.
* **Intuitive Navigation:** Includes separate sections for Discover, Trips, Reviews, and clearly defined search categories (Hotels, Things to Do, Restaurants).
* **Engaging Content Blocks:** Features a prominent video/image content block (`.main-1`) with a clear Call-to-Action (CTA).
* **Dynamic Card Sections:** Uses flexible layouts to display horizontal-scrolling cards for "Experiences near you" and "Best Restaurants," complete with ratings and specialized badges (e.g., "Likely to Sell Out," "Best Seller").
* **Interest-Based Grids:** Sections dedicated to exploring activities by interest (Outdoors, Food, Culture, Water) using a responsive grid system.
* **Comprehensive Footer:** Includes multi-column links, legal information, and region/currency selectors, mimicking professional site footers.

---

## 🚀 Technologies Used

* **HTML5:** Provided the robust structure for all page elements.
* **CSS3:** Utilized **Flexbox** and **Grid** extensively for complex, responsive layouts.
* **Media Queries:** Implemented precise breakpoints to optimize the layout, particularly for stacking and fixing the search bar on mobile screens.
* **Font Awesome:** Used for scalable vector icons throughout the interface.
* **Google Fonts (Outfit):** Ensured modern and readable typography across the site.

---

## ⚙️ How to Run Locally

1.  **Clone the Repository:**
    ```bash
    git clone (https://github.com/divagar199/trip-advisor-clone/)
    ```

2.  **Open the File:**
    Navigate to the project directory and open the `index.html` file in your web browser (Chrome, Firefox, etc.).

    ```bash
    cd [project-folder-name]
    start index.html
    ```
    *(Since this is a static project, no server or installation is required.)*

---

## 📱 Responsiveness Showcase

The CSS is designed around these core rules to ensure a smooth user experience on all devices:

| Component | Desktop (1024px+) | Tablet (768px+) | Mobile (< 600px) |
| :--- | :--- | :--- | :--- |
| **Search Bar Position** | Static, centered under header. | Static, centered. | **Fixed** at `top: 0` for scrolling access. |
| **Headline Filters** | Horizontal row. | Wraps onto multiple lines. | Hidden (`display: none`) to save vertical space. |
| **Interest Grids** | 4 columns. | 2 columns. | 1 column (Stacked). |
| **Experience Cards** | Wide view with horizontal scroll. | Horizontal scroll is maintained. | Cards use `60vw` width for easy thumb swiping. |

---

## 🤝 Contribution & Feedback

I welcome feedback on the responsiveness, styling, and general code structure. Feel free to fork the repository, open an issue, or submit a pull request!

**Developed by: [divagar199]**
