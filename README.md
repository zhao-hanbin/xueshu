[index.html](https://github.com/user-attachments/files/28958176/index.html)
<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>赵韩斌 · 学术论文合集</title>
<meta name="description" content="形状记忆合金 · 物理计算 · 物理智能 · 柔固转换 · 热量再分配">
<style>
  :root {
    --bg: #0f0f14;
    --card: #1a1a24;
    --border: #2a2a3a;
    --accent: #6c8cff;
    --accent2: #ff6b6b;
    --text: #e0e0e8;
    --text2: #8888a0;
    --tag-bg: rgba(108,140,255,0.12);
    --tag-text: #8cacff;
  }
  * { margin:0; padding:0; box-sizing:border-box; }
  body {
    font-family: -apple-system, "Segoe UI", "Noto Sans SC", system-ui, sans-serif;
    background: var(--bg);
    color: var(--text);
    line-height: 1.7;
    min-height: 100vh;
  }
  .container { max-width: 900px; margin: 0 auto; padding: 40px 20px; }
  header { text-align: center; padding: 60px 0 40px; }
  header h1 { font-size: 2em; font-weight: 700; letter-spacing: 2px; }
  header h1 span { color: var(--accent); }
  header p { color: var(--text2); margin-top: 8px; font-size: 0.95em; }
  header .orcid { display: inline-block; margin-top: 12px; color: var(--text2); font-size: 0.85em; text-decoration: none; }
  header .orcid:hover { color: var(--accent); }
  .stats { display: flex; justify-content: center; gap: 30px; margin: 30px 0; color: var(--text2); font-size: 0.9em; }
  .stats span { background: var(--card); padding: 6px 16px; border-radius: 20px; border: 1px solid var(--border); }
  .section { margin: 40px 0; }
  .section h2 {
    font-size: 1.3em;
    font-weight: 600;
    margin-bottom: 20px;
    padding-left: 14px;
    border-left: 3px solid var(--accent);
  }
  .section h2 .count { color: var(--text2); font-weight: 400; font-size: 0.8em; margin-left: 8px; }
  .card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 20px 24px;
    margin-bottom: 12px;
    transition: border-color 0.2s;
  }
  .card:hover { border-color: var(--accent); }
  .card .title { font-size: 1em; font-weight: 500; margin-bottom: 6px; }
  .card .title a { color: var(--accent); text-decoration: none; }
  .card .title a:hover { text-decoration: underline; }
  .card .meta { color: var(--text2); font-size: 0.82em; display: flex; flex-wrap: wrap; gap: 8px; align-items: center; }
  .card .meta .tag {
    display: inline-block;
    background: var(--tag-bg);
    color: var(--tag-text);
    padding: 1px 10px;
    border-radius: 10px;
    font-size: 0.78em;
  }
  .card .meta .doi { color: var(--text2); font-family: monospace; font-size: 0.9em; }
  .card .meta .doi:hover { color: var(--accent); }
  .card .desc { color: var(--text2); font-size: 0.85em; margin-top: 6px; line-height: 1.5; }
  .paradigm-tag { display: inline-block; background: rgba(255,107,107,0.1); color: var(--accent2); padding: 1px 10px; border-radius: 10px; font-size: 0.78em; margin-right: 4px; }
  footer { text-align: center; padding: 40px 0; color: var(--text2); font-size: 0.82em; border-top: 1px solid var(--border); margin-top: 40px; }
  footer a { color: var(--accent); text-decoration: none; }
  @media (max-width: 600px) {
    header h1 { font-size: 1.5em; }
    .card { padding: 16px; }
    .stats { gap: 12px; flex-wrap: wrap; }
  }
</style>
</head>
<body>
<div class="container">

<header>
  <h1><span>赵韩斌</span> · 学术论文合集</h1>
  <p>形状记忆合金 | 物理计算 | 物理智能 | 柔固转换 | 热量再分配</p>
  <a class="orcid" href="https://orcid.org/0009-0007-6464-076X" target="_blank">ORCID: 0009-0007-6464-076X</a>
  <div class="stats">
    <span>📄 论文 30+ 篇</span>
    <span>🏛️ Zenodo / EngrXiv</span>
    <span>🔬 独立研究者</span>
  </div>
