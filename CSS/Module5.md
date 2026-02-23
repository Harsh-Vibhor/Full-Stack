📘 CSS Module 5 — Box Model (Quick Notes)

📦 Every HTML element is treated as a rectangular box.

The Box Model has 4 layers (inside → outside):

1️⃣ Content
• The actual text, image, or element content
• Controlled by width and height

2️⃣ Padding
• Space inside the element, between content and border
• Increases element size
• Background color covers padding

3️⃣ Border
• The visible edge around the element
• Also increases element size

4️⃣ Margin
• Space outside the element
• Used to create distance between elements
• Background color does NOT cover margin

---

📏 Default Size Calculation

Total element size =
content + padding + border + margin

So width: 200px does NOT mean final width is 200px.

---

🔥 box-sizing Property (Important)

• box-sizing: content-box → default behavior
• box-sizing: border-box ⭐ → width includes padding & border

Most developers use:

* {
  box-sizing: border-box;
  }

---

🎯 Key Idea to Remember

Padding = inside space
Margin = outside space
Border adds size
Use border-box for predictable layouts
