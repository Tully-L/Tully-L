  # GitHub 主页贪吃蛇（配置片段）

在个人主页 `README.md` 里加上：

```markdown
![GitHub Snake Animation](https://raw.githubusercontent.com/Tully-L/Tully-L/output/github-contribution-grid-snake.svg)
![GitHub Snake Animation Dark](https://raw.githubusercontent.com/Tully-L/Tully-L/output/github-contribution-grid-snake-dark.svg)
```

如果你希望自动根据明暗主题显示：

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Tully-L/Tully-L/output/github-contribution-grid-snake-dark.svg">
  <img src="https://raw.githubusercontent.com/Tully-L/Tully-L/output/github-contribution-grid-snake.svg" alt="GitHub Snake Animation"/>
</picture>
```