</header>

<!-- ===== 旗舰论文 ===== -->
<div class="section">
  <h2>旗舰理论 <span class="count">· 物理计算三部曲</span></h2>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.5281/zenodo.20642739" target="_blank">Physical Computing: A Non-Von-Neumann Computing Paradigm Based on Shape Memory Alloy Phase Transformation</a></div>
    <div class="meta">
      <span class="tag">物理计算</span>
      <span class="tag">英文版</span>
      <a class="doi" href="https://doi.org/10.5281/zenodo.20642739" target="_blank">doi:10.5281/zenodo.20642739</a>
    </div>
    <div class="desc">核心理论：物理计算元件不是模仿电子学，而是在各自物理域中重新发现通用抽象功能。</div>
  </div>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.5281/zenodo.20642471" target="_blank">物理计算：材料相变、物理智能与非冯·诺依曼架构的理论与设计</a></div>
    <div class="meta">
      <span class="tag">物理计算</span>
      <span class="tag">中文版</span>
      <a class="doi" href="https://doi.org/10.5281/zenodo.20642471" target="_blank">doi:10.5281/zenodo.20642471</a>
    </div>
    <div class="desc">中文完整版，七条公理体系："物理本身就是程序"。</div>
  </div>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.31224/7287" target="_blank">Physical Intelligence (EngrXiv)</a></div>
    <div class="meta">
      <span class="tag">物理智能</span>
      <span class="tag">工程档案</span>
      <a class="doi" href="https://doi.org/10.31224/7287" target="_blank">doi:10.31224/7287</a>
    </div>
    <div class="desc">工程档案预印版——物理智能设计哲学的系统阐述。</div>
  </div>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.5281/zenodo.20571554" target="_blank">物理智能范式</a></div>
    <div class="meta">
      <span class="tag">物理智能</span>
      <span class="tag">v1.0</span>
      <a class="doi" href="https://doi.org/10.5281/zenodo.20571554" target="_blank">doi:10.5281/zenodo.20571554</a>
    </div>
  </div>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.5281/zenodo.20610681" target="_blank">物理智能范式 v2.0</a></div>
    <div class="meta">
      <span class="tag">物理智能</span>
      <span class="tag">v2.0</span>
      <a class="doi" href="https://doi.org/10.5281/zenodo.20610681" target="_blank">doi:10.5281/zenodo.20610681</a>
    </div>
  </div>
</div>

<!-- ===== 柔固转换 ===== -->
<div class="section">
  <h2>柔固转换范式 <span class="count">· 力学范式</span></h2>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.5281/zenodo.20487693" target="_blank">Stiffness-Switching v1.0</a></div>
    <div class="meta">
      <span class="paradigm-tag">力学范式</span>
      <span class="tag">v1.0</span>
      <a class="doi" href="https://doi.org/10.5281/zenodo.20487693" target="_blank">doi:10.5281/zenodo.20487693</a>
    </div>
  </div>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.5281/zenodo.20610714" target="_blank">Flexi-Rigid Transition v2.0</a></div>
    <div class="meta">
      <span class="paradigm-tag">力学范式</span>
      <span class="tag">v2.0</span>
      <a class="doi" href="https://doi.org/10.5281/zenodo.20610714" target="_blank">doi:10.5281/zenodo.20610714</a>
    </div>
  </div>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.5281/zenodo.20666920" target="_blank">Flexi-Rigid Transition v3.0</a></div>
    <div class="meta">
      <span class="paradigm-tag">力学范式</span>
      <span class="tag">v3.0</span>
      <a class="doi" href="https://doi.org/10.5281/zenodo.20666920" target="_blank">doi:10.5281/zenodo.20666920</a>
    </div>
    <div class="desc">完整版：10条原创设计原则 + 4个跨领域案例 + 航空航天拓展。</div>
  </div>
</div>

