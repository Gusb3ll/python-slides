---
theme: seriph
background: https://konachan.net/image/29ca055696ffd0e5fef746c98be86d6e/Konachan.com%20-%20343005%20blue_archive%20book%20cherry%20food%20fruit%20gray_hair%20halo%20long_hair%20purple_eyes%20shaoxiao%20skirt%20sorasaki_hina%20thighhighs%20zettai_ryouiki.jpg
class: 'text-center'
highlighter: shiki
lineNumbers: true
info: |
  ## Python for beginner slide
drawings:
  persist: false
css: unocss
---

# Python for beginner?

A slide by gusbell l.

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Start <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <!-- <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button> -->
  <a href="https://github.com/gusb3ll" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---

# Let's start with the simple

```py
print("Hello World")
# "Hello World"

text = "Hello World"
print(text)
# "Hello World"

print(1)
# 1
```

---

# Data types

```text
Text : String

Numeric : Integer, Float, Complex

Sequence : List [], Tuple (), Range

Mapping : Dictionary

Set : Set, FrozenSet

Boolean : Bool # True, false

Binary : Bypes, ByteArray, MemView

None : None
```

---

# Ex

```
"Hello World" => String


177013 => Integer

122.42 => Float

[1, 2, 3] => List

(1, 2, 3) => Tuple


{ 1: "one", 2: "two" } => Dictionary

{1, 2, 3} => Set
```

---

# How do we find types?

```py
print(type("Hello World"))
# str

i = 12345
print(type(i))
# int
```

---

# How to get data from outside the garden
