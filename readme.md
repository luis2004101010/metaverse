# TEST Project

A simple test project using **HTML**, **SCSS**, and **JavaScript**.

---

## Folder Structure

assets/
└── images/
├── about-bg.jpg
├── banner-bg.jpg
├── document.png
├── hero.png
├── logo.png
├── sphere.png
└── title.png

dist/
├── main.css
└── main.css.map

scss/
├── about.scss
├── banner.scss
├── features.scss
├── header.scss
└── main.scss

index.html
readme.md

## How to Run

### 1. Install Sass

If Sass is not installed, run:

npm install -g sass

### 2. Compile SCSS and Watch for Changes

sass --watch scss/main.scss:dist/main.css

### 3. Open in Browser

Simply open index.html in your browser to view the project.

## Notes

All images are located in assets/images/

SCSS files are in the scss/ folder

Compiled CSS is output to dist/main.css
