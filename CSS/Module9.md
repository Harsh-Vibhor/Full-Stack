📘 CSS Module 9 — Flexbox (Quick Notes)

🔹 Flexbox is used to arrange elements in rows or columns easily.

To activate Flexbox:
.container { display: flex; }

The container becomes a flex container,
its children become flex items.

---

1️⃣ flex-direction
• Controls layout direction
• row (default), column, row-reverse, column-reverse

---

2️⃣ justify-content ⭐
• Aligns items on main axis (horizontal in row layout)
• Values: flex-start, center, flex-end, space-between, space-around, space-evenly

---

3️⃣ align-items ⭐
• Aligns items on cross axis (vertical in row layout)
• Values: flex-start, center, flex-end, stretch

---

4️⃣ gap
• Adds spacing between items
• Cleaner than using margins

---

5️⃣ flex property
• Controls how items grow/shrink
• flex: 1 → items share equal space

---

🎯 Key Idea to Remember

Flexbox = easy alignment + spacing + responsive layout.
Used heavily in navbars, cards, and sections.
