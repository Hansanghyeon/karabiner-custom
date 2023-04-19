# karabiner-custom

<img width="1212" alt="스크린샷 2023-04-19 오전 9 06 10" src="https://user-images.githubusercontent.com/42893446/232930587-fabd793c-1bb4-4ff6-b26b-bfecc776192c.png">

기본적으로 위와같이 유명한 rule들은 karabiner에서 제공하는 게시판에서 어느정도 다운로드하고 임포트할수있다.

하지만 내가 룰을 만들어서 업데이트하고싶다면?

<img width="1212" alt="스크린샷 2023-04-19 오전 9 07 09" src="https://user-images.githubusercontent.com/42893446/232930685-46df6754-615b-41be-a2c2-65dae0d1be9f.png">

Misc에 들어가서 Open config foler를 열어준다. 해당 폴더를 text editor로 연다.

커스텀해서 만든 설정을 `profiles[0].complex_modifications.rules[0]`에다 객체로 추가하면된다.

json을 따로 임포트하게하는 방법은 아직 찾지 못하였다.
