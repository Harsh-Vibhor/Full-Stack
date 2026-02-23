📘 CSS Module 10 — CSS Grid (Quick Notes)

🔹 CSS Grid is used for creating layouts with rows AND columns (2D layout).

To activate Grid:
.container { display: grid; }

---

1️⃣ grid-template-columns ⭐
• Defines number and width of columns
• Example: grid-template-columns: 1fr 1fr 1fr;
• fr = fraction of available space

---

2️⃣ grid-template-rows
• Defines row heights
• Example: grid-template-rows: 100px 200px;

---

3️⃣ gap
• Adds spacing between rows & columns
• Cleaner than margins

---

4️⃣ repeat() ⭐
• Shortcut for repeating columns
• Example: grid-template-columns: repeat(3, 1fr);
• Very commonly used

---

5️⃣ Item Placement
• Control how items span columns/rows
• Example: grid-column: 1 / 3;

---

🎯 Key Idea to Remember

Flexbox = one direction layout
Grid = full page structured layout

Grid is best for dashboards, galleries, and page layouts.
