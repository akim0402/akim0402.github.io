---
layout: default
title: Data & Resources
---
<style>
  /* 1. 스크롤바 생기더라도 화면이 좌우로 덜컥거리지 않도록 강제 여백 확보 */
  html {
    overflow-y: scroll;
  }

  /* 2. 전체 레이아웃 너비 고정 및 Flex 배치 */
  .wrapper {
    max-width: 1100px !important;
    display: flex !important;
    justify-content: space-between !important;
    align-items: flex-start !important;
    gap: 30px !important;
  }

  /* 3. 왼쪽 프로필 너비 고정 */
  header {
    width: 280px !important;
    min-width: 280px !important;
    position: static !important;
    float: none !important;
    margin: 0 !important;
  }

  /* 4. 오른쪽 본문 너비 자동 확장 */
  section {
    flex: 1 !important;
    width: auto !important;
    max-width: none !important;
    float: none !important;
    position: static !important;
    margin: 0 !important;
  }
</style>

<!-- 왼쪽 정렬 -->
<div style="text-align: left; margin-bottom: 20px; font-size: 0.95em;">
  <a href="/">Home</a> | 
  <a href="/publications">Publications</a> | 
  <a href="/teaching">Teaching</a> | 
  <a href="/resources">Data & Resources</a> 
  <a href="/people">People</a> | | 
  <a href="https://sites.google.com/site/akim0402" target="_blank">CV (PDF)</a>
</div>
---

# Data & Resources

<!-- Index of Relative Rurality (IRR) 세부 페이지 연결 카드 -->
<div style="margin: 15px 0; padding: 12px 22px 20px 22px; background-color: #f8f9fa; border-left: 4px solid #2c3e50; border-radius: 6px;">
  <h3 style="margin-top: 0; margin-bottom: 10px; color: #2980b9; font-size: 1.25em;">
    Index of Relative Rurality (IRR)
  </h3>
  <p style="margin-bottom: 18px; line-height: 1.6; color: #333;">
    The Index of Relative Rurality (IRR) is a continuous measure of rurality for U.S. counties, bounded between 0 (most urban) and 1 (most rural). It captures fine-grained spatial and demographic variations based on population size, density, remoteness, and built-up area.
  </p>
  <a href="/irr" style="display: inline-block; padding: 10px 18px; background-color: #2c3e50; color: #ffffff !important; text-decoration: none; border-radius: 4px; font-weight: bold; font-size: 0.9em;">
    View Interactive Map & Download Data →
  </a>
</div>
