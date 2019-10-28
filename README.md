# FindingTheater-iOS-
## 시작하게 된 계기 

> 현재 영화관하면 떠오르는 영화관은 세 개의 큰 영화사들이다. 각각의 영화사는 각각의 영화 어플을 갖고 있다. 
그렇기에 어떤 영화를 보고 싶다면 어떤 영화사에서 영화를 볼지 먼저 정한 뒤에 가까운 영화관을 찾곤 한다.<br>
이러한 방법보다 영화사에 관계없이 가장 가까운 영화관들의 목록을 찾아주면 좋지 않을까 라는 생각을 하게 되었고, 그렇게 프로젝트를 설정하게 되었다.

## 구성

> 각 화면이 하는 일을 역할 별로 구분해보았다.<br>(!! 맨처음 어플을 실행할 때 위치 정보 사용에 동의하는지 묻는다.)

1. **초기화면**<br>
초기화면에서는 현재 상영 중인 영화 포스터를 순위 별로 나열한다.<br>
영화 포스터 화면 밑에는 두 개의 버튼이 존재 한다. 영화 정보 버튼과 영화관 찾기 버튼이다.<br>
위 쪽에는 좌석 보기 버튼이 있는데 해당 좌석에서 영화가 어떤 식으로 보일지 보여주는 버튼이다.<br>

2. **영화 정보 화면**<br>
영화 정보 화면에서는 선택한 영화의 정보들이 나와있다. <br>
영화 이름, 감독, 출연 배우, 러닝 타임 등등의 정보를 담고 있다.

3. **지하철 역 및 현재 위치 화면**<br>
초기 화면에서 영화관 찾기 버튼을 누르게 되면 나오는 페이지이다. <br>지하철역을 선택할 수 있는 메뉴와 현재 위치를 선택할 수 있는 메뉴가 있는데, 현재 위치를 선택할 수 있는 메뉴는 처음에 위치 정보 사용에 동의해야만 사용할 수 있다.
현재 위치 탭을 누르면 지도를 통해 현재 위치를 보여준다.

4. **결과 화면**<br>
현재 위치 혹은 자신이 설정한 지하철 위치에서 선택한 영화를 상영하는 영화관을 가까운 것부터 3~6개를 보여준다. <br>
아직은 완성본이 아니기에, 제대로 출력을 하지 못하고 있는데 추후에 수정을 하여 완성을 할 예정이다.

## 결과 화면

