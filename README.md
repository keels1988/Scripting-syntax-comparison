# Scripting-syntax-comparison
If you are new to scripting like me, hopefully these comparisons will help you out

# 🌐 Scripting Language Syntax Comparison

A quick reference comparing six popular scripting languages:

**Python**, **Bash**, **PowerShell**, **Ruby**, **Perl**, and **JavaScript**

---

## 📌 Table of Contents

- [1. Variable Declaration](#1-variable-declaration)
- [2. Print to Console](#2-print-to-console)
- [3. If Statement](#3-if-statement)
- [4. For Loop](#4-for-loop)
- [5. Function Definition](#5-function-definition)
- [6. Comments](#6-comments)
- [💡 Summary](#-summary)
- [🛠️ Contribute](#️-contribute)

---

## 1. 🧠 Variable Declaration

| Language     | Syntax                        |
|--------------|-------------------------------|
| Python       | `name = "Alice"`              |
| Bash         | `name="Alice"`                |
| PowerShell   | `$name = "Alice"`             |
| Ruby         | `name = "Alice"`              |
| Perl         | `$name = "Alice";`            |
| JavaScript   | `let name = "Alice";`         |

---

## 2. 📤 Print to Console

| Language     | Syntax                          |
|--------------|---------------------------------|
| Python       | `print("Hello")`                |
| Bash         | `echo "Hello"`                  |
| PowerShell   | `Write-Output "Hello"`          |
| Ruby         | `puts "Hello"`                  |
| Perl         | `print "Hello\n";`              |
| JavaScript   | `console.log("Hello");`         |

---

## 3. 🔍 If Statement

<details>
<summary>Click to expand</summary>

```python
if x == 5:
    print("yes")
```

```bash
if [ "$x" -eq 5 ]; then echo "yes"; fi
```

```powershell
if ($x -eq 5) { Write-Output "yes" }
```

```ruby
if x == 5
  puts "yes"
end
```

```perl
if ($x == 5) {
    print "yes\n";
}
```

```javascript
if (x === 5) {
    console.log("yes");
}
```

</details>

---

## 4. 🔁 For Loop

<details>
<summary>Click to expand</summary>

```python
for i in range(3):
    print(i)
```

```bash
for i in {0..2}; do echo $i; done
```

```powershell
for ($i=0; $i -lt 3; $i++) { $i }
```

```ruby
3.times { |i| puts i }
```

```perl
for ($i = 0; $i < 3; $i++) {
    print "$i\n";
}
```

```javascript
for (let i = 0; i < 3; i++) {
    console.log(i);
}
```

</details>

---

## 5. 🧹 Function Definition

<details>
<summary>Click to expand</summary>

```python
def greet():
    print("Hi")
```

```bash
greet() { echo "Hi"; }
```

```powershell
function Greet {
    Write-Output "Hi"
}
```

```ruby
def greet
  puts "Hi"
end
```

```perl
sub greet {
    print "Hi\n";
}
```

```javascript
function greet() {
    console.log("Hi");
}
```

</details>

---

## 6. 💬 Comments

| Language     | Syntax                 |
|--------------|------------------------|
| Python       | `# This is a comment`  |
| Bash         | `# This is a comment`  |
| PowerShell   | `# This is a comment`  |
| Ruby         | `# This is a comment`  |
| Perl         | `# This is a comment`  |
| JavaScript   | `// This is a comment` |

---

## 💡 Summary

| Language     | Highlights |
|--------------|-----------|
| **Python**   | Clean, readable, great for automation |
| **Bash**     | Ideal for Unix/Linux scripting |
| **PowerShell** | Strong for Windows admin with objects |
| **Ruby**     | Elegant, expressive syntax |
| **Perl**     | Powerful for text processing |
| **JavaScript** | Web-first, but full-stack with Node.js |

---

## 🛠️ Contribute

Feel free to fork this repo and add:
- More languages (Go, Rust, etc.)
- Additional syntax examples (switch, case, array handling)
- Real-world script snippets

Pull requests are welcome!

---

🌟 If this helped, give the repo a ⭐ and share it with other devs!

