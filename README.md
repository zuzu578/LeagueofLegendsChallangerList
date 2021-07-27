# LeagueofLegendsChallangerList
리그오브레전드 챌린저 리스트 
<img width="1130" alt="스크린샷 2021-07-28 오전 12 08 51" src="https://user-images.githubusercontent.com/69393030/127179184-94eae6a4-52a0-4ca2-b4a5-3508686f11f8.png">

# 설명
<img width="1026" alt="스크린샷 2021-07-27 오후 11 58 47" src="https://user-images.githubusercontent.com/69393030/127177486-20993bf6-bad6-40a3-aeff-154af5252206.png">
해당 api 는 챌린저 랭크 티어의 유저 리스트를 가져옵니다.

# dto 
<img width="1026" alt="스크린샷 2021-07-27 오후 11 59 27" src="https://user-images.githubusercontent.com/69393030/127177598-1683b686-ffe7-41d3-a0f9-bfeb84e587e3.png">
freshBlood	boolean	 
wins	int	Winning team on Summoners Rift. => 승
summonerName	string	=> 소환사 이름
miniSeries	MiniSeriesDTO	
inactive	boolean	
veteran	boolean	 => 해당 소환사가 pro 인지 일반유저인지 
hotStreak	boolean	
rank	string	 => 랭크 
leaguePoints	int	 => LP 
losses	int	Losing team on Summoners Rift. => 패 
summonerId	string	Player's encrypted summonerId.
# 요청변수(Parameter)
<img width="688" alt="스크린샷 2021-07-28 오전 12 01 22" src="https://user-images.githubusercontent.com/69393030/127177935-b638f247-0da0-4fb9-b05c-bd8f6cb60f7a.png">
Que Type (게임타입) 에따른 챌린저 리스트를 return 해줍니다.
# Que Type
 -5X5 : 5대5 랭크게임 
 =flex : 자유랭크게임 
# response
 <img width="829" alt="스크린샷 2021-07-28 오전 12 02 24" src="https://user-images.githubusercontent.com/69393030/127178141-59760054-0e30-4ed5-ad2a-827ced47e39c.png">
# response Body 
<img width="829" alt="스크린샷 2021-07-28 오전 12 02 44" src="https://user-images.githubusercontent.com/69393030/127178204-df6b60b4-b4cc-4d87-ac2d-e3ef6ab5249d.png">
# <back-end-transaction>
<img width="1130" alt="스크린샷 2021-07-28 오전 12 03 07" src="https://user-images.githubusercontent.com/69393030/127178282-b616ff6f-f552-4961-a404-aeccfddc2673.png">
# <front-end-transaction>
  <img width="1130" alt="스크린샷 2021-07-28 오전 12 03 49" src="https://user-images.githubusercontent.com/69393030/127178374-04694e07-cf23-4edc-9119-2286f449e3a4.png">

# features
  페이징기능 

