김버그의 html css는 재밌다 강의를 듣고  
마지막 final project 챕터를 수강하기전에 미리 혼자 만들어봤다  
program section의 그림자 빼고는 전부 똑같이 만드는데 성공했다  
강의에서는 부트스트랩의 그리드 시스템을 이용하는데 예제 규모가 작기도 하고  
괜히 이런저런 제약이 생겨서 나는 그냥 만들었다

<br>

처음에는 각 섹션마다 높이값을 정해놓고 플렉스방향 컬럼에 주축센터해서 세로가운데 정렬했는데  
나중에는 높이값이 따로 없는 상태에서 위아래 패딩을 주는 식으로 바꿨다  
근데 첫landing섹션은 모바일에서 화면전체를 채워야하기 때문에  
여기만 높이값을 따로 줬다 그렇지 않으면 내용이 적어서 세로로 너무 짧아진다

<br>

깨달은거  
1. 갭은 플렉스에서만 먹는다  
2. 갭으로 폭을 지정하면 스페이스비트윈 이런거 안먹고 고정값이 유지된다  
그래서 모바일 화면에서 갭썼으면 pc에서도 갭으로 조절해야한다  
3. nth-child 보다 더욱 우리 상식에 들어맞는? 유용한 nth-of-type  