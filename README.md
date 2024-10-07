# Front-End-Programmer-Exam
### Programming Assignment: Interactive 3D Portfolio with Next.js, Tailwind CSS, Framer Motion, GSAP, and AR.js

**Objective:**  
This assignment is designed to test your ability to create a dynamic, interactive web experience using **Next.js**, **TypeScript**, **Tailwind CSS**, **Framer Motion**, **GSAP**, and **AR.js**. The primary focus is on implementing animations, 3D interaction, and AR functionality, with a deployed live demo as a requirement.

---

### Task Overview

You will build an interactive portfolio page that includes the following features:

- **Frontend:**
  - Use **Next.js** and **TypeScript** for the project setup and structure.
  - Style the UI with **Tailwind CSS**.
  - Implement advanced animations using **Framer Motion** and **GSAP**.
  - Display a provided **GLTF** 3D model using a WebGL library like **Three.js**.
  - Integrate **AR.js** to allow users to view the 3D model in augmented reality (AR) on mobile devices.
  
- **Deployment:**  
  - Deploy the project on **Vercel** (or a similar platform) to provide a live demo URL as part of the submission.

---

### Detailed Requirements

#### 1. **Project Setup**

- Use **Next.js** with **TypeScript** as the framework for the project.
- Install and configure **Tailwind CSS** for responsive and modern styling.
- Set up **Framer Motion** and **GSAP** for animations throughout the project.

#### 2. **3D Model Integration**

- You will be provided with a **GLTF** file of a 3D model.
- Use **Three.js** (or a similar WebGL library) to load and display this model on your portfolio page.
- Allow the user to interact with the 3D model (rotate, zoom, etc.).
- Implement animations for the model’s appearance (e.g., fade-in or slide-in) when the page loads using **Framer Motion** or **GSAP**.

#### 3. **Augmented Reality (AR.js)**

- Integrate **AR.js** to provide an augmented reality experience where users can view the 3D model in their environment using their mobile device's camera.
- Create a **"View in AR"** button on the page. Clicking this button should activate the AR experience.
- Ensure the AR functionality works smoothly on mobile devices.

#### 4. **Motion and Animations**

- Implement the following animations using **Framer Motion** and **GSAP**:
  - A smooth loading animation for the 3D model (e.g., fade-in or scaling effect).
  - Hover animations on buttons and other interactive elements (e.g., the "View in AR" button).
  - Add scroll-based animations where certain elements (like text or images) animate into view as the user scrolls down the page.

#### 5. **Contact Section (No Backend)**

- Create a static "Contact Me" form with fields for:
  - Name
  - Email
  - Message
- Since no backend is required, focus on adding animations:
  - Use **Framer Motion** to animate the form fields when they come into view.
  - Animate the "Submit" button (e.g., apply a hover or click animation using **GSAP** or **Framer Motion**).

#### 6. **Responsive Design**

- Ensure the page is fully responsive, adapting well to both desktop and mobile screens.
- The 3D model and AR functionality should work seamlessly on mobile devices.

#### 7. **Deployment**

- Deploy the application on **Vercel** (or a similar platform).
- Provide the **live demo URL** as part of your submission.

---

### Provided Resources

- **GLTF File**: A GLTF 3D model file will be provided for you to display in the application.
- **AR.js Documentation**: You can refer to the [AR.js Documentation](https://ar-js-org.github.io/AR.js-Docs/) for integrating AR features.

---

### Deliverables

1. **GitHub Repository**: 
   - A public GitHub repository link with your complete code.

2. **Readme**:
   - A README file with instructions on how to set up and run the project locally.
   - Include details on how to access the AR functionality.

3. **Live Demo URL**:
   - The **deployed live demo** link from Vercel (or another deployment platform).

---

### Evaluation Criteria

- **Implementation**: Properly loading the 3D model, integrating AR.js, and applying animations.
- **Code Quality**: Clean, modular code with good use of TypeScript.
- **Animations**: Smooth, creative animations using **Framer Motion** and **GSAP**.
- **Responsiveness**: The website must work well on both desktop and mobile devices, including the AR experience.
- **Design**: Effective use of **Tailwind CSS** for modern, responsive design.
- **Deployment**: Successful deployment on Vercel with a working live demo.

---

### Bonus Points

- Advanced 3D model interactions (e.g., touch gestures for mobile, advanced rotations).
- Additional creative animations (such as parallax effects, scroll-triggered animations, etc.).
- Extra AR features like custom markers or more interactive AR scenes.

Good luck!
