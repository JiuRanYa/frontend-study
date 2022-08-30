## 一. Usual Commonds
### 1. Delete
delete this line：

dd：

shift + v/V d

D: delete after the cursor

### 2. Insert
Four modes： 

i：left side of cursor

I：jump to the first  non whitespace character in this line

a：right side of cursor

A：jump to the end of this line

### 3. View mode
#### 3.1 Virtual mode

shift + v : normal mode -> usually using copy some words

#### 3.1 Virtual line mode

shift + V : the whole line

### 4. Screen
zz：jump to the middle of screen

### 5. Operations
u: undo

## 二.Customization

### 1. usual customizing vim View

relactivenumber:

```
:set relativenumber

or

:set rnu
```

## 三. Text maniputation

S: delete all line and into insert mode

t: find letter and move left side of the target

number + j/k : jump (the number) line

{} : move to the next paragraph
