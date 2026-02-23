📘 CSS Module 11 — Responsive Design (Quick Notes)

📱 Responsive design makes websites adapt to different screen sizes.

---

1️⃣ Viewport Meta Tag ⭐
• Required for mobile responsiveness
• Add in HTML head: <meta name="viewport" content="width=device-width, initial-scale=1.0">

---

2️⃣ Responsive Units ⭐
• % → relative to parent size
• rem → scalable fonts
• vh/vw → relative to screen size
• Better than fixed px for layouts

---

3️⃣ Media Queries ⭐ (Core Tool)

• Apply CSS based on screen width
Example:
@media (max-width: 768px) {
body { background: lightgray; }
}

• Used to change layout, font size, spacing

---

4️⃣ Common Breakpoints
• Mobile → up to 480px
• Tablet → up to 768px
• Laptop → up to 1024px
• Desktop → above 1024px

---

5️⃣ Mobile-First Design ⭐
• Start styling for mobile first
• Add styles for larger screens later
• Leads to better performance and cleaner CSS

---

🎯 Key Idea to Remember

Responsive design = flexible units + media queries + mobile-first thinking.
