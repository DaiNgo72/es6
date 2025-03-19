# Bài tập: Spread Operator
## 1. Kết hợp hai object cấu hình hệ thống
```js
const mergeConfigs = (defaultConfig, userConfig) => {
  // Viết code ở đây
};

const defaultConfig = { theme: "light", language: "en", showNotifications: true };
const userConfig = { language: "vi", showNotifications: false };

console.log(mergeConfigs(defaultConfig, userConfig));
/*
Output:
{
  theme: "light",
  language: "vi",
  showNotifications: false
}
*/
```
## 2. Sao chép và cập nhật đối tượng (Deep Copy)
- Bạn cần sao chép một đối tượng và cập nhật một số thuộc tính mà không làm thay đổi đối tượng gốc.
```js
const updateUser = (user, updates) => {
  // Viết code ở đây
};

const user = { id: 1, name: "Alice", age: 25 };
const updatedUser = updateUser(user, { age: 26, city: "Hanoi" });

console.log(updatedUser); 
// Output: { id: 1, name: "Alice", age: 26, city: "Hanoi" }
console.log(user); 
// Output: { id: 1, name: "Alice", age: 25 } (Không bị thay đổi)
```
