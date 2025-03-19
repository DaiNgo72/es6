# Bài tập: Rest Parameters
## 1.
```js
const validateEmails = (...emails) => {
  // Viết code ở đây
};

console.log(validateEmails("user@example.com", "admin@domain.com", "invalidemail"));
// Output: { valid: ["user@example.com", "admin@domain.com"], invalid: ["invalidemail"] }
```

## 2.
```js
const mergeProducts = (...productLists) => {
  // Viết code ở đây
};

const list1 = [
  { id: 1, name: "Laptop" },
  { id: 2, name: "Phone" }
];

const list2 = [
  { id: 2, name: "Phone" },
  { id: 3, name: "Tablet" }
];

console.log(mergeProducts(list1, list2));
/*
Output:
[
  { id: 1, name: "Laptop" },
  { id: 2, name: "Phone" },
  { id: 3, name: "Tablet" }
]
*/
```
## 3.
```js
const formatPrices = (currency, ...prices) => {
  // Viết code ở đây
};

console.log(formatPrices("USD", 10, 20, 30));
// Output: ["$10.00", "$20.00", "$30.00"]

console.log(formatPrices("VND", 10000, 20000, 30000));
// Output: ["10,000 VND", "20,000 VND", "30,000 VND"]
```
