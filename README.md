# project_Pocketmon

## 프로젝트 포켓몬

아주 간단한 웹 공부 사이트 제작
가져가기를 누르면 랜덤한 포켓몬 사진을 띄워 준다

nodejs-express를 사용해 정적화면을 띄우고, Ngrok 터널링 기술을 통해 서버를 배포하였다. 다만 이는 로컬서버가동 문제로 AWS로 새로 배포할 예정이다.

### 사용 tool 
* [Node.js](https://nodejs.org/en/docs/)
* [Ngrok](https://ngrok.com/docs)
* [AWS / elasticbeans](https://docs.aws.amazon.com/ec2/index.html?nc2=h_ql_doc_ec2)

---
<img width="566" alt="image" src="https://user-images.githubusercontent.com/96401839/216385396-9af7c201-c3c7-4a62-901a-c86a0a470349.png">
가져가기를 누른다면?????

<img width="372" alt="image" src="https://user-images.githubusercontent.com/96401839/216385449-4ba03137-7ec9-4a0b-a6c1-6f6e097704dd.png">
짜잔~~ 당신의 포켓몬입니다~~~

---
### 개선사항 Have To
1. 다시 뽑기 버튼 추가
2. AWS 웹 서비스 띄우기
3. 포켓몬 사진 더 추가
4. 방문자수 카운트 추가
5. GET, POST 구조 변경하기
6. 방명록 추가하기 DB 구조로
7. 사진에 대응하는 이름 출력하기

### Vesrsion 
v.1.0.0 : 가장 기초적인 내용만 구현했다. 메인 file은 app.js

### Git convention
1. 모든 배포는 main에서 진행한다. main branch는 건드리지 않도록
2. 기능을 추가하기 위한 작업은 develop에서 진행된다. 
3. 목표로 한 기능이 구현되고 정상적으로 작동한다면 main에 PR-Merge을 진행한다.


---
#### Source & Reference
[포켓몬 사진들](https://pokemonkorea.co.kr/pokedex)
