# vworld 주소변환
vworld api를 이용하여 구주소 혹은 새주소를 검색하여 GPS좌표, 구주소, 새주소, 우편번호를 정리해 줍니다.


### 어떨 때 쓰는가?
구주소 -> 새주소 변환 + GPS, 우편번호
새주소 -> 구주소 변환 + GPS, 우편번호
GPS좌표 -> 구주소+새주소+GPS, 우편번호 

구주소와 새주소가 섞인 엑셀파일이 있었습니다. 구주소로 정렬해야 했습니다. 그리고 새주소라도 시군구를 빼먹고 쓴 것도 있고 해서 정해진 포맷으로 정리할 필요가 있었습니다.

그리고 어짜피 주소변환하는 김에 좌표 및 우편번호도 같이 정리해줍니다.

그외 GIS자료 정리를 위해 좌표로 된 것을 역으로 주소로 만들어주기 합니다.


### 왜 만들었는가
그냥 쉽게 살고 싶었습니다. 이미 만들어진게 있더군요. 그런데 돈을 내라고 하더라고요. 돈이 없었습니다. 


### 어떻게 사용하는가?
GPS좌표불러오기7.exe와 불러올예시파일을 다운 받습니다.

불러올예시파일에 주소(혹은 GPS정보)를 넣어둡니다.

GPS좌표불러오기를 더블클릭+파일찾기 하시거나, 불러올예시파일을 마우스로 끌어 프로그램 위에 놓으면 됩니다.



### 어떻게 작동하는가
Vworld API 사용법이 있습니다.
https://www.vworld.kr/dev/v4dv_geocoderguide2_s001.do
엑셀에서 주소를 받아, 서버에 올려, 반환값을 엑셀에 저장합니다. 참 쉽죠? 저는 한게 별로 없어요. 주석이 많아 그렇지 실제로 코드는 100줄이면 될거에요.

다만... vworld가 1년에 한번 키갱신을 해야 합니다. 그런데 그때마다 새로 컴파일하기 귀찮아서 드롭박스에 키를 저장해 두고 그 키를 불러옵니다. 나중에 키를 갱신하면 드롭박스의 파일만 수정하면 됩니다. 

### 당부의 말씀
하루 3000건인가 제한이 있습니다. 실행파일을 너무 많이 사용하시면 제가 곤란해집니다. 직접 키를 받으셔서 사용해주세요






