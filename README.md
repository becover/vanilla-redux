#vanilla-redux

리덕스를 이해해보는 예제

- 19.12.29 
  - 튜토리얼보고 parcel-bundler를 설치했으나 계속 parcel index.html 선언을 실행할 수 없다며 빌드되지 않아 3시간 넘게 씨름했다. (parce command not found 뜸)
  - package.json에 scripts로 start를 지정해주고 쓰면 되긴하는데 왜 parcel (entry file)을 쓰면 안되는걸까? npm list -g --depth=0으로 확인하면 번들러가 글로벌로 잘 설치되어있고, 실제 파일에 가도 잘 설치되어있었다. alias parcel="경로/npm/parcel"해줘도 안되고 재설치도 소용없고.. 정말 프로젝트 세팅에서부터 이럴때가 제일 막막하다. 빨리 더 경험을 채우고 아는게 늘었으면 좋겠다.
  - vim .bashrc에 직접 등록시켜서 사용은 하지만 여전히 왜 안되었던건진 모르겠어서 답답한 상태.. 다른 폴더에 똑같이 세팅해도 같은 현상이라 당분간 안될땐 이 방법으로 직접 세팅해줘야겠따. vim 모드에선 i눌러서 작성하고 모두 작성후 esc :wq 엔터! (write quite 약자) (도와주신 k님 너무너무 감사합니다!!)