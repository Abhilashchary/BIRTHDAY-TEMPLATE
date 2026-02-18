
---

# 🎉 Birthday Surprise Website Template

A cute, animated birthday surprise website built using **HTML, CSS, and JavaScript** — featuring:

* 🎊 Confetti animation
* ✨ Smooth scroll animations (AOS)
* 📸 Scrapbook-style photo wall
* 💌 Hidden birthday letter reveal
* 🎀 Soft aesthetic design

🔗 **Live Demo:**
[https://abhilashchary.github.io/BIRTHDAY-TEMPLATE/](https://abhilashchary.github.io/BIRTHDAY-TEMPLATE/)

---

## 📂 Project Structure

```
BIRTHDAY-TEMPLATE/
│
├── index.html
├── photo.jpg
└── README.md
```

Everything is inside **index.html**, so it’s beginner-friendly and easy to edit.

---

# 🚀 How To Run This Website

### ✅ Option 1: Run Locally (Easiest)

1. Download or clone the repository:

   ```
   git clone https://github.com/abhilashchary/BIRTHDAY-TEMPLATE.git
   ```

2. Open the folder.

3. Double-click `index.html`.

That’s it! It will open in your browser 🎉

---

### ✅ Option 2: Deploy on GitHub Pages

1. Push your edited code to your GitHub repository.
2. Go to:

   ```
   Settings → Pages
   ```
3. Under **Source**, select:

   ```
   Deploy from branch → main → /root
   ```
4. Save.

Your website will be live at:

```
https://yourusername.github.io/repository-name/
```

---

# 🖼 How To Change The Photos

Currently, all images use:

```html
<img src="photo.jpg" alt="Memory">
```

### To change photos:

### Step 1:

Replace `photo.jpg` in the project folder with your own images.

Example:

```
photo1.jpg
photo2.jpg
photo3.jpg
```

### Step 2:

Update the image source in `index.html`.

Example:

```html
<img src="photo1.jpg" alt="Memory">
<img src="photo2.jpg" alt="Memory">
<img src="photo3.jpg" alt="Memory">
```

Make sure:

* Images are in the same folder as `index.html`
* File names match exactly (case-sensitive)

---

# ✏️ How To Change The Text

You can edit all text directly inside `index.html`.

---

### 🎂 Change Name

Find:

```html
Happy Birthday<br> Kelly ! 🎉
```

Replace **Kelly** with your person’s name.

---

### 💌 Edit The Letter

Find this section:

```html
<div id="theLetter">
```

Modify the paragraphs inside it to write your own message.

---

### 📖 Edit Timeline Story

Search for:

```html
First Conversation
Realizing You're Cool
Small But Memorable
```

Change the headings and paragraphs to your own story.

---

### 📸 Edit Photo Captions

Below each image you’ll see:

```html
<p>Capturing a purely cute moment 💕</p>
```

Change the caption text however you like.

---

# 🎨 Customize Colors (Optional)

At the top of the CSS, you’ll find:

```css
:root {
    --bg-cream: #fdfaf5;
    --soft-pink: #fdf1f2;
    --main-pink: #f2a1b1;
    --accent-pink: #e07a8b;
}
```

You can change these hex values to completely transform the theme.

Example:

* Blue theme 💙
* Purple theme 💜
* Dark theme 🌙

---

# ✨ Features Used

* Canvas Confetti (CDN)
* AOS (Animate On Scroll)
* Google Fonts
* Pure HTML, CSS & JS (No frameworks)

---

# ⚠️ Important Notes

* GitHub Pages does NOT support backend code.
* This is a static website only.
* Keep all files in the root folder for easy deployment.
* Image file names must match exactly.

---

# ❤️ Make It Personal

To make this special:

* Use real photos
* Write inside jokes
* Add meaningful dates
* Customize colors based on their favorite color
* Add a custom background song (optional enhancement)

---

# 🛠 Optional Upgrade Ideas

* 🎵 Add background music
* 🎞 Add a slideshow
* 📱 Improve mobile responsiveness
* 💖 Add a countdown timer
* 🌙 Add dark mode toggle

---

# 👋 Final Note

This template was built to help you create something meaningful even if you can’t afford a big gift.

Sometimes effort > money.

If you use this template, feel free to ⭐ the repo!

---
