# Features gh
## ✅ Lists
- [✔] [symbl](https://symbl.cc/)
- [☑] Item 1
- [❌] Item 2
  - [❎] Subitem

## ✅ Tables ❎

| Name       | Age | City      |
|------------|-----|-----------|
| Alice      | 30  | New York  |
| Bob        | 25  | Los Angeles|
| Charlie    | 35  | Chicago   |

## List

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

## Diagram

- ex01

```mermaid
sequenceDiagram
    A ->>B : Hello B, how are you?
    B-->>J: How about you J?
    B--x A: I am OK thanks!
    B-x J: I am fine thanks!
    Note right of J: B thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

    B-->A: Checking with J...
    A->J: Yes... J, how are you?
```

- ex02

```mermaid
sequenceDiagram
    F->>B: I smile for you.
    B->>F:F, you are cute.
```
- ex03

```mermaid
timeline
    title School i have been completed โรงเรียนของหนู
    1996 : PC
    1999 : PSU-HYI
         : PSU-PN
    2010 : CU
    2016 : HD
```
- ex 04

```mermaid
sequenceDiagram
    A ->>B : Hello B, how are you?
    B-->>J: How about you J?
    B--x A: I am OK thanks!
    B-x J: I am fine thanks!
    Note right of J: B thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

    B-->A: Checking with J...
    A->J: Yes... J, how are you?
```

- ex 05

```mermaid
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
```

- ex 06

```mermaid
pie title What Voldemort doesn't have?
         "FRIENDS" : 2
         "FAMILY" : 3
         "NOSE" : 45
```

- ex 07
	- [fontawesome v4 icons](https://fontawesome.com/v4/icons/)

```mermaid
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
```

## ✅ Code Block

```js
console.log("Hello from JS");
alert( 'Hello, world!' );
```

## ✅ Math

Inline math: $\gamma = \frac{1}{\sqrt{1 - v^2/c^2}}$

Block math:

more
$$
\exists x \forall y (Rxy \equiv Ryx)
$$

$v(t) = v_0 + \frac{1}{2}at^2$

$\gamma = \dfrac{1}{\sqrt{1 - v^2/c^2}}$  

$\exists x \forall y (Rxy \equiv Ryx)$

$p \wedge q \models p$

$\Box\diamond p\equiv\diamond p$

$\int_{0}^{1} x dx = \left[\dfrac{1}{2}x^2\right]_{0}^{1} = \dfrac{1}{2}$

$e^x = \sum\limits_{n=0}^\infty \dfrac{x^n}{n!} = \lim_{n\rightarrow\infty} (1+x/n)^n$
