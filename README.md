<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>写给未来的 Yulin Wang</title>
<style>
  :root { color-scheme: dark; }
  * { box-sizing: border-box; }
  body {
    margin: 0; min-height: 100vh; display: grid; place-items: center;
    padding: 28px; color: #f4f0e8;
    font-family: "Microsoft YaHei", "PingFang SC", system-ui, sans-serif;
    background: radial-gradient(ellipse at 50% 0%, #243a35 0%, #111b1b 42%, #0a1012 100%);
  }
  .card {
    width: min(760px, 100%); position: relative; overflow: hidden;
    padding: clamp(34px, 7vw, 72px); border: 1px solid rgba(215,190,133,.35);
    background: linear-gradient(145deg, rgba(255,255,255,.055), rgba(255,255,255,.015));
    box-shadow: 0 30px 100px rgba(0,0,0,.35); border-radius: 22px;
  }
  .card::before {
    content: ""; position: absolute; width: 260px; height: 260px; right: -110px; top: -110px;
    border: 1px solid rgba(215,190,133,.18); border-radius: 50%;
    box-shadow: 0 0 0 24px rgba(215,190,133,.025), 0 0 0 48px rgba(215,190,133,.02);
  }
  .eyebrow { color: #c9b27b; letter-spacing: .24em; font-size: 12px; text-transform: uppercase; }
  h1 { font-size: clamp(30px, 6vw, 52px); font-weight: 500; letter-spacing: .04em; line-height: 1.25; margin: 24px 0 12px; }
  h1 span { color: #d8c18a; }
  .sub { color: #aab5b0; font-size: 15px; letter-spacing: .08em; }
  .rule { width: 54px; height: 2px; margin: 34px 0; background: #c9b27b; }
  .wish { font-size: clamp(17px, 2.4vw, 20px); line-height: 2.15; color: #e7e5dc; }
  .wish p { margin: 0 0 12px; }
  .wish strong { color: #dfc98f; font-weight: 500; }
  .closing { margin-top: 34px; padding-top: 24px; border-top: 1px solid rgba(255,255,255,.12); }
  .closing .big { font-size: clamp(22px, 4vw, 30px); letter-spacing: .12em; color: #e2cc91; }
  .closing .small { margin-top: 12px; font-size: 13px; color: #899994; letter-spacing: .08em; }
  footer { margin-top: 30px; color: #667570; font-size: 11px; letter-spacing: .2em; }
  @media (prefers-reduced-motion: no-preference) {
    .card { animation: rise .8s ease-out both; }
    @keyframes rise { from { opacity: 0; transform: translateY(12px); } to { opacity: 1; transform: translateY(0); } }
  }
</style>
</head>
<body>
  <main class="card">
    <div class="eyebrow">A NOTE TO THE FUTURE</div>
    <h1>写给未来的<br><span>Yulin Wang</span></h1>
    <div class="sub">愿你走得坚定，也走得长远。</div>
    <div class="rule"></div>
    <section class="wish">
      <p>愿你在未来的日子里，<strong>稳住心态</strong>。</p>
      <p>不因一时得失而慌张，不被外界的声音带乱节奏。</p>
      <p>把大目标拆成小步骤，<strong>步步为营，持续向前</strong>。</p>
      <p>认真做好每一件值得做的事，让能力增长，让财富积累，让选择越来越多。</p>
      <p>不急着证明自己，只专注于把路走对、把事情做成。</p>
      <p>愿你一路稳扎稳打，积累实力与底气，最终<strong>顺利上岸</strong>，迎来真正属于自己的好日子。</p>
    </section>
    <div class="closing">
      <div class="big">愿你顺利上岸。</div>
      <div class="small">稳住心态 · 步步为营 · 积累财富 · 终见彼岸</div>
    </div>
    <footer>KEEP YOUR PACE · BUILD YOUR FUTURE</footer>
  </main>
</body>
</html>
