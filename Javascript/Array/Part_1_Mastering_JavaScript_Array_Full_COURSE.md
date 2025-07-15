# 📘 Mastering JavaScript Array || Full COURSE || Part 1

**✍️ Noted By:** MD SOHAG MIYA <br>
📺 Reference Video: [https://youtu.be/cnClUIjNvGw?si=\_AXCHAEaQ5Jwq0hQ](https://youtu.be/cnClUIjNvGw?si=_AXCHAEaQ5Jwq0hQ)

---

## 📚 Course Topics (Part 1)

1. What is an Array?
2. কিভাবে Array তৈরি করা যায়?
3. কিভাবে Array থেকে Element পাওয়া যায়?
4. কিভাবে Array-তে Element যোগ করা যায়?
5. কিভাবে Array থেকে Element মুছে ফেলা যায়?
6. কিভাবে একটি Array কপি/ক্লোন করা যায়?
7. কিভাবে যাচাই করব একটি value অ্যারে কিনা?

---

## 🎬 Watch Full Video (Click to Open)

[![Mastering JavaScript Array - Part 1](https://img.youtube.com/vi/cnClUIjNvGw/maxresdefault.jpg)](https://youtu.be/cnClUIjNvGw?si=_AXCHAEaQ5Jwq0hQ)

---

## 📝 NOTES:

---

### 1. What is an Array?

Programming এ  Array কে  বলা হয় একটা  Collection of Element
Element যেমন :

```js
const a = 10  
const b = 20
```

Array হচ্ছে এক বা একাধিক element এর একটা collection.

```js
[100, true, "Hello", {}]
```

**element** = 10, true, "Hello", {} এগুলা এক একটা element
**position/index** = 100 = 0, true = 1, "Hello" = 2, {} = 3  কারণ index 0 থেকে শুরু হয়।
**Length** = Array তে আমরা যতগুলো element রাখি, এগুলা নির্ধারণ করে এর length কত হবে।

> **Note:**
> Array হচ্ছে একটা data structure, যে data structure এর মধ্যে আমরা continues data রাখতে পারি এবং প্রতিটা element আলাদা আলাদা type হতে পারে।
> Array index সবসময় 0 থেকে শুরু হয়, index মানে হলো element এর position মানে element টা কোন position এ আছে।
> এবং Array তে যতগুলো element আমরা রাখি তা নির্ধারণ করে এর length কত হবে।

---

### 2. Array কে কী কী উপায়ে Create করা যায়?

Array আমরা multiple উপায়ে create করতে পারি।

**must state forward way হলো:**

```js
const sald = ["tomato", "caa", "etc"]
```

**with Array construction:**

```js
new Array("A", "B")
```

> **Note:**
> যখন constructor দিয়ে একটা argument pass করা হয় Array constructor এর মধ্যে, তাহলে একটা array তৈরি হয়,
> সেই array টা তৈরি হয় ওই সংখ্যক empty element দিয়ে, যা number pass করা হয়।

যেমন:

```js
new Array(10)
```

তাহলে একটা array তৈরি হবে, সাথে 10টা empty element।

---

### 3. How to get Element From an Array?

```js
const arr = ["A", "B", "C"]
```

আমরা এভাবে তুলতে পারি যেমন:

```js
arr[element]
const element = arr[index]
```

আমরা length ধরে বা loop চালিয়ে চাইলে প্রতিটা array element get করতে পারি।

---

### 4. How To add Element in an Array?

**Push**

```js
arr.push()
```

> push সবসময় array এর শেষে element ঢুকিয়ে দেয়।
> push array কে modify করার পর সেটার length return করে।

**Unshift**

```js
arr.unshift()
```

> এটা দিয়ে array এর শুরুতে element কে ঢুকিয়ে দিতে পারি।

> **Note:** push, unshift হচ্ছে **mutable**।

---

### 5. How to remove element from an Array?

**Pop**

```js
arr.pop()
```

> pop() method দিয়ে আমরা শেষে থেকে element delete করতে পারি।

**Shift**

```js
arr.shift()
```

> shift() method দিয়ে আমরা শুরু থেকে element delete করতে পারি।

> **Note:** pop, shift এই দুইটা method ও **mutable** মানে main array কে সরাসরি change/mutate করে।

---

### 6. How to copy and clone an Array in JS?

copy বা clone হচ্ছে একটা array এর মতোই আরেকটা array তৈরি করা, কিন্তু reference আলাদা হবে।

**slice():**

```js
arr.slice()
```

> এই method টা call বা invoke করলে আরেকটা array return করে
> যদিও এর আরও কাজ আছে — আমরা সামনে দেখবো।

> **Note:** slice হলো **immutable** — মানে এটা main array কে সরাসরি change করে না, নতুন array return করে।

---

### 7. How to determine if a value is an Array?

কি করে আমি বুঝবো একটা value array কিনা? বা একটা array আসলেই array কিনা?

```js
Array.isArray(value)
```

> এটা দিয়ে আমরা check করতে পারি, একটা value আসলে array কিনা।

---
