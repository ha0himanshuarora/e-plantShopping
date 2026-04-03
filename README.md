# Paradise Nursery – Houseplant Shopping Application

A high-fidelity React-based e-commerce interface for a specialized houseplant nursery. This project demonstrates advanced state management using Redux Toolkit, dynamic UI updates, and a responsive shopping experience.

## Live Demo
**[View the Live Store on Vercel](https://e-plant-shopping-b1ux.vercel.app)** *(Note: Update this link if your Vercel deployment URL changes)*

---

## Features

### 1. Landing Page
* **Immersive Visuals:** High-quality nature-themed background with a Glassmorphism content overlay.
* **Our Mission:** Integrated About Us section detailing the nursery's commitment to air quality and serenity.
* **Seamless Entry:** Get Started CTA that triggers a smooth transition to the product catalog.

### 2. Product Listing Page
* **Smart Categorization:** Plants are grouped into categories like Air Purifying, Aromatic, and Low Maintenance.
* **Real-time Cart Status:**
    * The Add to Cart button dynamically transforms to "Added to Cart" and disables itself once a plant is selected.
    * A persistent navbar badge displays the live total count of all items in the cart.

### 3. Shopping Cart Page
* **Granular Control:** Increase, decrease, or remove plant types directly from the cart view.
* **Auto-Cleanup:** If a plant's quantity reaches zero, it is automatically purged from the Redux state.
* **Automated Calculations:**
    * **Subtotal:** Individual totals for each plant type based on quantity.
    * **Grand Total:** Real-time calculation of the entire order cost.

---

## Tech Stack

* **Core:** React.js (Vite-powered)
* **State Management:** Redux Toolkit
* **Data Flow:** React-Redux (useSelector, useDispatch hooks)
* **Styling:** Custom CSS3 with Flexbox and Grid layouts
* **Deployment:** Vercel

---

## Local Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/haOhimanshuarora/e-plantShopping.git](https://github.com/haOhimanshuarora/e-plantShopping.git)
   cd e-plantShopping