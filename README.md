# ABC Robotics Landing Page

A modern, high-performance static landing page for ABC Robotics. Designed to showcase enterprise-grade industrial automation and robotics solutions with a professional, grounded aesthetic.

## 🚀 Live Demo

**[View the Live Site on Vercel](https://landing-webpage-five.vercel.app/)**

## 🎨 Design Approach
- **Striking yet Grounded:** The goal was to create a highly dynamic, visually impressive hero section that captures attention immediately, while using grounded, professional copywriting to establish trust as a true B2B corporate entity.
- **High Contrast Aesthetic:** Utilized a deep slate/navy background with vibrant industrial orange accents (`#FF8800`) to convey high-tech precision, manufacturing power, and modern engineering.
- **Dynamic Interaction:** Implemented subtle hover states, micro-animations, and a continuous glowing 3D SVG animation to make the interface feel responsive and alive without overwhelming the user.

## 🛠️ Technologies Used
- **HTML & CSS:** Used to build the core structure of the website and design how it looks. All the complex visual effects, like the spinning rings and glowing robot, are made entirely using standard CSS animations.
- **React:** Used to break the website down into smaller, reusable building blocks (like the Hero section, the Timeline, and the Features list). This makes the code organized, easy to read, and simple to update.
- **JavaScript:** Used to add interactive features to the site, such as making elements smoothly appear when you scroll down the page, and making the mobile menu work.

## 💡 Key Features & Decisions
- **Zero-Build Architecture:** Deliberately chose a serverless, build-free architecture. The entire site runs statically, ensuring lightning-fast load times, extreme portability, and easy local development.
- **Animated SVG Hero:** Instead of relying on heavy WebGL libraries (like Three.js) or large video files, the 6-DOF industrial robot arm and "HUD" elements are built entirely with SVG and CSS keyframes. This keeps the page weight incredibly low while maintaining high visual fidelity.
- **Corporate Pivot:** Intentionally replaced generic "sci-fi AI" buzzwords with professional industrial terminology (e.g., "System Integration", "PLC Programming", "10+ Years Experience") to ensure the brand resonates with actual manufacturing clients.

## 💻 How to Run Locally

Since this is a lightweight static website without complex build tools, it is extremely easy to run locally:

**Option 1: Open in Browser (Easiest)**
1. Navigate to the project folder.
2. Double-click on the `index.html` file to open it directly in your web browser.

**Option 2: Use a Local Server**
If you have Node.js installed and prefer running it over a local server:
1. Open your terminal in the project directory.
2. Run the following command:
   ```bash
   npx serve .
   ```
3. Open `http://localhost:3000` in your browser.
