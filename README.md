# KorLibraryCheater

LibraryCheater는 한국인들이 라이브러리 탐색을 편하게 할수있도록 도와줍니다.
0. help()로는 탐색이 어려운 크기의 라이브러리가 있습니까?
1. 먼저 라이브러리의 최상위 모듈을 입력받아 검색합니다
2. 다음으로 선택한 모듈의 클래스와 함수를 검색합니다
3. 마지막으로 선택한 클래스와 함수의 매개변수를 검색합니다

현재는 sklearn만 구현되어있습니다.

from korlibrarycheater import sk_library_cheater
sk_library_cheater()
