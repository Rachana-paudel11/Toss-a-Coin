# Coin Toss Simulator  

A simple and interactive **coin toss web app** built using **HTML, CSS (Bootstrap), and JavaScript**.  
This project demonstrates the use of **JavaScript event handling, random number generation, and DOM manipulation**.  

---

## Features  
- Toss a virtual coin with one click.  
- Randomly shows **Head** or **Tail** using images.  
- Styled with **Bootstrap 5** for a clean and responsive UI.  
- Beginner-friendly example for learning JavaScript basics.  

---

##  Technologies Used  
- **HTML5** – Structure of the webpage  
- **CSS3 / Bootstrap 5** – Styling and layout  
- **JavaScript (ES6)** – Logic for coin toss  

---

## How to Run  
1. Clone or download this repository.  
2. Place the files (`index.html`, `head.jpg`, `tail.jpg`) in the same directory.  
3. Open `index.html` in your browser.  
4. Click **"Toss the Coin"** button to simulate a toss.  

---

## File Structure  
coin-toss-simulator/
├── index.html # Main HTML file
├── head.jpg # Image of coin head
├── tail.jpg # Image of coin tail
└── README.md # Project documentation


---

## JavaScript Example  

```javascript
button.addEventListener("click", () => {
  let random = Math.floor(Math.random() * 2); // Generates 0 or 1
  if (random === 0) {
    image.src = "head.jpg";
  } else {
    image.src = "tail.jpg";
  }
});
