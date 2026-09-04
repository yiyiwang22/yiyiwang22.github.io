---
weight: 10
menu: "main"
hide_meta: true
---

<style>
  /* 核心样式表：采用深海蓝调，提升专业感并保护视力 */
  .profile-wrapper {
    /* font-family: Georgia, 'Times New Roman', serif;
    line-height: 1.6;
    color: #333;
    font-size: 0.9rem;
    font-variant-numeric: lining-nums;
  -webkit-font-feature-settings: "lnum";
  font-feature-settings: "lnum"; */
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  line-height: 1.6;
  color: #333;
  font-size: 1rem;
  }
  /* 降低 strong 标签的加粗程度，使其更加精致 */
  .profile-wrapper strong {
    color: #4a5568; /* 改用深灰蓝色/深灰色，视觉上比纯黑柔和很多 */
  font-weight: bold;
  }
  /* 标题样式：使用深海蓝色 (#2a4d69) 替换橙色 */
  .profile-wrapper h1, 
  .profile-wrapper h3 {
    color: #c99dfa; 
    font-style: italic;
    margin-top: 0.8em;
    margin-bottom: 0.5em;
  }
  .profile-wrapper h4{
    color: #c99dfa; 
    font-style: italic;
    margin-top: 0.1em;
    margin-bottom: 0.1em;
  }
    .profile-wrapper h6{
    color: #c99dfa; 
    font-style: italic;
    margin-top: 0.1em;
    margin-bottom: 0.1em;
  }
  /* 超链接样式：深蓝色调，加粗以示区分 */
  .profile-wrapper a {
    color: #8c9fe2;
    text-decoration: underline;
    font-weight: bold;
    font-size: 1rem; 
    border-bottom: 1px solid transparent;
    transition: all 0.3s ease;
  }
  .profile-wrapper a:hover {
    color: #2a4d69;
    border-bottom: 1px solid #2a4d69;
  }
  .profile-wrapper .small-links a {
  font-size: 0.6rem; /* 数值越小字号越小，可以根据需要调整成 0.8rem 或 13px */
}
  /* 段落间距 */
  .profile-wrapper p {
    margin-bottom: 0.5em;
    margin-top: 0.5em;
  }

  /* 列表样式优化 */
  .profile-wrapper ul {
    margin-left: 20px;
    margin-bottom: 1.0em;
  }
  .profile-wrapper li {
    margin-bottom: 0.6em;
  }
  
  /* 头像样式 */
  .avatar-img {
    max-width: 150px;
    border-radius: 8px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    margin-bottom: 20px;
    display: block;
  }

  /* 底部硬核徽章 */
  .geek-badge {
    font-size: 0.85rem;
    color: #7f8c8d;
    font-style: italic;
    text-align: center;
    margin-top: 40px;
    border-top: 1px solid #ecf0f1;
    padding-top: 15px;
  }
</style>

<div class="profile-wrapper">

  <h4>About me</h4>

  <img src="https://yiyiwang22.github.io/me.jpeg" alt="Yiyi Wang Avatar" class="avatar-img"> 

  <p>Hi everyone, I'm <strong>Yiyi Wang</strong>, a Ph.D. student in Computer Science and Engineering at the University of South Florida. Currently, I am working under the supervision of Prof. <a href="http://shareefahmed.myweb.usf.edu/">Shareef Ahmed</a>.</p>

  <p>My research is deeply rooted in <strong>Real-Time Systems (RTS)</strong>. I focus on exploring and developing predictable scheduling frameworks to optimize underlying system performance and resource allocation.</p>

 <p>My journey into systems research started at Wuhan University, where building a 5-stage pipelined CPU from scratch sparked my deep interest in computer architecture. Prior to USF, I earned my Master's degree in Language Technology (with Distinction) from the University of Gothenburg, and my Bachelor's degree (Top 10%) from Wuhan University.
  <h6>Publication</h6>
    <p>S. Ahmed, S. Liu, <strong>Y. Wang</strong>, R. Wagle, J. Anderson, "Schedulability Analysis for Pub-Sub Graphs Under Global EDF Scheduling", 47th IEEE Real-Time Systems Symposium. <span style="color: #e74c3c;">(Acceptance Rate 14.3%)</span></p>
    
  <!-- <h6>Links</h6><a href="https://github.com/yiyiwang22">My GitHub</a>
    <a href="https://www.linkedin.com/in/yiyi-wang-0551b7179/">My LinkedIn</a> 
 -->
<p class="small-links">
  <a href="https://github.com/yiyiwang22">My GitHub</a> | 
  <a href="https://www.linkedin.com/in/yiyi-wang-0551b7179/">My LinkedIn</a>
</p>
<!-- 
  <h6>Interests</h6>
  <p>I enjoy popping dance and writing rap songs. </p> -->

  <br>

  <!-- <div align="center" style="width: 100%; max-width: 600px; margin: 0 auto;">
    <script type="text/javascript" id="mapmyvisitors" src="//mapmyvisitors.com/map.js?d=-GaSbw50DLBdzn-j28l6bWkfIuvhsMmIZ8RSzzEb-6g&cl=ffffff&w=a"></script>
      </div> -->
  <!-- 隐形访客统计 -->
<script>
  (function() {
    var trackerUrl = "https://rough-dust-8d76.yw22.workers.dev";
    
    fetch(trackerUrl, { method: "POST" }).catch(function() {
    });
  })();
</script>

</div>