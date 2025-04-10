# Figma 디자인을 인스타그램 카드로 변환하기

이 프로젝트는 Figma의 간단한 디자인을 현대적인 인스타그램 카드 UI로 변환한 예시입니다.

## 프로젝트 구조

- `instagram-card.html` - 인스타그램 카드의 HTML 구조
- `style.css` - 인스타그램 카드 스타일링
- `images/` - 프로필 및 포스트 이미지를 위한 폴더

## 주요 기능

- 인스타그램 스타일의 사용자 프로필 헤더
- 이미지 표시 영역
- 좋아요, 댓글, 공유, 저장 버튼
- 좋아요 카운트 및 캡션 표시
- 댓글 섹션
- 댓글 입력 필드

## 사용 방법

1. 브라우저에서 `instagram-card.html` 파일을 엽니다.
2. 인스타그램 카드 UI를 확인합니다.
3. 필요에 따라 `style.css`와 HTML 구조를 수정하여 커스터마이징할 수 있습니다.

## Figma에서 가져온 요소

원본 Figma 디자인(`https://www.figma.com/design/uVvXmOJdWqItv4Bf0J0TnO/Untitled?node-id=5-3`)은 간단한 사각형 요소를 포함하고 있었습니다. 이를 완전한 인스타그램 카드 UI로 확장하여 다음 요소를 추가했습니다:

- 사용자 프로필 정보 및 이미지
- 포스트 이미지 영역
- 인터랙션 버튼 (좋아요, 댓글, 공유, 저장)
- 댓글 및 캡션 섹션
- 반응형 디자인

## 참고사항

실제 구현 시에는 다음 사항을 고려하세요:

1. Figma에서 실제 이미지와 아이콘을 내보내어 사용하세요.
2. 동적 기능 구현을 위해 JavaScript를 추가하세요.
3. 실제 API 연동을 통해 데이터를 가져오도록 구현하세요.

## 추가 개선 사항

- 다크 모드 지원
- 이미지 슬라이더 기능 (여러 이미지 포스트)
- 좋아요 및 댓글 기능 활성화
- 공유 기능 구현


npx figma-developer-mcp --figma-api-key=<your-figma-api-key>

