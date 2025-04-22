# Demo
ตัวอย่าง **Markdown** $a \in \mathbb{R}^+$.
<div class="mermaid">
 sequenceDiagram
	A->>B: I like you.
	B->>C: C, you are cute.
	C->>A: A, Are you OK?
</div>	

---

## Diagram
<div class="mermaid">
graph TD
	A[Start] --> E[find 1+1]
	E --> B{Is it 1+1 = 0 ?}
	B -- True --> C[Good!]
	B -- False --> D[Fix it]
	D --> E
</div>

---

##
```html
<div>Test
	<p>How to</p>
	<p>555</p>
</div>
```
---
## Lists
- [✔] [symbl](https://symbl.cc/)
- [☑] Item 1
- [❌] Item 2
  - [❎] Subitem
  - [✅] test ทำใหม่
---
## ✅ Tables ❎
| ชื่อ    | อายุ | บ้านเกิด    |
|--------|-----|-----------|
| A      | 30  | New York  |
| B      | 25  | Los Angeles|
| Ch     | 35  | Chicago   |
---
## Code Example 1
```js
function greet(name) {
  return `Hello, ${name}!`;
}
```
---
## Code Example 2
```js
window.MathJax = { 
	tex: { inlineMath: [['\\(', '\\)']], 
	displayMath: [['$$', '$$']] }, 
	svg: { fontCache: 'global' } 
}; 
```
---
## Math Example
- $x = \dfrac{-b \pm \sqrt{b^2 - 4ac}}{2a}$
- Block math: 
$$\int\limits_{t=1}^{\infty} f(t) dt = \dfrac{ \pi + \sqrt{\omega - \sin^2 \theta}}{1+\zeta} $$
---
![by-nc-sa](https://mirrors.creativecommons.org/presskit/buttons/88x31/png/by-nc-sa.png)