<!-- ===== 力学涟漪 ===== -->
<div class="section">
  <h2>力学涟漪 <span class="count">· 应用设计</span></h2>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.5281/zenodo.20488766" target="_blank">涟漪二：缝合但不收紧</a></div>
    <div class="meta">
      <span class="paradigm-tag">力学涟漪</span>
      <a class="doi" href="https://doi.org/10.5281/zenodo.20488766" target="_blank">doi:10.5281/zenodo.20488766</a>
    </div>
  </div>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.5281/zenodo.20541972" target="_blank">涟漪三：八字固定·点状驱动</a></div>
    <div class="meta">
      <span class="paradigm-tag">力学涟漪</span>
      <a class="doi" href="https://doi.org/10.5281/zenodo.20541972" target="_blank">doi:10.5281/zenodo.20541972</a>
    </div>
  </div>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.31224/7263" target="_blank">涟漪三：八字悬吊和点激励周边吸能 (EngrXiv)</a></div>
    <div class="meta">
      <span class="paradigm-tag">力学涟漪</span>
      <span class="tag">工程档案</span>
      <a class="doi" href="https://doi.org/10.31224/7263" target="_blank">doi:10.31224/7263</a>
    </div>
  </div>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.5281/zenodo.20629093" target="_blank">涟漪四：变截面力控</a></div>
    <div class="meta">
      <span class="paradigm-tag">力学涟漪</span>
      <a class="doi" href="https://doi.org/10.5281/zenodo.20629093" target="_blank">doi:10.5281/zenodo.20629093</a>
    </div>
  </div>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.5281/zenodo.20668414" target="_blank">涟漪五：SMA在骨科外固定中的深度应用</a></div>
    <div class="meta">
      <span class="paradigm-tag">力学涟漪</span>
      <a class="doi" href="https://doi.org/10.5281/zenodo.20668414" target="_blank">doi:10.5281/zenodo.20668414</a>
    </div>
  </div>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.5281/zenodo.20680979" target="_blank">涟漪六：航空航天工程篇</a></div>
    <div class="meta">
      <span class="paradigm-tag">力学涟漪</span>
      <a class="doi" href="https://doi.org/10.5281/zenodo.20680979" target="_blank">doi:10.5281/zenodo.20680979</a>
    </div>
  </div>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.5281/zenodo.20689740" target="_blank">涟漪七：腔内支撑</a></div>
    <div class="meta">
      <span class="paradigm-tag">力学涟漪</span>
      <a class="doi" href="https://doi.org/10.5281/zenodo.20689740" target="_blank">doi:10.5281/zenodo.20689740</a>
    </div>
  </div>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.5281/zenodo.20690532" target="_blank">涟漪八：减张缝合</a></div>
    <div class="meta">
      <span class="paradigm-tag">力学涟漪</span>
      <a class="doi" href="https://doi.org/10.5281/zenodo.20690532" target="_blank">doi:10.5281/zenodo.20690532</a>
    </div>
  </div>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.5281/zenodo.20690845" target="_blank">涟漪九：标准力控元件</a></div>
    <div class="meta">
      <span class="paradigm-tag">力学涟漪</span>
      <a class="doi" href="https://doi.org/10.5281/zenodo.20690845" target="_blank">doi:10.5281/zenodo.20690845</a>
    </div>
  </div>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.5281/zenodo.20698571" target="_blank">涟漪十二：非生命智能体</a></div>
    <div class="meta">
      <span class="paradigm-tag">力学涟漪</span>
      <a class="doi" href="https://doi.org/10.5281/zenodo.20698571" target="_blank">doi:10.5281/zenodo.20698571</a>
    </div>
  </div>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.5281/zenodo.20699451" target="_blank">涟漪十三：软限位</a></div>
    <div class="meta">
      <span class="paradigm-tag">力学涟漪</span>
      <a class="doi" href="https://doi.org/10.5281/zenodo.20699451" target="_blank">doi:10.5281/zenodo.20699451</a>
    </div>
  </div>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.5281/zenodo.20703090" target="_blank">涟漪十五：可降解SMA骨科植入物</a></div>
    <div class="meta">
      <span class="paradigm-tag">力学涟漪</span>
      <a class="doi" href="https://doi.org/10.5281/zenodo.20703090" target="_blank">doi:10.5281/zenodo.20703090</a>
    </div>
  </div>
