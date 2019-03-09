## 1-week

> [Tutorial 1: Serialization](https://www.django-rest-framework.org/tutorial/1-serialization/#tutorial-1-serialization) & [Tutorial 2: Requests and Responses](https://www.django-rest-framework.org/tutorial/2-requests-and-responses/#tutorial-2-requests-and-responses)

- api란 무엇인가?
  - html덩어리를 응답하는 것이아니라 json을 응답
  - 왜 api를 쓸 것인가?
  - 현재 프로젝트가 프론트와 서버로 나뉘어서 따로 개발해서 협업해야하기 때문에, api를 만들 수 있어야함
  - api 잘 되어있는 문서: https://naver.github.io/searchad-apidoc/#/guides
  - 지금은 프론트와 협업하기 위해 html을 응답하는 것이 아닌 json형태의 퓨어한 데이터를 응답하는 것으로 이해하자
- 승준 궁금했던 점 
  - Csrf_Token을 왜 drf에선 안쓰는가?
    - https://www.slideshare.net/EunhyangKim2/ss-118560530
- 경준 궁금했던 점
  - 왜 하필 json을 쓸까? (자문 자답)
    - 모든데서 잘 통용돼서? 
    - 대부분 딕셔너리 자료형이 있는데 이와 비슷해서(성일) 
  - `format_suffix_patterns` 는 뭐야?
    - json이나 api확장자에 맞는 형식으로 return해줌
- 한울 궁금한점
  - Deserializer을하는 과정이 이해가안된다
  - 굳이 dictionary를 왜 json형태로 바꾸는가?
  - Serailizer은 인스턴스도 받고 data도 받는데 직렬화, 비직렬화 둘 다 가능한것인가?
- 기타
  - Restful하다는 것은 무엇인가, 왜 쓰는가
  - python generator, iterator은 무엇인가?
- 첫 주 스터디 피드백
  - 승준
    - 좋았던 점: 다들 열심히 준비한것같다!
    - 안좋은 점: 공영방송의 일부만 출현을 한 것 같다. (모두가 질문하고 참여해야하는데)
      - => 멘토를 양쪽에 앉힐까?  …. 그럼 더 지역방송화 될듯
      - => pull request로 실시간으로 많이 해결을 하자 
      - 웬만하면 월요일까지 올리자..(안올려도 됨)
  - 성일
    - 질문을 다들 많이 해서 놓칠 수 있는 부분을 알 수 있어서 좋았음
    - 모임 시간이 짧다..
      - => 시간되는 사람들 먼저만나자…? 흐어어 장고 스터디는 소모임을 적극 .. 지지합니다.. 
      - 슬랙 활성화하자 + 풀리퀘 활성화하자
  - 경준
    - 지각을 안했으면 좋겠음. (지각비 걷어서 회식합시다!!!)
      - => 지각비 1분에 500원 최대 5000원
    - 첫주여서 감잡는 느낌, 어떻게 더 잘할 수 있을지 (스터디 방식) 각자 많이 생각해오자
  - 주은 (…) 좋다…! 
  - 상은
    - 멘토뿐만아니라 경준 + 성일도 많이 설명해줘서 고맙..
  - 수민
    - 앞으로 열심히 해야지..! 화이팅!! 
    - 기초적인 질문을 (모르면 몰라서 질문을 못해서…) 해서 좋다 (아는 사람도 다시 되짚어 보는 기회였다)
  - 예원
    - 기초적인 내용이라도 계속 반복해서 얘기하면 고마울듯!
    - 개인적으로 승준멘토가 설명하는중 질문있냐고 물어보는 방식이 최대한 지켜줬음 좋겠다. (질문이 꼬리에꼬리를 무니까 모른다는걸 알게돼서 더 좋았음)
  - 한울
    - 진짜 배운것도 많고 동기부여 많이돼서 너무 유익했다! 다들 감사해(비장한 말투)
  - 기타의견
    - 스터디 시작할 때 풀리퀘 한 번씩 리뷰하는 시간 갖자
    - 트렐로팔까? 
    - 멘토로서 걱정되는 부분으로는 따라가다 놓치면 바로 피드백해주면 좋겠다. (승준)
    
    

