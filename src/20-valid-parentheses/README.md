<h1 align="center">
  有效的括号
<h1>

> leetcode [valid-parentheses](https://leetcode-cn.com/problems/valid-parentheses/)

## 题目描述(难度级别🌟 )

给定一个只包括 `(`，`)`，`{`，`}`，`[`，`]` 的字符串，判断字符串是否有效。

有效字符串需满足：

- 左括号必须用相同类型的右括号闭合。
- 左括号必须以正确的顺序闭合。

注意空字符串可被认为是有效字符串。

## 示例

示例1

```
输入: "()"
输出: true
```

示例2

```
输入: "()[]{}"
输出: true
```

示例3

```
输入: "(]"
输出: false
```

示例4

```
输入: "([)]"
输出: false
```

示例5

```
输入: "{[]}"
输出: true
```