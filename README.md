如何用 VS Code 打开和编写
项目结构说明

  Templates/  
  ├── TemplateLatex/ ← 主文件夹   
  │ ├── Project Thesis.tex ← 主 tex 文件  
  │ ├── *.tex ← 各章节内容  
  │ ├── Figures/ ← 图片素材  
  │ └── Project Thesis.pdf← 编译后的 PDF  

  
### 0. pull
```bash
mkdir (随便起个名字，叫AA好了)
cd AA
git clone https://github.com/LiuJingting0201/eMobilityReport.git
git pull
```
不要打开单独的tex文件

  
### 1. 安装工具（首次需要）

- 安装 [TeX Live](https://www.tug.org/texlive/) 或 MiKTeX（LaTeX 发行版）
- 安装 VS Code 插件：**LaTeX Workshop**

---

### 2. 编译 PDF 报告

打开 `TemplateLatex` 文件夹后：

- 打开 `Project Thesis.tex`
- 按下 `Ctrl + Alt + B` 自动编译
- 编译后的 PDF 会在右侧显示，并生成 `Project Thesis.pdf`

---

### 3. 修改内容

- 编辑各章节 `.tex` 文件（如 `Motor_model.tex`）
- 新图像放在 `Figures/` 文件夹里，并在 `.tex` 中引用
- 如果没有图，可以先插入占位图 `ExFig.pdf`

---


