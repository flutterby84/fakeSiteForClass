# Final Responsive Website — Web Design (CIS 134)

Hi there! 👋 my name is Meghan,   
This is the final project I created for my Web Design course at Indian Hills Community College.  
It’s a responsive website built with HTML, Tailwind CSS, and some JavaScript. Thas a website created for a fictitious company. 


---

## 📄 What’s included

✅ Home Page (`index.html`)  
✅ Contact Page (`contact.html`)  
✅ Products Page (`product.html`)

---

## ✨ What I did and how I did it (step by step)

### 1️⃣ Basic Layout
- Created the structure for all three pages using HTML.
- Set up semantic elements: `<header>`, `<main>`, `<footer>`.
- Added navigation links between pages.

### 2️⃣ Responsive Layout with Tailwind
- Used Tailwind utility classes to control layout.
- Example classes:
  - `flex`, `flex-col`, `md:flex-row` → stacks or rows items depending on screen size.
  - `gap-4`, `p-4`, `m-4` → added space and padding.
  - `w-full`, `w-10`, `h-32 md:h-48` → controlled image sizes.
  - `text-3xl`, `text-xl` → adjusted text sizes.
  - `rounded`, `border`, `shadow-lg` → added borders, rounded corners, shadows.
  
### 3️⃣ Responsive Navigation
- Added a hamburger menu (`☰`) for mobile view.
- Used JavaScript to toggle the mobile nav menu open/closed.
- Tailwind classes like:
  - `hidden md:flex` → hide on mobile, show on desktop.
  - `md:hidden` → show hamburger button only on mobile.

### 4️⃣ Responsive Images
- Added banner images and product images.
- Used `object-cover`, `object-[70%_30%]` to control how images fit in their boxes.
- Made images responsive with `h-32 sm:h-40 md:h-48`.

### 5️⃣ Responsive Forms
- On Contact page: name, surname, email, message.
- On Product page: search bar.
- Tailwind classes:
  - `flex`, `flex-col`, `sm:flex-row` → stack or row inputs.
  - `w-full`, `max-w-md` → control input width.

### 6️⃣ Responsive Tables
- On Product page, added a product info table.
- Used `table-auto w-full`, `border-collapse`, `border`, `px-4 py-2` for a clean table.

### 7️⃣ Custom Fonts
- Added two custom fonts from Google Fonts.
- Applied to headings and body text.

### 8️⃣ Accessibility
- Added descriptive `alt` text to images.
- Checked color contrast.
- Made sure forms have clear labels.

---

## 💻 How to view the site

Check it out live here:  
https://github.com/flutterby84/fakeSiteForClass/upload/main

---

## ⚙️ Technologies used

- HTML
- Tailwind CSS (via CDN)
- JavaScript
- Google Fonts

---

Thanks for checking it out! 🌟

