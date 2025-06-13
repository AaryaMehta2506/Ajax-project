# 🖼️ AJAX Product Image Preview

This project showcases a simple, elegant **product image viewer** using **AJAX techniques** with **HTML, CSS, and JavaScript**. Users can click on thumbnail images to change the main product image dynamically—mimicking the behavior seen in modern e-commerce platforms.

---

## 🚀 Features

- 🖼️ **Thumbnail Switching**: Clicking on a thumbnail updates the main product image.
- 📱 **Responsive Design**: Adjusts layout for mobile and desktop views.
- ⚡ **Dynamic Image Loading**: Powered by JavaScript for seamless interaction.
- 🎨 **CSS Styling**: Clean and intuitive layout, easy to customize.
- 💻 **Lightweight**: No external dependencies required.

---

## 🗂️ Project Structure
ajax-image-preview/
├── ajax.html # Main HTML file
├── ajax_files/
│ ├── 2.jpeg # Main image & thumbnail
│ ├── 3.jpeg # Alternate thumbnail
│ ├── 4.jpeg # Alternate thumbnail
│ └── style.css # Custom CSS for styling layout
├── README.md # Project documentation
└── LICENSE # MIT License

## 📦 Requirements

- 🐍 No backend or package installation required
- 💡 Just a browser that supports modern JavaScript (Chrome, Firefox, Edge, etc.)

---

## ▶️ How to Run

1. Clone or download this repository:
   ```
   git clone https://github.com/YourUsername/ajax-image-preview.git
   cd ajax-image-preview
   ```
2. Open ajax.html in any modern browser:
```
start ajax.html    # Windows
open ajax.html     # macOS
```
3. Click on any thumbnail to preview the image as the main product.

.

## 💡 Use Cases
E-commerce product galleries

Image carousels

Real-time preview modules

UI prototyping for interactive layouts

## 🧠 How It Works
Each thumbnail is wrapped in a .box div.

JavaScript onclick events change the src of the main product image.

Active thumbnail is highlighted using .active CSS class.
```
function changeImage(event) {
  document.querySelector(".pro-img").src = event.children[0].src;
  for (let i = 0; i < thumbs.length; i++) {
    thumbs[i].classList.remove("active");
  }
  event.classList.add("active");
}
```

## 🤝 Contributing
Feel free to fork this repo, make changes, and submit pull requests!
You can also extend this with animations, gallery sliders, or backend integration.

## 📄 License
This project is licensed under the [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

## 👩‍💻 Author

**Aarya Mehta**  
🔗 [GitHub Profile](https://github.com/AaryaMehta2506)
