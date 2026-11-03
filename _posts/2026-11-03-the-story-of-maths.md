---
layout: post
title: "BBC 纪录片《数学的故事》：四集人物与知识图谱"
date: 2026-11-03 12:00:00 +0800
categories: 数学
excerpt: "从古埃及、巴比伦和希腊，到东方数学、微积分、无穷与现代数学：沿着人物与思想的联系，重新走过纪录片的四集。"
---

看完 BBC 纪录片 <em>The Story of Maths</em>（《数学的故事》）后，我想把四集里的数学家、文明和重要想法连成一张更完整的地图。

图中每个人物节点都列出中英文名、所属地区和代表贡献。**实线**表示知识传承、影响或问题的延续，**虚线**表示平行发展、争论或较早出现的相似想法；连线是学习线索，不代表所有关系都能简单归结为单向影响。

<figure class="math-map">
  <div class="math-map-scroll" role="region" aria-label="《数学的故事》四集人物与知识关系图，可横向和纵向滚动查看" tabindex="0">
    <pre class="mermaid">
flowchart TB
  LG["图例：🟤 古代　🟡 中世纪　🔵 近代　🟣 现代&lt;br/&gt;实线＝影响 / 传承　虚线＝平行 / 争论 / 先声"]

  subgraph E1["① 宇宙语言：古埃及 / 巴比伦 / 希腊"]
    direction LR
    A1["🟤 阿赫摩斯 · Ahmes&lt;br/&gt;古埃及 / Ancient Egypt&lt;br/&gt;莱因德纸草书：分数与面积问题"]
    B1["🟤 巴比伦泥板 · Babylonian tablets&lt;br/&gt;美索不达米亚 / Mesopotamia&lt;br/&gt;六十进制、方程与天文计算"]
    P["🟤 毕达哥拉斯 · Pythagoras&lt;br/&gt;古希腊 / Ancient Greece&lt;br/&gt;数与比例；勾股传统"]
    PL["🟤 柏拉图 · Plato&lt;br/&gt;古希腊 / Ancient Greece&lt;br/&gt;学院传统；重视数学证明"]
    EU["🟤 欧几里得 · Euclid&lt;br/&gt;亚历山大城 / Alexandria&lt;br/&gt;《几何原本》：公理化几何"]
    AR["🟤 阿基米德 · Archimedes&lt;br/&gt;叙拉古 / Syracuse&lt;br/&gt;穷竭法、面积与体积"]
    ER["🟤 埃拉托色尼 · Eratosthenes&lt;br/&gt;昔兰尼与亚历山大 / Cyrene &amp; Alexandria&lt;br/&gt;估算地球周长；筛法"]
    HY["🟤 希帕蒂娅 · Hypatia&lt;br/&gt;亚历山大城 / Alexandria&lt;br/&gt;数学教学与古典著作评注"]
    GR2["🟤 丢番图 · Diophantus&lt;br/&gt;阿波罗尼奥斯 · Apollonius&lt;br/&gt;托勒密 · Ptolemy&lt;br/&gt;亚历山大传统 / Alexandria&lt;br/&gt;数论方程 · 圆锥曲线 · 天文学"]
  end

  subgraph E2["② 东方奇才：中国 / 印度 / 波斯与伊斯兰学术世界 / 意大利"]
    direction LR
    LIU["🟡 刘徽 · Liu Hui&lt;br/&gt;中国 / China&lt;br/&gt;割圆术；为《九章算术》作注"]
    Q["🟡 秦九韶 · Qin Jiushao&lt;br/&gt;中国 / China&lt;br/&gt;《数书九章》；一次同余方程"]
    ARY["🟡 阿耶波多 · Aryabhata&lt;br/&gt;印度 / India&lt;br/&gt;位值记数；天文与正弦表"]
    BRA["🟡 婆罗摩笈多 · Brahmagupta&lt;br/&gt;印度 / India&lt;br/&gt;零、负数的运算规则"]
    BHA["🟡 婆什迦罗二世 · Bhaskara II&lt;br/&gt;印度 / India&lt;br/&gt;代数；变化问题的早期研究"]
    MAD["🟡 玛德哈瓦 · Madhava&lt;br/&gt;印度，喀拉拉 / Kerala&lt;br/&gt;无穷级数；圆周率计算"]
    KH["🟡 花剌子米 · al-Khwarizmi&lt;br/&gt;花剌子模与巴格达 / Khwarazm &amp; Baghdad&lt;br/&gt;系统发展代数学；算法一词的词源"]
    OK["🟡 奥马尔·海亚姆 · Omar Khayyam&lt;br/&gt;波斯 / Persia&lt;br/&gt;用圆锥曲线求解三次方程"]
    FI["🟡 斐波那契 · Fibonacci&lt;br/&gt;比萨，意大利 / Pisa, Italy&lt;br/&gt;《算盘书》；传播印度—阿拉伯数字"]
    TA["🔵 塔尔塔利亚 · Tartaglia&lt;br/&gt;意大利 / Italy&lt;br/&gt;三次方程的解法"]
    CA["🔵 卡尔达诺 · Cardano&lt;br/&gt;意大利 / Italy&lt;br/&gt;《大术》刊载三次方程解法"]
    FE["🔵 费拉里 · Ferrari&lt;br/&gt;意大利 / Italy&lt;br/&gt;发现四次方程的一般解法"]
  end

  subgraph E3["③ 空间的边界：欧洲近代数学"]
    direction LR
    PF["🔵 皮耶罗·德拉·弗朗切斯卡&lt;br/&gt;Piero della Francesca&lt;br/&gt;意大利 / Italy&lt;br/&gt;透视法与几何"]
    DE["🔵 勒内·笛卡尔 · René Descartes&lt;br/&gt;法国 / France&lt;br/&gt;解析几何；笛卡尔坐标"]
    FM["🔵 皮埃尔·德·费马 · Pierre de Fermat&lt;br/&gt;法国 / France&lt;br/&gt;数论、极值与切线方法"]
    NE["🔵 艾萨克·牛顿 · Isaac Newton&lt;br/&gt;英格兰 / England&lt;br/&gt;微积分；运动与引力定律"]
    LE["🔵 戈特弗里德·莱布尼茨&lt;br/&gt;Gottfried Wilhelm Leibniz&lt;br/&gt;德意志地区 / German lands&lt;br/&gt;独立发展微积分；创用重要记号"]
    EU2["🔵 莱昂哈德·欧拉 · Leonhard Euler&lt;br/&gt;瑞士 / Switzerland&lt;br/&gt;分析学、数论；丰富数学记号"]
    GA["🔵 卡尔·弗里德里希·高斯&lt;br/&gt;Carl Friedrich Gauss&lt;br/&gt;德意志地区 / German lands&lt;br/&gt;数论、测地学与微分几何"]
    BO["🔵 亚诺什·鲍耶 · János Bolyai&lt;br/&gt;匈牙利 / Hungary&lt;br/&gt;独立发展非欧几何"]
    LO["🔵 尼古拉·罗巴切夫斯基&lt;br/&gt;Nikolai Lobachevsky&lt;br/&gt;俄罗斯 / Russia&lt;br/&gt;独立发展双曲几何"]
    RI["🔵 格奥尔格·黎曼 · Bernhard Riemann&lt;br/&gt;德意志地区 / German lands&lt;br/&gt;黎曼几何；提出黎曼假设"]
    WI["🟣 安德鲁·怀尔斯 · Andrew Wiles&lt;br/&gt;英国 / United Kingdom&lt;br/&gt;证明费马大定理"]
  end

  subgraph E4["④ 超越无限：20世纪—现代"]
    direction LR
    PO["🟣 亨利·庞加莱 · Henri Poincaré&lt;br/&gt;法国 / France&lt;br/&gt;拓扑学；动力系统先声"]
    CAN["🟣 格奥尔格·康托尔 · Georg Cantor&lt;br/&gt;德国 / Germany&lt;br/&gt;集合论；比较不同大小的无穷"]
    HIL["🟣 大卫·希尔伯特 · David Hilbert&lt;br/&gt;德国 / Germany&lt;br/&gt;希尔伯特纲领；提出数学问题"]
    GOD["🟣 库尔特·哥德尔 · Kurt Gödel&lt;br/&gt;奥地利 / Austria&lt;br/&gt;不完备定理；连续统假设相对一致性"]
    COH["🟣 保罗·科恩 · Paul Cohen&lt;br/&gt;美国 / United States&lt;br/&gt;证明连续统假设独立于 ZFC"]
    JUL["🟣 加斯东·朱利亚 · Gaston Julia&lt;br/&gt;法国 / France&lt;br/&gt;复迭代与朱利亚集"]
    MAN["🟣 伯努瓦·芒德布罗 · Benoit Mandelbrot&lt;br/&gt;法国 / 美国 France / United States&lt;br/&gt;推广分形几何；芒德布罗集"]
  end

  A1 -.->|古代文明间的数学交流| P
  B1 -.->|较早出现的数值关系| P
  P -->|数与比例| PL
  PL -->|学院与几何传统| EU
  EU -->|公理化方法| AR
  EU -->|亚历山大学术| ER
  ER -.->|亚历山大学术传统；并非直接师承| HY
  EU --> GR2

  LIU -.->|中国数学传统| Q
  ARY -->|位值记数与天文| BRA
  BRA -->|印度数学知识交流| KH
  BHA -.->|代数问题的先声| KH
  KH -->|代数与数字传播| FI
  FI -->|代数在欧洲的发展| TA
  TA -->|三次方程解法| CA
  CA -->|四次方程解法| FE
  OK -.->|三次方程的几何解| CA
  Q -.->|同余思想的早期例子| GA
  MAD -.->|无穷级数的先声| NE

  PF -->|透视与几何| DE
  DE -->|坐标方法| NE
  DE -->|坐标方法| LE
  FM -->|极值与切线问题| NE
  NE <-->|微积分优先权争论| LE
  NE -->|微积分的发展| EU2
  LE -->|记号与分析方法| EU2
  EU2 -->|分析与数论| GA
  GA -.->|非欧几何的独立先声| BO
  GA -.->|非欧几何的独立先声| LO
  GA -->|微分几何| RI
  FM -.->|费马大定理问题| WI

  RI -->|黎曼假设| HIL
  CAN -->|连续统假设| HIL
  HIL -->|形式化基础问题| GOD
  GOD -->|连续统假设独立性研究| COH
  CAN -->|连续统假设| COH
  PO -.->|拓扑与动力系统的另一条发展线| CAN
  JUL -->|复迭代与分形研究| MAN

  classDef ancient fill:#f5e6d3,stroke:#8b5a2b,color:#000;
  classDef medieval fill:#fff3c4,stroke:#b8860b,color:#000;
  classDef modern fill:#dbeafe,stroke:#2563eb,color:#000;
  classDef contemporary fill:#ede9fe,stroke:#7c3aed,color:#000;
  classDef info fill:#fff,stroke:#999,color:#000,stroke-dasharray:4 4;
  class LG info;
  class A1,B1,P,PL,EU,AR,ER,HY,GR2 ancient;
  class Q,LIU,ARY,BRA,MAD,BHA,KH,OK,FI medieval;
  class TA,CA,FE,DE,FM,NE,LE,EU2,GA,BO,LO,RI,PF modern;
  class WI,PO,CAN,HIL,GOD,COH,MAN,JUL contemporary;
    </pre>
  </div>
  <figcaption>图很宽，可以在框内横向滚动；手机上也可以拖动查看。颜色表示大致时代，不是精确年代。</figcaption>
