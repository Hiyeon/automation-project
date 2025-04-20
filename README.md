# Automation Project

## 1. 구글 이미지 썸네일 다운로드
- **Notebook:** [1_google_thumbnails_download.ipynb](./1_google_thumbnails_download.ipynb)
- **내용:** Python의 웹 자동화 도구인 **Selenium**을 사용하여, 키워드 기반으로 구글 이미지 검색 결과에서 썸네일 이미지를 자동 수집. 스크롤 조작, 이미지 필터링, 폴더 생성, 저장까지 전 과정을 자동화한 코드.
- **참고 링크:** [Python으로 구글 이미지 자동 수집하기 (Selenium 기반)](https://hi2world.tistory.com/entry/Python%EC%9C%BC%EB%A1%9C-%EA%B5%AC%EA%B8%80-%EC%9D%B4%EB%AF%B8%EC%A7%80-%EC%9E%90%EB%8F%99-%EC%88%98%EC%A7%91%ED%95%98%EA%B8%B0-Selenium-%EA%B8%B0%EB%B0%98-%ED%81%AC%EB%A1%A4%EB%9F%AC)

## 2. TechCrunch 뉴스 요약본 Slack으로 보내기 자동화
- **Workflow:** [2_techcrunch2slack.json](./2_techcrunch2slack.json)
- **TechCrunch 링크:** [TechCrunch AI 카테고리](https://techcrunch.com/category/artificial-intelligence)
- **내용:** n8n과 Google Gemini API를 활용하여 TechCrunch의 최신 AI 뉴스 10건을 요약하고, 포맷된 Slack Block Kit 메시지로 지정 채널에 자동 전송.
- **참고 링크:** [클로드 MCP로 안 되던 거, n8n으로 뚫었습니다! (커스텀 툴 구축 포함)](https://youtu.be/eOS1TLqA4tY?si=OMCEugfmviha8rLz)
