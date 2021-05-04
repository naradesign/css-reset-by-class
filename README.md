# css-reset-by-class

CSS reset by class 스타일은 reset.css, normalize.css의 unused, overridden 문제를 극복하기 위한 아이디어입니다.

1. Less overwrite.
2. Do not predefine unused CSS.
3. Effective restriction of selectors.
4. Multilingual readability.


## Less overwrite.
* 전역 초기화를 최소화하여 CSS 스타일 덮어쓰기를 제한한다.


## Do not predefine unused CSS.
* 사용하지 않는 요소를 미리 정의하지 않아 바이트를 낭비하지 않는다.


## Effective restriction of selectors.
* class 선택자만 사용하도록 유도하므로 복잡도를 효과적으로 제한하고 관리할 수 있다.
* class 선택자를 사용할 때 개발자에게 유용한 스타일로 초기화한다.
* 사용자가 생성한 HTML은 UA(User Agent) 초기 스타일로 표시한다.


## Multilingual readability.
* 다국어 문서를 단어 단위로 줄 바꿈한다. 
* 박스보다 큰 단어는 박스 끝에서 감싼다.
