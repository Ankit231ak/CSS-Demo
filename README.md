
## <H1> CSS loaders </H1>
<b>
<br>
### 1. `GlowEffect.html`
Creates three colored glowing boxes (blue, red, and yellow). Each box glows on hover using `box-shadow` and CSS transitions.

- 📌 Uses:
  - CSS transitions
  - `box-shadow` glow on hover
- 🎨 Colors: Blue, Red, Yellow
- 💡 Great for buttons or attention-grabbing elements.

---

### 2. `Gradient.html`
Generates a small animated gradient box using `@property` and `conic-gradient`. The gradient rotates infinitely.

- 📌 Uses:
  - CSS `@property` and `@keyframes`
  - `conic-gradient` animation
- 💡 Useful for background loaders or card decorations.

---

### 3. `Gradient2.html`
A glowing animated gradient box created with layered `::before` and `::after` pseudo-elements. The gradient spins continuously.

- 📌 Uses:
  - `conic-gradient`
  - `::before` and `::after` pseudo-elements
  - `blur` effect for glow
- 🎞️ Animation: Smooth 360° rotation

---

### 4. `Gradient3.html`
A larger, circular glowing box with animated gradients. It builds on the concepts in the previous files but with a circular shape and more glow intensity.

- 📌 Uses:
  - Circular `border-radius`
  - Animated `conic-gradient` using `--angle`
  - Enlarged size and soft glow

---

## ✅ How to Use

1. Open any of the `.html` files in a modern web browser (e.g., Chrome, Firefox, Edge).
2. You’ll see visually styled boxes with hover or auto animation effects.
3. Modify CSS values (like color, size, animation speed) as needed.

---

## 🔧 Requirements

- A modern browser supporting:
  - CSS `@property` (e.g., Chrome 85+, Edge 85+)
  - `conic-gradient`
  - Pseudo-elements (`::before`, `::after`)
  - CSS animations


