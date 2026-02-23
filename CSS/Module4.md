📘 CSS Module 4 — Colors & Units (Quick Notes)

🎨 COLORS IN CSS

1️⃣ Color Names
• Example: color: red;
• Simple but limited choices

2️⃣ HEX Colors ⭐ (Most common)
• Format: #RRGGBB
• Example: #ff0000 (red), #000000 (black)
• Widely used in real projects

3️⃣ RGB Colors
• Format: rgb(red, green, blue)
• Values range: 0–255
• Example: rgb(255, 0, 0)

4️⃣ RGBA (RGB + Transparency)
• Format: rgba(r, g, b, opacity)
• Opacity: 0 (transparent) → 1 (solid)
• Used for overlays & UI effects

5️⃣ HSL Colors
• Format: hsl(hue, saturation%, lightness%)
• Used in design systems and fine color control

---

📏 CSS UNITS

🔹 Absolute Unit

• px → fixed size
Example: font-size: 16px;
• Easy but not responsive

---

🔹 Relative Units ⭐ (Important)

• % → relative to parent size
Example: width: 50%;

• em → relative to parent font-size

• rem ⭐ → relative to root font-size
Best for typography and spacing

• vh → viewport height
• vw → viewport width
Used for full-screen layouts

---

🎯 Key Idea to Remember

HEX for colors,
rem for fonts,
% and vh/vw for responsive layouts.
