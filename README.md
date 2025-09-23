# MindGradient CSS

A modern, customizable, and easy-to-use CSS gradient library for creating beautiful, animated gradients.

👉 [Live Demo & Generator](http://code.iqbalmind.id/mindgradient/)

MindGradient is a lightweight, plug-and-play CSS library that allows you to add stunning, animated gradients to any HTML element with just a single class. It's built with customization in mind, using modern CSS variables to make theming a breeze.

---

## ✨ Features
- 🎨 **16+ Beautiful Presets** – A curated collection of modern, elegant gradients.  
- ✨ **Subtle Animations** – An optional animation class to bring your gradients to life.  
- 🛠 **Fully Customizable** – Easily change gradient colors using CSS variables.  
- 🪶 **Feather-light** – Tiny footprint with zero dependencies.  
- ⚙ **Interactive Generator** – Visually create your own gradients and get the code instantly.  

---

## 📦 Installation

### CDN
The quickest way is to link the stylesheet directly in your HTML `<head>` tag:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/iqbalmind/mindgradient@latest/mindgradient.css">
```

### NPM

Install the package using your favorite package manager:
```npm
npm install mindgradient
```

Then, import the CSS file into your main stylesheet or JavaScript file:
```css
/* In your main CSS file */
@import 'mindgradient/mindgradient.css';
```

## 🚀 Usage

Add the desired gradient class (e.g., `.grd-sunset`) to any element.

(Optional) Add the .grd-animated class to enable subtle animation.
```css
<!-- A simple static gradient -->
<div class="grd-sunset"></div>

<!-- An animated gradient -->
<div class="grd-ocean grd-animated"></div>
```

## 🎨 Customization

Override the default colors of any gradient by redefining its CSS variables in your own stylesheet.
Make sure your custom rules are loaded after mindgradient.css.
```css
/* your-styles.css */
.grd-sunset {
  --grd-color-1: #0052D4; /* A new starting blue */
  --grd-color-2: #9CECFB; /* A new ending cyan */
}
```

## 🤝 Contributing

Contributions are welcome!
If you have ideas for new gradients, features, or improvements, please open an issue or submit a pull request on the GitHub repository

## 📜 License

This project is licensed under the MIT License – see the [LICENSE](https://github.com/iqbalmind/mindgradient/blob/main/LICENSE) file for details.

Made with ❤ by [IqbalMind](http://iqbalmind.id/)
