# 科学排版

## 正体与斜体

- **变量、物理量**：使用 *斜体*（italic）
- **单位**：使用 **正体**（upright）

---

## 不同的排版引擎

- **TeX**：由高德纳（Donald Knuth）开发的排版系统原始版本  
- **LaTeX**：基于 TeX，提供宏与结构化文档工具  
- **pdfTeX**：支持生成 `.pdf` 和 `.dvi` 两种格式  
- **ConTeXt**：另一套基于 TeX 的排版宏包系统  
- **XeTeX**：增强字体功能，支持 Unicode 和系统字体（如 `\xeCJK`），若要使用自己的字体，则用XeTeX

现在一般使用pdfTeX/XeTeX

---

## 源文件结构

- `\documentclass[options]{class}`

   class的选项有：
  





- `usepackage{宏包名称}`





## 基本命令和规定






## 表格样例

左对齐l,右对齐r，中间对齐c，|表示竖直边框 
每一行用&来分隔，最后\hline表示添加横向直线

## 处理流程

经典的是先生成.dvi，再生成.pdf，现在可以直接

只能通过生成pdf来插入位图（.png,.jpg,……），而.dvi不支持


## 注意

LaTeX里面的图片和表格是无法规定出现在哪些位置的（随机），如何排版是计算机决定

- 希腊字母

| 字符 | LaTeX     | 字符 | LaTeX    |
| -- | --------- | -- | -------- |
| α  | `\alpha`  | β  | `\beta`  |
| γ  | `\gamma`  | δ  | `\delta` |
| ω  | `\omega`  | ζ  | `\zeta`  |
| η  | `\eta`    | θ  | `\theta` |
| λ  | `\lambda` | μ  | `\mu`    |
| π  | `\pi`     | ρ  | `\rho`   |
| σ  | `\sigma`  | τ  | `\tau`   |
| φ  | `\phi`    | χ  | `\chi`   |

| 字符 | LaTeX    | 字符 | LaTeX     |
| -- | -------- | -- | --------- |
| Γ  | `\Gamma` | Δ  | `\Delta`  |
| Θ  | `\Theta` | Λ  | `\Lambda` |
| Π  | `\Pi`    | Σ  | `\Sigma`  |
| Φ  | `\Phi`   | Ω  | `\Omega`  |

- 数学符号

| 字符 | LaTeX      | 字符 | LaTeX     |
| -- | ---------- | -- | --------- |
| ≠  | `\neq`     | ≈  | `\approx` |
| ∞  | `\infty`   | ∫  | `\int`    |
| ∂  | `\partial` | ∑  | `\sum`    |
| ∀  | `\forall`  | ∃  | `\exists` |
| ±  | `\pm`      | ∝  | `\propto` |
| ⋅  | `\cdot`    | ×  | `\times`  |
| ≤  | `\leq`     | ≥  | `\geq`    |

- 其他字符

| 字符          | LaTeX       | 说明       |
| ----------- | ----------- | -------- |
| $\vec{x}$   | `\vec{x}`   | 向量符号     |
| $\check{x}$ | `\check{x}` | 字母上加 ˇ   |
| $\hbar$     | `\hbar`     | 约化普朗克常数  |
| $\odot$     | `\odot`     | 点乘符号     |
| $\aleph$    | `\aleph`    | 阿列夫（集合论） |
| $\S$        | `\S`        | 段落符号     |


| 字符 | LaTeX             |
| -- | ----------------- |
| ⇒  | `\Rightarrow`     |
| ⇐  | `\Leftarrow`      |
| ⇔  | `\Leftrightarrow` |
| →  | `\to`             |
| ↦  | `\mapsto`         |


- 集合符合

| 字符 | LaTeX       |
| -- | ----------- |
| ∈  | `\in`       |
| ∉  | `\notin`    |
| ⊂  | `\subset`   |
| ⊆  | `\subseteq` |
| ∪  | `\cup`      |
| ∩  | `\cap`      |

- 箭头

| 字符 | LaTeX        |
| -- | ------------ |
| ↑  | `\uparrow`   |
| ↓  | `\downarrow` |
| ⇑  | `\Uparrow`   |
| ⇓  | `\Downarrow` |


