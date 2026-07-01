# lijianhao190.github.io
<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>李健豪 | 个人简历</title>
<style>
  :root {
    --bg: #fafafa;
    --card: #ffffff;
    --text: #1a1a1a;
    --muted: #6b6b6b;
    --accent: #2b6cb0;
    --border: #e5e5e5;
  }
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body {
    font-family: -apple-system, "PingFang SC", "Microsoft YaHei", Segoe UI, sans-serif;
    background: var(--bg);
    color: var(--text);
    line-height: 1.6;
  }
  .container {
    max-width: 760px;
    margin: 0 auto;
    padding: 60px 24px 100px;
  }
  header {
    display: flex;
    align-items: center;
    gap: 24px;
    margin-bottom: 48px;
  }
  .avatar {
    width: 96px;
    height: 96px;
    border-radius: 50%;
    background: var(--border);
    display: flex;
    align-items: center;
    justify-content: center;
    color: var(--muted);
    font-size: 13px;
    flex-shrink: 0;
    border: 1px solid #ddd;
  }
  h1 {
    font-size: 28px;
    font-weight: 600;
    margin-bottom: 6px;
  }
  .title {
    color: var(--accent);
    font-size: 16px;
    font-weight: 500;
  }
  section {
    margin-bottom: 40px;
  }
  h2 {
    font-size: 14px;
    text-transform: uppercase;
    letter-spacing: 1px;
    color: var(--muted);
    margin-bottom: 16px;
    border-bottom: 1px solid var(--border);
    padding-bottom: 8px;
  }
  .about {
    font-size: 15px;
    color: #333;
  }
  .item {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 8px;
    padding: 18px 20px;
    margin-bottom: 12px;
  }
  .item-title {
    font-weight: 600;
    font-size: 15px;
  }
  .item-sub {
    color: var(--muted);
    font-size: 13px;
    margin-top: 2px;
  }
  .placeholder {
    border: 1px dashed var(--border);
    border-radius: 8px;
    padding: 28px 20px;
    text-align: center;
    color: var(--muted);
    font-size: 14px;
  }
  .contact-list {
    display: flex;
    flex-direction: column;
    gap: 8px;
    font-size: 14px;
  }
  .contact-list a {
    color: var(--accent);
    text-decoration: none;
  }
  footer {
    text-align: center;
    color: #aaa;
    font-size: 12px;
    margin-top: 60px;
  }
</style>
</head>
<body>
  <div class="container">
    <header>
      <div class="avatar">照片<br>占位</div>
      <div>
        <h1>李健豪</h1>
        <div class="title">高中物理教师</div>
      </div>
    </header>

    <section>
      <h2>关于我</h2>
      <p class="about">
        毕业于中央民族大学,现任高中物理教师,拥有2年一对一教学经验,工作地点为北京市。
        擅长将复杂的物理概念用清晰易懂的方式讲解给学生,注重因材施教,帮助学生建立扎实的知识基础与学习信心。
      </p>
    </section>

    <section>
      <h2>教育背景</h2>
      <div class="item">
        <div class="item-title">中央民族大学</div>
        <div class="item-sub">物理学专业 · 北京市</div>
      </div>
    </section>

    <section>
      <h2>工作经历</h2>
      <div class="item">
        <div class="item-title">高中物理教师 · 一对一教学</div>
        <div class="item-sub">北京市 · 2年教学经验</div>
      </div>
    </section>

    <section>
      <h2>作品 / 案例展示</h2>
      <div class="placeholder">此处用于展示教学案例、课件或学生成果<br>(占位区域,可后续添加内容)</div>
    </section>

    <section>
      <h2>联系方式</h2>
      <div class="contact-list">
        <div>📧 Email: <a href="mailto:lijianhao190@outlook.com">lijianhao190@outlook.com</a></div>
        <div>💬 WeChat: kdtd13245</div>
      </div>
    </section>

    <footer>© 2026 李健豪</footer>
  </div>
</body>
</html>