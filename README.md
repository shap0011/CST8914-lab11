# Lab 11: Accessible Custom Components & widgets

**Student: Olga Durham**

**Student #: 040687883**

---

## What is the keyboard interaction missing?

The original accordion only supported basic Tab focus and click. It did not implement the extra keyboard interactions recommended by the WAI-ARIA accordion pattern, such as using arrow keys (and optionally Home/End) to move between accordion headers.

---

## What is the ARIA missing?

The original code was missing the ARIA relationships between each header and its panel. The buttons did not have `aria-expanded` or `aria-controls`, and the content panels did not have `role="region"` or `aria-labelledby`. Because of this, screen readers could not know which section was expanded or which button controlled which panel.

---

[Simple Accordions](https://shap0011.github.io/CST8914-lab11/index.html)

## Reference:

[Accordion Example](https://www.w3.org/WAI/ARIA/apg/patterns/accordion/examples/accordion/)
