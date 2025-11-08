<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<title>影视接口说明 | Media API Info</title>
<style>
  body { font-family: "Microsoft YaHei", sans-serif; line-height: 1.7; padding: 20px; }
  .lang-btn { margin-right: 10px; cursor: pointer; padding: 5px 10px; border: 1px solid #ccc; border-radius: 6px; }
  .active { background: #0078d7; color: white; }
</style>
<script>
function switchLang(lang) {
  document.getElementById('zh').style.display = lang === 'zh' ? 'block' : 'none';
  document.getElementById('en').style.display = lang === 'en' ? 'block' : 'none';
  document.getElementById('btn-zh').classList.toggle('active', lang === 'zh');
  document.getElementById('btn-en').classList.toggle('active', lang === 'en');
}
</script>
</head>
<body onload="switchLang('zh')">

<div>
  <span id="btn-zh" class="lang-btn" onclick="switchLang('zh')">中文</span>
  <span id="btn-en" class="lang-btn" onclick="switchLang('en')">English</span>
</div>
<hr>

<!-- 中文内容 -->
<div id="zh">
  <h2>🌈 多元影视接口说明</h2>
  <p>本接口提供高效、稳定的影视聚合访问，适用于多元文化与性别友好社区。</p>
  <ol>
    <li>访问 <a href="https://ptus815.dpdns.org/">https://ptus815.dpdns.org/</a> 下载 Fongmi 或 OK影视盒子。</li>
    <li>点击“复制接口”获取链接。</li>
    <li>在软件设置 → 点播栏中粘贴接口即可使用。</li>
  </ol>
  <h3>☕ 请我喝杯咖啡</h3>
  <p>如果您喜欢本项目，欢迎请我喝咖啡支持！</p>
  <table>
    <tr>
      <td><img src="https://d.kstore.dev/download/14943/zfb.jpg" width="150"></td>
      <td><img src="https://d.kstore.dev/download/14943/wxzc.jpg" width="150"></td>
    </tr>
  </table>
  <h3>致谢</h3>
  <p>感谢 <a href="https://github.com/FongMi/TV">FongMi/TV</a> 及所有开源贡献者的努力。</p>
</div>

<!-- English content -->
<div id="en" style="display:none">
  <h2>🌈 Inclusive Media API Overview</h2>
  <p>This API provides efficient and stable media aggregation, supporting diverse and gender-inclusive communities.</p>
  <ol>
    <li>Visit <a href="https://ptus815.dpdns.org/">https://ptus815.dpdns.org/</a> to download Fongmi or OK Movie Box.</li>
    <li>Click “Copy API” to get your interface link.</li>
    <li>In the app, go to Settings → On-demand and paste the link.</li>
  </ol>
  <h3>☕ Support My Work</h3>
  <p>If you find this project helpful, consider buying me a coffee!</p>
  <h3>Thanks</h3>
  <p>Thanks to <a href="https://github.com/FongMi/TV">FongMi/TV</a> and all open-source contributors.</p>
</div>

</body>
</html>