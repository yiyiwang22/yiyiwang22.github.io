---
weight: 10
menu: "main"
hide_meta: true
---

<style>
/* =========================================================
   Academic Homepage — Dynamic Theme Adaptation
   ========================================================= */

.profile-wrapper {
  max-width: 1000px;
  margin: 0 auto;
  padding: 18px 22px 36px;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif !important;
  font-size: 17px !important;
  line-height: 1.65 !important;
  color: inherit !important; /* 彻底继承主题自带颜色 */
}

/* 基础文本 */
.profile-wrapper p {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif !important;
  font-size: 17px !important;
  line-height: 1.65 !important;
  color: inherit !important;
  margin-top: 0 !important;
  margin-bottom: 10px !important;
}

.profile-wrapper strong {
  color: inherit !important;
  font-weight: 700 !important;
}

/* Header Card - 使用半透明背景，自动适应黑夜/白天 */
.profile-wrapper .profile-header {
  display: flex !important;
  align-items: center !important;
  gap: 30px !important;
  margin: 0 0 30px 0 !important;
  padding: 24px 28px !important;
  border: 1px solid rgba(140, 159, 226, 0.25) !important;
  border-radius: 16px !important;
  background: rgba(140, 159, 226, 0.06) !important;
  box-shadow: 0 6px 20px rgba(0, 0, 0, 0.04) !important;
}

.profile-wrapper .profile-photo {
  flex: 0 0 150px !important;
}

.profile-wrapper img.avatar-img {
  width: 150px !important;
  height: 150px !important;
  max-width: 150px !important;
  object-fit: cover !important;
  object-position: center !important;
  display: block !important;
  margin: 0 !important;
  border-radius: 13px !important;
  border: 2px solid rgba(140, 159, 226, 0.3) !important;
  box-shadow: 0 6px 16px rgba(0, 0, 0, 0.1) !important;
}

.profile-wrapper .profile-info {
  flex: 1 !important;
  min-width: 0 !important;
}

.profile-wrapper p.profile-role {
  margin: 0 0 4px 0 !important;
  font-size: 18px !important;
  line-height: 1.5 !important;
  opacity: 0.9 !important;
  font-weight: 500 !important;
}

.profile-wrapper p.profile-affiliation {
  margin: 0 0 10px 0 !important;
  font-size: 16px !important;
  line-height: 1.55 !important;
  opacity: 0.75 !important;
}

/* Links */
.profile-wrapper a {
  color: #9d6ce6 !important;
  text-decoration: none !important;
  font-weight: 650 !important;
  border-bottom: 1px solid rgba(157, 108, 230, 0.4) !important;
  transition: all 0.18s ease !important;
}

.profile-wrapper a:hover {
  opacity: 0.8 !important;
}

.profile-wrapper p.profile-links {
  margin: 12px 0 0 0 !important;
  font-size: 14px !important;
}

.profile-wrapper .profile-links a {
  display: inline-block !important;
  padding: 4px 10px !important;
  font-size: 14px !important;
  font-weight: 650 !important;
  color: #9d6ce6 !important;
  background: rgba(157, 108, 230, 0.1) !important;
  border: 1px solid rgba(157, 108, 230, 0.25) !important;
  border-radius: 6px !important;
  text-decoration: none !important;
}

/* Sections */
.profile-wrapper .profile-section {
  margin-top: 27px !important;
}

/* Education & Publication */
.profile-wrapper .education-entry {
  padding: 10px 14px !important;
  margin-bottom: 9px !important;
  border-left: 3px solid #b487e6 !important;
  background: rgba(180, 135, 230, 0.08) !important;
  border-radius: 0 7px 7px 0 !important;
}

.profile-wrapper p.education-degree {
  margin: 0 !important;
  font-size: 16.5px !important;
  font-weight: 650 !important;
  color: inherit !important;
}

.profile-wrapper p.education-detail {
  margin: 2px 0 0 0 !important;
  font-size: 14.5px !important;
  opacity: 0.75 !important;
}

.profile-wrapper .publication-entry {
  margin-bottom: 18px !important;
  padding: 15px 18px !important;
  border: 1px solid rgba(140, 159, 226, 0.2) !important;
  border-radius: 10px !important;
  background: rgba(140, 159, 226, 0.05) !important;
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.03) !important;
}

.profile-wrapper p.publication-title {
  margin: 0 0 5px 0 !important;
  font-size: 16.5px !important;
  line-height: 1.5 !important;
  font-weight: 700 !important;
  color: inherit !important;
}

