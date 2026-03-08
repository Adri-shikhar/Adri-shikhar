## Hi there 👋

# Hi there, I'm [Your Name]! 👋

Welcome to my GitHub! I am a passionate Frontend Developer currently leveling up my skills from beginner to intermediate JavaScript. I love building dynamic, data-driven user interfaces and writing clean, modern ES6+ code.

## 🚀 What I Bring to the Table

I have been deep-diving into the core mechanics of JavaScript. Here is what I am actively working with:

* **Modern JavaScript (ES6+):** Arrow functions `=>`, Template Literals, and writing clean, one-line `.map()` transformations.
* **Asynchronous Data:** Fetching live data from REST APIs using `async / await` and safely unpacking JSON.
* **Advanced DOM Manipulation:** Building Single Page Application (SPA) tabbed navigation using `querySelector` and dynamic class toggling.
* **Event Architecture:** Utilizing Event Delegation and Event Bubbling to efficiently manage clicks on dynamically generated UI cards.
* **Under the Hood:** A strong understanding of core JS mechanics, including Closures (for data privacy) and the difference between Primitive (Value) and Non-Primitive (Reference) memory.

## 💻 Code Philosophy

I believe in writing code that reads like plain English. Here is a quick look at my preferred style for handling asynchronous data:

```javascript
// Fetching and safely rendering data using modern ES6 syntax
const getAndRenderUsers = async () => {
    try {
        const response = await fetch("[https://jsonplaceholder.typicode.com/users](https://jsonplaceholder.typicode.com/users)");
        const users = await response.json();
        
        // Using .map() to extract exactly what the UI needs
        const userCards = users.map(user => `<div class="card">${user.name}</div>`);
        document.querySelector("#user-container").innerHTML = userCards.join("");
        
    } catch (error) {
        console.error("Failed to fetch users. Check connection.");
    }
};
