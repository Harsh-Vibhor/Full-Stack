📘 CSS Module 3 — Selectors (Quick Notes)

🔹 What are Selectors?
• Used to target HTML elements for styling
• Decide “which elements get the CSS”

---

1️⃣ Element Selector
• Targets all elements of a tag
Example: p { color: blue; }

---

2️⃣ Class Selector ⭐ (Most Used)
• Targets elements with a class
• Starts with . (dot)
Example: .box { background: red; }
• Can be reused on many elements

---

3️⃣ ID Selector
• Targets element with specific ID
• Starts with #
Example: #header { color: green; }
• Should be unique per page

---

4️⃣ Group Selector
• Style multiple elements together
Example: h1, p, div { color: purple; }

---

5️⃣ Descendant Selector ⭐
• Targets elements inside another element
Example: div p { color: orange; }

---

6️⃣ Child Selector
• Targets direct children only
Example: div > p { color: red; }

---

7️⃣ Attribute Selector
• Targets elements by attribute
Example: input[type="text"] { border:1px solid; }

---

8️⃣ Pseudo-Classes ⭐ (Element State)
• Style based on interaction/state
Examples:
:hover → mouse over
:focus → input selected
:nth-child() → specific child

---

9️⃣ Pseudo-Elements
• Style parts of elements
Examples:

---

🎯 Key Idea to Remember
Classes are used most in real projects.
Selectors control exactly where styles apply.