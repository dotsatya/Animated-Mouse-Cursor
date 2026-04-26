# ✨ Cursor Animation (JavaScript + CSS)

This repository showcases a **custom animated cursor** built using
**JavaScript and CSS** to enhance user interaction and UI experience.

------------------------------------------------------------------------

## 🚀 Features

-   🎯 Custom cursor replacing default pointer\
-   🌈 Smooth animation effects\
-   🖱️ Cursor follows mouse movement\
-   ✨ Hover effects on clickable elements\
-   ⚡ Lightweight and fast

------------------------------------------------------------------------

## 📂 Project Structure

    /cursor-animation
    │── index.html
    │── style.css
    │── script.js
    │── README.md

------------------------------------------------------------------------

## 🧠 How It Works

### 1. HTML

Basic structure with cursor element

``` html
<div class="cursor"></div>
```

------------------------------------------------------------------------

### 2. CSS (Styling & Animation)

``` css
.cursor {
  width: 20px;
  height: 20px;
  border: 2px solid white;
  border-radius: 50%;
  position: fixed;
  pointer-events: none;
  transform: translate(-50%, -50%);
  transition: transform 0.1s ease;
}
```

------------------------------------------------------------------------

### 3. JavaScript (Movement Logic)

``` javascript
const cursor = document.querySelector(".cursor");

document.addEventListener("mousemove", (e) => {
  cursor.style.top = e.clientY + "px";
  cursor.style.left = e.clientX + "px";
});
```

------------------------------------------------------------------------

## ⚙️ How to Run

1.  Clone the repository\
2.  Open `index.html` in browser

------------------------------------------------------------------------

## 🎯 Future Improvements

-   Add trailing cursor effect\
-   Add click animations\
-   Add different themes\
-   Optimize for mobile devices

------------------------------------------------------------------------

## 📬 Connect With Me

-   Portfolio: https://dotsatya.vercel.app\
-   LinkedIn: https://linkedin.com/in/satya-sundar-dey

------------------------------------------------------------------------
