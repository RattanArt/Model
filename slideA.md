# Demo
ตัวอย่าง **Markdown** $a \in \mathbb{R}^+$.
---

## ex01

<div class="mermaid">
sequenceDiagram
    A ->>B : Hello B, how are you?
    B-->>J: How about you J?
    B--x A: I am OK thanks!
    B-x J: I am fine thanks!
    Note right of J: B thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

    B-->A: Checking with J...
    A->J: Yes... J, how are you?
</div>
---

## ex02

<div class="mermaid">
sequenceDiagram
    F->>B: I smile for you.
    B->>F:F, you are cute.
</div>
- ex03

<div class="mermaid">
timeline
    title School i have been completed โรงเรียนของหนู
    1996 : PC
    1999 : PSU-HYI
         : PSU-PN
    2010 : CU
    2016 : HD
</div>
---

## ex 04

<div class="mermaid">
sequenceDiagram
    A ->>B : Hello B, how are you?
    B-->>J: How about you J?
    B--x A: I am OK thanks!
    B-x J: I am fine thanks!
    Note right of J: B thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

    B-->A: Checking with J...
    A->J: Yes... J, how are you?
</div>
---

## ex 05

<div class="mermaid">
gitGraph:
    commit "Ashish"
    branch newbranch
    checkout newbranch
    commit id:"1111"
    commit tag:"test"
    checkout main
    commit type: HIGHLIGHT
    commit
    merge newbranch
    commit
    branch b2
    commit
</div>
---

## ex 06

<div class="mermaid">
pie title What Voldemort doesn't have?
         "FRIENDS" : 2
         "FAMILY" : 3
         "NOSE" : 45
</div>
---

## ex 07
- [fontawesome v4 icons](https://fontawesome.com/v4/icons/)
---
<div class="mermaid">
mindmap
  root)mindmap(
    Origins
	::icon(fa fa-refresh fa-spin)
      Long history
      ::icon(fa fa-book)
      Popularisation
	  ::icon(fa fa-car)
        British popular psychology author Tony Buzan
    Research
	::icon(fa fa-cog fa-spin)
      On effectiveness<br/>and features
      On Automatic creation
        Uses
		::icon(fa fa-spinner fa-pulse)
            Creative techniques
            Strategic planning
            Argument mapping
    Tools
	::icon(fa fa-spinner fa-spin)
      Pen and paper
      Mermaid
</div>
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
