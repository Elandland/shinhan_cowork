# Github Commit Message Convention
```
Feat : 새로운 기능을 추가할 경우
Fix : 버그를 고친 경우
Design : CSS 등 사용자 UI 디자인 변경
!BREAKING CHANGE : 커다란 API 변경의 경우
!HOTFIX : 급하게 치명적인 버그를 고쳐야하는 경우
Style : 코드 포맷 변경, 세미 콜론 누락, 코드 수정이 없는 경우
Refactor : 프로덕션 코드 리팩토링
Comment : 필요한 주석 추가 및 변경
Docs : 문서를 수정한 경우
Test : 테스트 추가, 테스트 리팩토링(프로덕션 코드 변경 X)
Chore : 빌드 태스트 업데이트, 패키지 매니저를 설정하는 경우(프로덕션 코드 변경 X)
Rename : 파일 혹은 폴더명을 수정하거나 옮기는 작업만인 경우
Remove : 파일을 삭제하는 작업만 수행한 경우
```

# HTML Convention
* 들여쓰기는 공백(space) 2문자를 사용한다.
* 속성값에는 반드시 큰따옴표("")를 사용한다
* 태그명, 속성명, 속성값 등에는 모두 소문자만 사용한다.
* HTML 문서 형식을 명확하게 지정한다.
* Boolean 속성은 값을 따로 명시하지 않는다.
* 불필요한 태그 작성을 피한다
* 목적에 맞는 HTML 태그를 사용한다.
* 엔티티 참조는 사용하지 않는다.
* css/자바스크립트 파일을 불러오는 경우 type을 명시하지 않는다.
* css는 상단, 자바스크립트는 하단에 불러온다.

# CSS Convention
* 들여쓰기는 공백 2문자를 사용한다
* 클래스, 아이디 명은 -를 사용하는 케밥 케이스를 사용한다.
* 선언 블록은 여는 중괄호({) 앞에 공백 1문자를 넣고 닫는 중괄호(})는 새로운 행에 배치한다.
* 선언시 : 이후 공백 1문자를 추가한다.
* 단일 스타일은 한줄, 다중 스타일은 한줄에 하나씩 표시한다.
* 스타일 지정시 아이디 대신 클래스를 사용한다.
* 자바스크립트 Hook에서 스타일 지정을 위해 만들어진 클래스를 사용하지 않는다.
* 숫자 0값 이후에는 불필요한 단위를 작성하지 않는다.
* border이 없을때는 none이 아닌 0을 사용한다.
* 16진법 컬러는 될 수 있으면 3글자로 표현한다.
* 태그 선택자 대신 클래스 선택자를 사용한다.
* 선택자 길이는 최대 3개이상 넘지 않게 제한한다. 부모선택자를 표시해야한다면 꼭 필요한 경우만 작성한다.
* 축약이 가능한 프라퍼티는 축약해서 사용한다.
* @import 대신 <link>를 사용한다
