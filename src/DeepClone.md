# 一行代码实现深拷贝

```javascript
const origin = [{name: 'ZhangSan', age: 18, sex: 'men', isStudent: true}]

// 一行代码实现深拷贝
const target = JSON.parse(JSON.stringify(origin))
```

