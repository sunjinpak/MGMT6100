# MGMT 6100 Website Project Note

## Project Overview
- **Purpose**: MGMT 6100 Human Resources Management 수업 자료 웹사이트
- **Platform**: GitHub Pages with Jekyll (Cayman theme)
- **Created**: January 2026

## Live URLs
- **Website**: https://sunjinpak.github.io/MGMT6100/
- **GitHub Repo**: https://github.com/sunjinpak/MGMT6100

## File Structure
```
website/
├── _config.yml              # Jekyll 설정
├── index.md                 # 홈페이지
├── syllabus.md              # 실러버스
├── roster.md                # 학생 명단
├── team-meeting-rubric.md   # 팀 미팅 루브릭
├── team-presentation-rubric.md  # 팀 프레젠테이션 루브릭
├── team-meeting-1.md ~ 11.md    # 팀 미팅 어젠다
├── convert_to_word.py       # Markdown → Word 변환 스크립트
├── *.docx                   # Word 다운로드 파일들
└── assets/
    └── css/
        └── style.scss       # 커스텀 CSS 스타일
```

## CSS 테이블 스타일 설정

### 파일 위치
`assets/css/style.scss`

### 전체 CSS 코드
```scss
---
---

@import "jekyll-theme-cayman";

/* Custom styles for MGMT 6100 */

/* Tables: fit within screen, auto column sizing */
.main-content table {
  width: 100% !important;
  max-width: 100% !important;
  display: table !important;
  table-layout: auto !important;
}

/* Table cells: wrap text properly */
.main-content table th,
.main-content table td {
  padding: 8px 12px;
  word-wrap: break-word;
  overflow-wrap: break-word;
  word-break: break-word;
}
```

### CSS 설명
| 규칙 | 적용 대상 | 효과 |
|------|-----------|------|
| 전체 테이블 | 모든 테이블 | 화면 너비 100%, 자동 컬럼 크기 |
| 테이블 셀 | 모든 셀 | 텍스트 줄바꿈 (word-break) |

**참고**: 컬럼별 너비 지정 규칙은 테이블 간 충돌을 일으켜 제거함. 브라우저가 콘텐츠에 따라 자동으로 너비 결정.

## 실러버스 포맷팅 규칙

### 헤더 섹션 (중앙 정렬 + 줄바꿈)
웹과 Word 모두에서 중앙 정렬과 줄바꿈을 적용하려면 HTML 태그 사용:

```html
<h2 style="text-align: center">MGMT 6100 Human Resources Management</h2>
<h3 style="text-align: center">Spring 2026 (3 units)</h3>

<p style="text-align: center">
<strong>Jan 20 Tue - May 18 Mon, 2026</strong><br>
<strong>TuTh 7:00 PM - 8:15 PM; Business Development Ctr 165B</strong>
</p>

<p style="text-align: center"><em>This syllabus is subject to change based on the needs of the class.</em></p>
```

### 줄바꿈 (`<br>` 태그)
- **웹**: `<br>` 태그가 그대로 렌더링됨
- **Word**: `convert_to_word.py`가 `<br>`를 `⏎` 마커로 변환 후, Word 줄바꿈(`w:br`)으로 변환
- 테이블 셀과 일반 텍스트 모두에서 작동

### Instructor 정보 예시
```markdown
**Instructor:** Sunjin Pak, Assistant Professor of Management<br>
**Office:** BDC A137<br>
**Office hours:** Tuesday/Thursday 6:00-7:00 PM or by appointment
```

## Word 변환 스크립트

### 사용법
```bash
cd ~/Obsidian/Teaching/MGMT\ 6100/website
python3 convert_to_word.py
```

### 주요 기능
- Jekyll front matter 제거
- 네비게이션 링크 제거 ("← Back to Home", "Download Word Document")
- HTML 태그를 Markdown으로 변환 (`<h2>` → `##`, `<strong>` → `**`)
- `<br>` 태그를 Word 줄바꿈으로 변환 (테이블/일반 텍스트 모두)
- 실러버스 헤더 중앙 정렬
- 상대 링크를 GitHub Pages 절대 URL로 변환
- 테이블 검정 테두리 추가
- 테이블 너비 100% 설정
- 하이퍼링크 파란색 밑줄 처리

## Maintenance

### 새 문서 추가 시
1. Obsidian에서 문서 작성
2. website 폴더에 복사 (파일명: lowercase-with-hyphens.md)
3. Jekyll front matter 추가
4. `convert_to_word.py`에 파일 추가
5. `python3 convert_to_word.py` 실행
6. index.md에 링크 추가
7. git add, commit, push

### 문서 수정 시
1. Obsidian에서 수정
2. website 폴더에 복사
3. `python3 convert_to_word.py` 실행
4. git add, commit, push

## Change Log

| 날짜 | 변경 내용 |
|------|-----------|
| 2026-01-16 | CSS 테이블 스타일 단순화 - 컬럼별 너비 규칙 제거, 자동 너비 + 텍스트 줄바꿈으로 변경 |
| 2026-01-16 | 실러버스 헤더 중앙 정렬 (HTML 태그 사용) |
| 2026-01-16 | Google Doc 실러버스 링크 추가 |
| 2026-01-16 | Team Meeting Agenda 1-11 Word 다운로드 버튼 추가 |
| 2026-01-16 | Course Materials (Syllabus, Roster, Rubrics) Word 다운로드 버튼 추가 |
| 2026-01-16 | Class Participation Report 링크 추가 |
| 2026-01-16 | 실러버스 Course Agenda 내부 링크 수정 (23개) |
| 2026-01-16 | Word 변환 스크립트 줄바꿈 버그 수정 - ⏎ 마커를 실제 줄바꿈으로 변환하도록 개선 |