</figure>

<p id="math-graph-fallback" class="math-source-note" role="status" hidden>图谱脚本未能加载，可能是网络暂时无法访问国内 CDN。请稍后刷新；下面仍有四集的文字总结。</p>
<script src="https://registry.npmmirror.com/mermaid/11.4.1/files/dist/mermaid.min.js" onerror="document.getElementById('math-graph-fallback').hidden = false"></script>
<script>
  if (window.mermaid) {
    mermaid.initialize({
      startOnLoad: true,
      securityLevel: "strict",
      theme: "base",
      themeVariables: {
        fontFamily: "system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif",
        lineColor: "#7b6a58",
        clusterBkg: "#fffaf3",
        clusterBorder: "#d8c8b3"
      },
      flowchart: {
        htmlLabels: true,
        nodeSpacing: 28,
        rankSpacing: 42,
        curve: "basis"
      }
    });
  } else {
    document.getElementById("math-graph-fallback").hidden = false;
  }
</script>

## 按集回看

### ① 宇宙语言 · The Language of the Universe

数学从日常生活中的计数、土地测量和天文计算开始。巴比伦泥板展示了位值记数、六十进制和解方程的熟练应用；古埃及纸草书留下分数与几何问题。希腊数学家则将证明和逻辑推演发展为重要传统。

