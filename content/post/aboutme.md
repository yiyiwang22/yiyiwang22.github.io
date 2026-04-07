---
weight: 10
menu: "main"
hide_meta: true
---

<style>
  /* 核心样式表：采用深海蓝调，提升专业感并保护视力 */
  .profile-wrapper {
    font-family: Georgia, 'Times New Roman', serif;
    line-height: 1.6;
    color: #333;
    font-size: 1rem;
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
    border-bottom: 1px solid transparent;
    transition: all 0.3s ease;
  }
  .profile-wrapper a:hover {
    color: #2a4d69;
    border-bottom: 1px solid #2a4d69;
  }
  
  /* 段落间距 */
  .profile-wrapper p {
    margin-bottom: 0.5em;
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

  <h1>About me</h1>

  <img src="https://yiyiwang22.github.io/me.jpeg" alt="Yiyi Wang Avatar" class="avatar-img"> 

  <p>Hi everyone, I'm <strong>Yiyi Wang</strong>, a Ph.D. student in Computer Science and Engineering at the University of South Florida. Currently, I am conducting research under the supervision of Prof. <a href="http://shareefahmed.myweb.usf.edu/">Shareef Ahmed</a>.</p>

  <p>My research is deeply rooted in <strong>Real-Time Systems (RTS)</strong> and <strong>Operating Systems</strong>. I focus on exploring and developing predictable scheduling frameworks to optimize underlying system performance and resource allocation.</p>

 <p>My passion for systems was ignited during my undergraduate years at Wuhan University, where I <strong>built a 5-stage pipelined CPU</strong>. Academically, I maintained a record of excellence, <strong>ranking in the top 10%</strong> of my major with an overall <strong>GPA of 3.73/4.0</strong>.</p> To broaden my technical horizon, I spent two years exploring Language Technology at the University of Gothenburg, where I graduated with my master's thesis passing with <strong>Distinction</strong>.</p>

 
 <p>Now, I have returned to my core interest: operating systems and high-performance computing. Previously, I also explored <strong>MPI</strong> communication optimizations for <strong>GPU-accelerated</strong> molecular dynamics (Gromacs). You can find some of my former research documents [<a href="https://github.com/yiyiwang22/MPI_GPU_Gromacs">here</a>].</p>

  <h3>Core Projects</h3>
  <h4>Undergraduate Project (Independent, 2017)</h4>
  <ul>
    <li><strong><a href="https://raw.githubusercontent.com/yiyiwang22/yiyiwang22.github.io/3276570222ff8c48ea502f54f8d34d24e251bd26/static/cpuVHDL.pdf">Multi-cycle pipelined CPU hardware simulation</a></strong>
      <ul>
        <li>Architected a cycle-accurate five-level pipelined CPU using <strong>Verilog HDL</strong> and Mars-MIPS.</li>
        <li>Implemented complex hardware logic to handle architectural hazards, including data hazards and control hazards.</li>
        <li>Simulated core MIPS instruction sets to verify hardware-level instruction execution and pipeline efficiency.</li>
      </ul>
    </li>
  </ul>

  <h4>Work Project (Independent, 2022)</h4>
  <p><em>Software Engineer</em></p>
  <ul>
    <li><strong><a href="https://github.com/yiyiwang22/LintCustomisation/tree/main">LintCustomisation Generator using Java</a></strong>
      <ul>
        <li>Independently developed a custom Lint detection tool to enforce architectural standards for large-scale Japanese banking software.</li>
        <li>Engineered specific detection rules for <strong>Java</strong> source code analysis, achieving automated scanning of class/function naming conventions and illegal API calls.</li>
<li>Automated team workflows by developing <strong>Java</strong>-based tools to enable automated code modifications and efficient batch Lint rule generation.</li>
      </ul>
    </li>
  </ul> 

  <h3>Explorations in Language Tech</h3>

  <h4>Master Thesis (Independent, 2025)</h4>
  <p><em>Student Intern in <a href="https://sinch.com">Sinch</a></em></p>
  <ul>
    <li><strong>Prompt strategy on the code generation by LLMs</strong> <em>(Pass with Distinction)</em> 
      <ul>
        <li>Evaluated the performance of Gemini-Flash and DeepSeek-R1 models using the MBPP benchmark, achieving a pass@3 score of 79.4% with DeepSeek-R1.</li>
        <li>Demonstrated that DeepSeek-R1’s accuracy (86.8%) is competitive with ChatGPT Plus (87.5%) in specialized code generation tasks.</li>
        <li>Optimized grammatical correctness of generated code by implementing advanced prompting strategies, including Chain-of-Thought (CoT), persona engineering, and few-shot learning.</li>
      </ul>
    </li>
  </ul> 

  <h4>Master Project (Independent, 2024)</h4>
  <ul>
    <li><strong><a href="https://github.com/yiyiwang22/final-project-dialogue-system2/blob/main/README.md">Travel recommendation implemented with NLG and NLU based on Microsoft Azure</a></strong>
      <ul>
        <li>Developed a robust voice-interaction application integrating Azure Speech Studio for real-time ASR (Speech Recognition) and TTS (Text-to-Speech).</li>
        <li>Implemented complex conversation state management using the XState library, achieving high robustness and visualized state transitions.</li>
        <li>Enabled dynamic audio configuration for voice tone, speaking speed, and intonation to enhance user experience.</li>
      </ul>
    </li>
  </ul>

  <h6>Links</h6>
  <ul>
    <li><a href="https://github.com/yiyiwang22">My GitHub</a></li>
    <li><a href="https://www.linkedin.com/in/yiyi-wang-0551b7179/">My LinkedIn</a></li> 
  </ul>

  <h6>Interests</h6>
  <p>I enjoy popping dance and writing rap songs. </p>

  <br>

  <div align="center" style="width: 100%; max-width: 600px; margin: 0 auto;">
    <script type="text/javascript" id="clustrmaps" src="https://www.clustrmaps.com/map_v2.js?d=lpdu7lj6oKwOF761F_SjmogNM_pPDnmD1qu6UgfcAEs&cl=ffffff&w=a&t=m&co=2d78ad&ct=ffffff"></script>
  </div>
  

</div>