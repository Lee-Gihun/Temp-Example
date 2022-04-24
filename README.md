# Temp-Example
Temporary Example for Clean Code

## 작은 PR 규칙

코드의 길이가 길어질수록 리뷰어의 집중도는 떨어질 수밖에 없다. 코드를 이해하는 시간이 길어지고, 리뷰는 목표한 일정에 완료되지 못하고, 병목이 된다. 코드 리뷰가 임팩트를 내는 부분에 있어서 병목이 되지 않도록 '작은 PR 규칙' (1개의 PR은 1,000 Line을 넘을 수 없다)를 정하자

- 1 개의 PR은 1,000 Line 을 넘을 수 없다.
- Pull Request, Commit의 단위는 최소의 기능 단위로 세분화한다.

## Commit을 위한 규칙

**제목 맨 앞 글자는 대문자로 작성** 

1. Update : 새로운 기능 추가, 코드 보강
2. Fix : 각종 버그 픽스
3. Refactor : 이름 변경, 경로 이동 등등
4. Remove :  각종 삭제시 사용한다. 단, 파일 단위 삭제는 refactor를 사용한다.
5. Merge
6. Style : 스타일 관련 기능(코드 포맷팅, 세미콜론 누락, 코드 자체의 변경이 없는 경우)
7. Misc : 빌드 업무 수정, 패키지 매니저 수정(ex .gitignore 수정 같은 경우)
8. Test: 테스트 코트, 리펙토링 테스트 코드 추가
9. Hotfix : 긴급하게 Master Branch로 수정사항 반영이 필요한 경우

**Commit Message 예시**


Fix - 모델 input shape 오류 수정

Refactor - Data Pipeline 변경

Style - Black Implemented
---

## Code Formatting을 위한 규칙

`pip install black` & `black ./`
Black is the uncompromising Python code formatter. By using it, you agree to cede control over minutiae of hand-formatting. In return, Black gives you speed, determinism, and freedom from pycodestyle nagging about formatting. You will save time and mental energy for more important matters.
