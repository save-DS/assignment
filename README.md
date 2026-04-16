# 자료구해조 규칙

## Git Commit Convention(커밋 규칙)

효율적인 협업을 위해 다음과 같은 커밋 메시기 규칙을 사용합니다.
| 커밋 타입 | 설명 |
|-----------|------------------------------------------------|
| 🎉 `FEAT` | 새로운 기능 추가 |
| 🐛 `FIX` | 버그 및 오류 수정 |
| 🛠 `CHORE` | 코드 수정, 내부 파일 수정 |
| 📝 `DOCS` | 문서 수정 (README 등) |
| 🔄 `REFACTOR` | 코드 리팩토링 (기능 변경 없음) |
| 🧪 `TEST` | 테스트 코드 추가 및 수정 |

## 작업 방식

본인 브랜치에서 작업 시작 -> 브랜치 이름은 본인이름으로 해주세요
git checkout -b (이름)

### 작업 후 커밋

git add .
git commit -m "feat(main-page): 메인 페이지 구성 및 ui 요소 렌더링"

### 원격 저장소에 푸시 및 PR 생성(예시)

git push origin (이름)
GitHub에서 Pull Request(PR) 생성 → develop 브랜치에 병합

### 절대 main에 올리지 말기!