欧几里得把几何知识组织进《几何原本》，阿基米德用穷竭方法求面积和体积。亚历山大城的学术传统还连结着埃拉托色尼、希帕蒂娅，以及研究数论、圆锥曲线和天文学的学者。

### ② 东方奇才 · The Genius of the East

中国数学重视算法和实际问题：刘徽用割圆术计算圆周率，秦九韶研究一次同余方程。印度数学家发展位值记数、零与负数的运算法则；玛德哈瓦研究无穷级数和圆周率。

在巴格达等地，花剌子米推动代数学发展。波斯学者奥马尔·海亚姆用几何方法处理三次方程。后来斐波那契的《算盘书》帮助印度—阿拉伯数字在拉丁欧洲传播；意大利数学家又推进三次和四次方程的求解。

### ③ 空间的边界 · The Frontiers of Space

文艺复兴时期的透视法和几何研究，为描述空间提供新的想法。笛卡尔用坐标连接代数与几何，费马研究数论、极值和切线；牛顿与莱布尼茨分别发展微积分，也由此引发著名的优先权争论。

欧拉和高斯把分析、数论与几何推向新高度。鲍耶和罗巴切夫斯基独立发展非欧几何，黎曼则开创了影响深远的几何理论。几个世纪后，怀尔斯证明了费马大定理。

### ④ 超越无限 · To Infinity and Beyond

康托尔的集合论让数学家能够比较不同大小的无穷。希尔伯特希望通过严格的形式系统巩固数学基础；哥德尔的不完备定理揭示了形式系统的内在限制，后来科恩证明连续统假设独立于 ZFC 公理系统。

庞加莱发展拓扑与动力系统研究。朱利亚的复迭代研究启发了后来的分形探索，芒德布罗则推广了分形几何的应用与影响。图灵、计算和新的数学领域也让“数学能回答什么问题”成为现代数学的重要主题。

> **阅读图谱的小提醒：**数学是许多文明长期交流、独立探索和共同发展的成果。图中的国家名称是为了方便理解，古代人物所属的是当时的城邦、地区或学术世界，并不总与今天的国界相同；虚线表示相关或相似的思想，不一定是直接师承。

<p class="math-source-note">这是一份根据纪录片主题整理的学习笔记，不是逐集字幕或完整人物清单。人物贡献和连线做了简化，适合继续查资料、提问题、补充新节点。</p>
