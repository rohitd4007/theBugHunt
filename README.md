# theBugHunt
A collection of short, daily quizzes to sharpen your dev brain — one puzzle at a time.

# 🧠 Daily JavaScript Quiz Vault

Sharpen your JavaScript skills with daily tricky JS quizzes! Each question includes 4 options and a hidden answer revealed only on click. Perfect for devs, interview prep, or just for fun. Bookmark ⭐ and solve one daily!

---

## 📅 Day 1

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

## 📅 Day 2

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

## 📅 Day 3

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

## 📅 Day 4

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

## 📅 Day 5

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

Follow [@https://www.instagram.com/the_final_commit/](https://www.instagram.com/the_final_commit/) for daily tech quizzes on Instagram!
