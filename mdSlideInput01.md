# Hello
## Slide 0

This is a Markdown slide.

---

<section>
    <h3>Slide 1: Flowchart</h3>
        <div class="mermaid">
        %%{init: {'theme': 'normal', 'themeVariables': { 'darkMode': true }}}%%
        flowchart TD
			A[Start] --> B{Is it?};
            B -- Yes --> C[OK];
            C --> D[Rethink];
            D --> B;
            B -- No ----> E[End];
        </div>
		<aside class="notes">
			Shhh, these are your private notes 📝
		 </aside>
</section>

---

# Slide 2: Math

Inline math: $E = mc^2$

Block math:
$$
\int_{a}^{b} x^2 dx = \frac{b^3 - a^3}{3}
$$

Note:
กด  S บน  keyboard แล้ว จะมี speaker notes support 

---

# Slide 3: Table 
## Table

| Name   | Age |
|--------|-----|
| Alice  | 24  |
| Bob    | 30  |

---

# Slide 4: List
## List

- Item 1
- Item 2
  - Subitem
	- Test

---

<section>
<h3>Slide 5: Mermaid Graph</h3><div class="mermaid">
%%{init: { "theme": "normal" } }%%
graph TD
  A[Start] --> B{Is it?}
  B -- Yes --> C[OK]
  B -- No --> D[Retry]
</div>
</section>

---

## Slide 6: Test

- drama
	- you มาไหม
		- i ไปด้วย
			- we ไปด้วยกัน

---

## Slide 7: Code

```js
const deck = new Reveal({ 
	plugins: [Markdown, Highlight], }); 
deck.initialize(); 
```

---

<section>
<h3>Slide 8: Mermaid theme</h3>
<div class="mermaid">
%%{init: { "theme": "forest" } }%%
graph TD
	A(Forest) --> B[/Another/]
	A --> C[End]
	  subgraph section
	  B
	  C
	  end      
</div>
</section>

---

## Slide 9:  To do 
-  *ไทย*
- **ทำไม**

---

## Slide 10: XOX
|  Name      | Age |  Why      |
|------------|-----|-----------|
| $\alpha$   |  0  | A $\to$ B |
| $\beta$    |  1  | A $\cup$ B|
| $\gamma$   |  2  | A $\cap$ B|

Note:
This will only display in the notes window.

---

![by-nc-sa](https://mirrors.creativecommons.org/presskit/buttons/88x31/png/by-nc-sa.png)