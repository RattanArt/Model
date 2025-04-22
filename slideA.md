# Demo
ตัวอย่าง **Markdown** $a \in \mathbb{R}^+$.
<div class="mermaid">
 sequenceDiagram
	A->>B: I like you.
	B->>C: C, you are cute.
	C->>A: A, Are you OK?
</div>	

---
## Diagram A
<div class="mermaid">	
graph LR
	A --> E
	E --> B
<div>
---
	
## Diagram
```mermaid
graph TD
	A --> E
	E --> B
	B --> C
	B --> D
	D --> E
```
---

## Mind map
```mermaid
mindmap
  root)mindmap(
    Origins	
      Long history      
      Popularisation	  
        British popular psychology author Tony Buzan
    Research	
      On effectiveness<br/>and features
      On Automatic creation
        Uses		
            Creative techniques
            Strategic planning
            Argument mapping
    Tools	
      Pen and paper
      Mermaid
```
---
	
## Code
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
