# 多轮对话 Agent 推理系统优化小组报告

这是一个中文 LaTeX 报告项目，主文件为 `main.tex`，各章节放在 `sections/` 目录中。

## 编译方式

推荐使用 XeLaTeX：

```bash
latexmk -xelatex main.tex
```

清理编译产物：

```bash
latexmk -C
```

## 项目结构

- `main.tex`：报告入口、导言区和章节引用
- `sections/`：各章节正文
- `references.bib`：参考文献
- `latexmkrc`：latexmk 编译配置
- `.gitignore`：忽略 LaTeX 编译产物

## 报告章节

- 项目背景与目标
- 组员分工
- 问题拆解
- 性能分析：核心指标只关注 TTFT，同时分析 KV cache、prefill、排队时间等影响因素
- 尝试策略
- 最终策略
- 总结与展望