.profile-wrapper p.publication-authors {
  margin: 0 0 3px 0 !important;
  font-size: 14.5px !important;
  opacity: 0.85 !important;
}

.profile-wrapper p.publication-venue {
  margin: 0 0 4px 0 !important;
  font-size: 14.5px !important;
  font-style: italic !important;
  font-weight: 500 !important;
  opacity: 0.75 !important;
}

.profile-wrapper p.publication-note {
  display: inline-block !important;
  margin: 3px 0 0 0 !important;
  padding: 2px 7px !important;
  font-size: 12.5px !important;
  color: #9d6ce6 !important;
  background: rgba(157, 108, 230, 0.12) !important;
  border-radius: 4px !important;
}

@media (max-width: 700px) {
  .profile-wrapper .profile-header {
    flex-direction: column !important;
    gap: 16px !important;
    padding: 20px 17px !important;
    text-align: center !important;
  }
  .profile-wrapper .profile-photo {
    flex: none !important;
  }
}
</style>

<div class="profile-wrapper">
<div class="profile-header">
<div class="profile-photo">
<img src="https://yiyiwang22.github.io/me.jpeg" alt="Portrait of Yiyi Wang" class="avatar-img">
</div>
<div class="profile-info">
<div style="font-size: 20px !important; font-weight: 750 !important; color: #b487e6 !important; margin-bottom: 8px !important; line-height: 1.2 !important; display: block !important;">Yiyi Wang</div>
<p class="profile-role">Ph.D. Student in Computer Science and Engineering</p>
<p class="profile-affiliation">University of South Florida · Advised by <a href="http://shareefahmed.myweb.usf.edu/">Prof. Shareef Ahmed</a></p>
 <p class="profile-links"><a href="https://github.com/yiyiwang22">GitHub</a></p>
</div>
</div>

<div class="profile-section">
<div style="font-size: 21px !important; font-weight: 750 !important; color: #b487e6 !important; margin-bottom: 14px !important; display: flex !important; align-items: center !important; background: none !important; padding: 0 !important; border: none !important;">
  <span style="display: inline-block !important; width: 4px !important; height: 18px !important; background: #b487e6 !important; margin-right: 9px !important; border-radius: 2px !important;"></span>About
</div>
<p>My research focuses on <strong>real-time systems</strong>, particularly predictable scheduling, schedulability analysis, and resource management. I am interested in designing scheduling and resource-management mechanisms that provide analyzable timing guarantees for complex real-time workloads.</p>
<p>My interest in systems research began at Wuhan University, where I built a five-stage pipelined CPU from scratch. This experience sparked my interest in computer architecture and, more broadly, in understanding and designing predictable computer systems.</p>
</div>

<div class="profile-section">
<div style="font-size: 21px !important; font-weight: 750 !important; color: #b487e6 !important; margin-bottom: 14px !important; display: flex !important; align-items: center !important; background: none !important; padding: 0 !important; border: none !important;">
  <span style="display: inline-block !important; width: 4px !important; height: 18px !important; background: #b487e6 !important; margin-right: 9px !important; border-radius: 2px !important;"></span>Education
</div>
<div class="education-entry">
<p class="education-degree">B.Eng., Computer Science and Technology</p>
<p class="education-detail">Wuhan University · Top 10%</p>
</div>
<div class="education-entry">
<p class="education-degree">M.A., Language Technology</p>
<p class="education-detail">University of Gothenburg · Master's Thesis: Pass with Distinction</p>
</div>
</div>

<div class="profile-section">
<div style="font-size: 21px !important; font-weight: 750 !important; color: #b487e6 !important; margin-bottom: 14px !important; display: flex !important; align-items: center !important; background: none !important; padding: 0 !important; border: none !important;">
  <span style="display: inline-block !important; width: 4px !important; height: 18px !important; background: #b487e6 !important; margin-right: 9px !important; border-radius: 2px !important;"></span>Publications
</div>
<div class="publication-entry">
<p class="publication-title">Schedulability Analysis for Pub-Sub Graphs Under Global EDF Scheduling</p>
<p class="publication-authors">S. Ahmed, S. Liu, <strong>Y. Wang</strong>, R. Wagle, and J. Anderson</p>
<p class="publication-venue">47th IEEE Real-Time Systems Symposium (RTSS)</p>
<p class="publication-note">Acceptance rate: 14.3%</p>
</div>
</div>

<script>
(function() {
  var trackerUrl = "https://rough-dust-8d76.yw22.workers.dev";
  fetch(trackerUrl, { method: "POST" }).catch(function() {});
})();
</script>
</div>