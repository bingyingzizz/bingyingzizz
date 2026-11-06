### 数学星图 MathGalaxy

把数学概念按依赖关系画成一张可漫游的星图 —— 从 ZF 公理一路到凝聚态数学。
每个概念一个节点、一份独立网页，推导的证明写在边上。

**[🔭 在线浏览](https://bingyingzizz.github.io/mathgalaxy/)** ·
**[📦 源码](https://github.com/bingyingzizz/MathGalaxy)**

纯静态、零依赖：双击 `index.html` 就能跑，不用装任何东西。
图上的四种边 —— 黑箭头 = 推出 · 黑直线 = 等价 · 蓝线 = 定义引用 · 紫虚线 = 跨领域类比（弱边）；
另有一类粉箭头的「推论」边：结论成立，但不参与分层。

也留了给 AI 的入口：[`llms.txt`](https://github.com/bingyingzizz/MathGalaxy/blob/main/llms.txt)
是整张图的检索协议 —— 先用 `dist/alias.md` 把大白话（或英文名）换成节点 id，
再沿 `dist/index.md` → `dist/index/<星团>.md` → `dist/nodes/<id>.md` 读下去；
中文是原本，常见概念另有 `nodes/<id>.en.md` 英文页。
`dist/graph.json` / `dist/graph.md` 是全量导出，适合下载，不适合检索。

方向上偏本科以上的数学：数理逻辑 · 集合论 · 序理论 · 拓扑 · 抽象代数 · 分析 · 实变与泛函 ·
范畴论 · 同调代数 · 凝聚态数学 · 解析空间 · 复变函数 · 微分几何 · 数论。
