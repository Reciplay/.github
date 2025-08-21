<p align="center">
  <picture>
    <!-- 다크 모드일 때 흰색 로고 -->
    <source
      srcset="https://raw.githubusercontent.com/PathFinder-2025/resources/main/path-finder-logo-white.png"
      media="(prefers-color-scheme: dark)" />
    <!-- 라이트 모드일 때 검은색 로고 -->
    <source
      srcset="https://raw.githubusercontent.com/PathFinder-2025/resources/main/path-finder-logo-black.png"
      media="(prefers-color-scheme: light)" />
    <!-- picture 태그 미지원 브라우저용 fallback -->
    <img
      src="https://raw.githubusercontent.com/PathFinder-2025/resources/main/path-finder-logo-black.png"
      alt="Path Finder Logo"
      width="200" />
  </picture>
</p>

# Path Finder

> 삼성청년SW아카데미 13기 팀 프로젝트

---

## 🚀 프로젝트 소개

Path Finder는 사용자가 **여행 도시**, **여행 기간**, **여행 테마**를 선택하면  
관광지 추천과 자동 여행 일정 수립을 지원하는 웹 서비스입니다.

[![영상 링크](https://i.ytimg.com/an_webp/zj-pUPFEg_Q/mqdefault_6s.webp?du=3000&sqp=CJik0sEG&rs=AOn4CLCFhGy6WSOzIyc1k7hwM5OlLX-xuA)](https://www.youtube.com/watch?v=zj-pUPFEg_Q)
---

## ✨ 주요 기능

- **관광지 추천**  
  여행 도시 및 테마 기반으로 데이터베이스에서 후보 관광지 필터링  
- **일정 자동 생성**  
  선택된 관광지를 여행 일수에 맞춰 날짜별로 그룹화(클러스터링)  
- **최단 경로 계산**  
  각 그룹 내 관광지 간 최적 이동 경로 계산 및 추천
  
