# theBugHunt
A collection of short, daily quizzes to sharpen your dev brain — one puzzle at a time.

# 🧠 Daily JavaScript Quiz Vault

Sharpen your JavaScript skills with daily tricky JS quizzes! Each question includes 4 options and a hidden answer revealed only on click. Perfect for devs, interview prep, or just for fun. Bookmark ⭐ and solve one daily!

---

---

## 📅 Quiz #1

```js
console.log(3 + 2 + "5");
```

**Options:**

* A) 10
* B) 55
* C) "10"
* D) "35"

<details>
<summary>✅ Answer</summary>
**B) 55**  
Explanation: `3 + 2 = 5` (number), then `5 + "5" = "55"` (string).
</details>

---

## 📅 Quiz #2

```js
let result = [1, 2, 3] + [4, 5, 6];
console.log(result);
```

**Options:**

* A) "1,2,34,5,6"
* B) "1,2,3,4,5,6"
* C) "1,2,34,5,6"
* D) "1,2,34,5,6"

<details>
<summary>✅ Answer</summary>
**B) "1,2,34,5,6"**  
Explanation: Arrays convert to strings, and then are concatenated. `"1,2,3" + "4,5,6" = "1,2,34,5,6"`
</details>

---

## 📅 Quiz #3

```js
let x = 5;
console.log(x++ + ++x);
```

**Options:**

* A) 10
* B) 11
* C) 12
* D) 13

<details>
<summary>✅ Answer</summary>
**B) 11**  
Explanation: `x++` is 5, `++x` becomes 6. 5 + 6 = 11.
</details>

---

## 📅 Quiz #4

```js
let obj = {
  valueOf() { return 10; },
  toString() { return "20"; }
};
console.log(obj + "");
```

**Options:**

* A) 10
* B) "20"
* C) "10"
* D) "\[object Object]"

<details>
<summary>✅ Answer</summary>
**C) "10"**  
Explanation: `valueOf()` is prioritized in numeric contexts. `obj + ""` triggers coercion → 10 + "" = "10".
</details>

---

## 📅 Quiz #5

```js
console.log(typeof null);
```

**Options:**

* A) "null"
* B) "undefined"
* C) "object"
* D) "none"

<details>
<summary>✅ Answer</summary>
**C) "object"**  
Explanation: Historical JS bug – `null` is `object` since early spec days.
</details>

---

## 📅 Quiz #6

```js
console.log("5" - - "2");
```

**Options:**

* A) 3
* B) 7
* C) "52"
* D) NaN

<details>
<summary>✅ Answer</summary>
**B) 7**  
Explanation: Unary minus on "-" converts both to numbers → 5 - (-2) = 7
</details>

---

## 📅 Quiz #7

```js
console.log(true + false);
```

**Options:**

* A) 0
* B) 1
* C) truefalse
* D) NaN

<details>
<summary>✅ Answer</summary>
**B) 1**  
Explanation: true → 1, false → 0 → 1 + 0 = 1
</details>

---

## 📅 Quiz #8

```js
console.log("10" - "4" - "3" - 2 + "5");
```

**Options:**

* A) "15"
* B) 1
* C) "15"
* D) "15"

<details>
<summary>✅ Answer</summary>
**D) "15"**  
Explanation: "10" - "4" - "3" - 2 = 1, then 1 + "5" → "15"
</details>

---


## 📅 Quiz 9

### ❓ What will be the output?

```js
let result = [1, 2, 3] + [4, 5, 6];
console.log(result);
```

* A) \[1,2,3,4,5,6]
* B) "123456"
* C) "1,2,34,5,6"
* D) "1,2,3,4,5,6"

<details>
<summary>✅ Answer</summary>

**D) "1,2,34,5,6"** – Actually, it's **"1,2,34,5,6"** because both arrays are converted to strings before the `+`, resulting in concatenated strings.

</details>

---

## 📅 Quiz 10

### ❓ What will this print?

```js
let x = 5;
console.log(x++ + ++x);
```

* A) 10
* B) 11
* C) 12
* D) 13

<details>
<summary>✅ Answer</summary>

**B) 11** – `x++` gives 5, then `++x` increments to 6 and gives 6, so 5 + 6 = 11.

</details>

---

## 📅 Quiz 11

### ❓ What does this output?

```js
console.log("5" - - "2");
```

* A) "7"
* B) 7
* C) NaN
* D) undefined

<details>
<summary>✅ Answer</summary>

**B) 7** – Unary minus on a string coerces it to a number. So "5" - - "2" becomes 5 + 2.

</details>

---

## 📅 Quiz 12

### ❓ What will the output be?

```js
let obj = {
  valueOf() {
    return 10;
  },
  toString() {
    return "20";
  }
};
console.log(obj + "");
```

* A) "\[object Object]"
* B) "20"
* C) "10"
* D) "1020"

<details>
<summary>✅ Answer</summary>

**C) "10"** – `valueOf()` is used for coercion in arithmetic and `+` with string forces object to be primitive. So 10 + "" = "10"

</details>

---

## 📅 Quiz 13

### ❓ Which value is logged?

```js
let result = [] + {};
console.log(result);
```

* A) "\[object Object]"
* B) "{}"
* C) {}
* D) undefined

<details>
<summary>✅ Answer</summary>

**A) "\[object Object]"** – Array becomes "", object becomes "\[object Object]", so final string is "\[object Object]".

</details>

---



> 📌 More quizzes coming soon! Stay tuned and star ⭐ the repo.

---

### 🙌 Want to contribute?

Feel free to open a pull request with your own tricky JS question!

---

### 📬 Connect

Follow [@The_Final_Commit](https://www.instagram.com/the_final_commit/) for daily tech quizzes on Instagram!
