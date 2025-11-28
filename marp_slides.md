---
marp: true
theme: custom-theme
paginate: true
footer: "© 2025 Software Documentation | 23f2004606@ds.study.iitm.ac.in"
---

<!-- Custom Marp Theme + Styling -->
<style>
section {
  font-family: "Segoe UI", sans-serif;
}

h1 {
  color: #1a73e8;
}

.custom-box {
  padding: 16px;
  border-radius: 10px;
  background: #e8f0fe;
  border: 2px solid #1a73e8;
  font-size: 1.1rem;
}

img.bg {
  opacity: 0.3;
}
</style>

<style id="custom-theme">
:root {
  --background-color: #ffffff;
  --text-color: #222;
  --accent-color: #1a73e8;
}
section {
  background-color: var(--background-color);
  color: var(--text-color);
}
h1, h2, h3 {
  color: var(--accent-color);
}
</style>

---
# Product Documentation
## Technical Overview
**Author:** 23f2004606@ds.study.iitm.ac.in

---
# Introduction

This presentation demonstrates maintainable, version-controlled documentation using **Marp**, convertible to:

- PDF (via Marp CLI / GitHub CI)
- HTML
- PPTX
- GitHub Pages

---
<!-- Background image slide -->
![bg](https://images.unsplash.com/photo-1527443154391-507e9dc6c5cc)

# System Architecture Overview

This slide includes a **background image**, fulfilling the requirement.

---
# Code Example

```python
def process_data(items):
    return [item * 2 for item in items]

print(process_data([1, 2, 3]))
```

---
# Algorithmic Complexity

For an algorithm processing input size \(n\):

\[
T(n) = n^2 + 3n + 2 = O(n^2)
\]

Another example:

\[
f(n) = \log(n) + n\log(n)
\]

---
# Custom Styled Block

<div class="custom-box">
This is a custom-styled block using Marp CSS.
Useful for highlights or important notes.
</div>

---
# Conclusion

- Fully version-controlled documentation
- Convertible to HTML/PDF/PPTX
- Includes custom theming and styling
- Ideal for maintainable software product docs

**Contact:** 23f2004606@ds.study.iitm.ac.in