</div>

<!-- ===== 热力学 ===== -->
<div class="section">
  <h2>热量再分配 <span class="count">· 热力学范式</span></h2>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.5281/zenodo.20571412" target="_blank">热力学范式 v1.0</a></div>
    <div class="meta">
      <span class="paradigm-tag">热力学</span>
      <span class="tag">v1.0</span>
      <a class="doi" href="https://doi.org/10.5281/zenodo.20571412" target="_blank">doi:10.5281/zenodo.20571412</a>
    </div>
  </div>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.5281/zenodo.20610597" target="_blank">热力学范式 v2.0</a></div>
    <div class="meta">
      <span class="paradigm-tag">热力学</span>
      <span class="tag">v2.0</span>
      <a class="doi" href="https://doi.org/10.5281/zenodo.20610597" target="_blank">doi:10.5281/zenodo.20610597</a>
    </div>
  </div>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.5281/zenodo.20579930" target="_blank">水之心 v1.0</a></div>
    <div class="meta">
      <span class="paradigm-tag">热力学</span>
      <span class="tag">仿生</span>
      <a class="doi" href="https://doi.org/10.5281/zenodo.20579930" target="_blank">doi:10.5281/zenodo.20579930</a>
    </div>
    <div class="desc">基于SMA物理智能的仿生搏动热泵系统。</div>
  </div>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.5281/zenodo.20610655" target="_blank">水之心 v2.0</a></div>
    <div class="meta">
      <span class="paradigm-tag">热力学</span>
      <span class="tag">v2.0</span>
      <a class="doi" href="https://doi.org/10.5281/zenodo.20610655" target="_blank">doi:10.5281/zenodo.20610655</a>
    </div>
  </div>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.31224/7286" target="_blank">水之心 (EngrXiv)</a></div>
    <div class="meta">
      <span class="paradigm-tag">热力学</span>
      <span class="tag">工程档案</span>
      <a class="doi" href="https://doi.org/10.31224/7286" target="_blank">doi:10.31224/7286</a>
    </div>
  </div>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.5281/zenodo.20580228" target="_blank">热峰钳制</a></div>
    <div class="meta">
      <span class="paradigm-tag">热力学</span>
      <a class="doi" href="https://doi.org/10.5281/zenodo.20580228" target="_blank">doi:10.5281/zenodo.20580228</a>
    </div>
  </div>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.5281/zenodo.20689331" target="_blank">热力涟漪十：向日葵系统</a></div>
    <div class="meta">
      <span class="paradigm-tag">热力学</span>
      <a class="doi" href="https://doi.org/10.5281/zenodo.20689331" target="_blank">doi:10.5281/zenodo.20689331</a>
    </div>
  </div>
</div>

<!-- ===== 方法论 ===== -->
<div class="section">
  <h2>方法论与综合</h2>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.5281/zenodo.20581184" target="_blank">以身为器方法论 v1.0</a></div>
    <div class="meta">
      <span class="tag">方法论</span>
      <a class="doi" href="https://doi.org/10.5281/zenodo.20581184" target="_blank">doi:10.5281/zenodo.20581184</a>
    </div>
  </div>

  <div class="card">
    <div class="title"><a href="https://doi.org/10.5281/zenodo.20702280" target="_blank">以身为器 v2.0</a></div>
    <div class="meta">
      <span class="tag">方法论</span>
      <span class="tag">v2.0</span>
      <a class="doi" href="https://doi.org/10.5281/zenodo.20702280" target="_blank">doi:10.5281/zenodo.20702280</a>
    </div>
  </div>
</div>

<footer>
  <p>赵韩斌 · 独立研究者 · 浙江 · 中国</p>
  <p>📧 <a href="mailto:zhaohanbin@outlook.com">zhaohanbin@outlook.com</a></p>
  <p>ORCID: <a href="https://orcid.org/0009-0007-6464-076X" target="_blank">0009-0007-6464-076X</a></p>
  <p style="margin-top:12px; font-size:0.78em;">本文集自动生成 · 论文全部以开放获取发布于 Zenodo / EngrXiv</p>
</footer>

</div>
</body>
</html>
