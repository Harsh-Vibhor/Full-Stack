📘 CSS Module 12 — Transitions & Animations (Quick Notes)

🎬 These add motion and smooth effects to UI elements.

---

1️⃣ transition ⭐
• Makes property changes smooth
• Example: transition: background 0.3s ease;
• Commonly used on hover effects

---

2️⃣ transform ⭐
• Used to move, rotate, or resize elements
• Examples:
scale() → zoom effect
translateX()/translateY() → move element
rotate() → rotate element

---

3️⃣ keyframes
• Defines animation steps
• Example:
@keyframes slide {
from { transform: translateX(0); }
to { transform: translateX(100px); }
}

---

4️⃣ animation
• Runs keyframe animation
• Example: animation: slide 1s infinite;

---

🎯 Key Idea to Remember

Transitions = smooth changes on interaction
Animations = continuous motion using keyframes
