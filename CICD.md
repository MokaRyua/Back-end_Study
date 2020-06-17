# CI & CD

여러분들은 이제부터 공사장 노동자 입니다. 그리고 전 제 3자로써 아무것도 모른체 물어봅니다.

"건물을 다 짓고 피드백을 들으면서 보수공사를 하는게 좋습니까? 피드백을 들으면서 건물을 짓는게 좋습니까?"

여러분들은 어떤 선택을 하실껀가요? 제 생각에는 대부분 후자를 선택할 것이라고 생각합니다. 누가 다짓고 

귀찮게 다시 보강합니까? 이제 다른 질문입니다. 이것이 코드에 적용된다면 어떨꺼 같습니까? 진짜 짱이죠

매일매일 여러명에서 깃에다가 푸쉬하고 에러난거 일일이 다 확인하고 고치고 많이 귀찮습니다. 그래서 

나온 개념이 CI/CD입니다.  그럼 개념 설명 들어갑니다.

___

### CI(Continuous Integration)

__CI__는 빌드 및 테스트 자동화입니다. 얼마나 편합니까? 내가 귀찮게 하나하나 일일이 귀찮게 했던 것들이 자동으로 해준다니!?!?!? 

??? : "아 그럼 어렵겠지 개념도 어렵고 하기 싫다~" 이러는 사람이 있다면 내가 말해주겠다. 한줄로 설명 가능하다.

- __CI는 빌!드!및!테!스!트!자!동!화!__ 뭐 이게 끝이다. 더이상 설명할 것이 없다. 하고 싶어도 없어서 못한다.



___

### CD(Continuous Deploy 또는 Delivery)

__CD__는 배포 자동화 이게 끝이다. 여러분들이 aws putty를 이용해 배포를 해보았다면 이것이 얼마나 편리한지 

알 것이다 git에서 clone 해오고 코드가 수정되면 pull히고 다시 실행하고 코드가 수정 될 때 마다 일일이 다 

해준것을 자동화 시킨것이다. 이 얼마나 아름다고 이쁜 것이더냐. CD또한 더이상 설명 할 것이 없다...

- __CD는 배!포!자!동!화!__ 이게 끝이다.

___

### 결론

CD는 CI를 해야지 할 수 있는거라 자동으로 같이 따라오는 형제? 같은거다.

이론은 이해하기 쉬우나 그것을 구현하는 것은 또 다른 이야기이다.

CI/CD 를 자동화하기 위해서는 고려해야할 부분이 생각보다 많으며,

언제, 어떤 자동화 프로세스를, 어떻게 돌리고, 어떤 방식으로 결과를 리포트할지 등의 절차를 매우 엄밀하게 정의해야한다.

다해이게도  Travis, Jenkins 와 같이, CI/CD 자동화를 조금이나마 쉽게 구현가능하게 해주는 것들이 있다.

서버를 어느정도 짤 준 안다면 해보는 것을 추천한다.