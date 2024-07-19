<img width=100% src="https://github.com/user-attachments/assets/30c90110-9818-45f7-8f89-8a7a26b17bbc">

# GYM KIOSK🔥

### 📖 프로젝트 개요
헬스장에서 사용 할 수 있는 실용적인 키오스크를 만드는 것을 목표로 진행<br/>
<br/><br/>

### 🚀 프로젝트 목표
- HTML, CSS, JavaScript를 활용하여 프론트엔드 기본적인 활용
- 사용자의 편의성을 위한 UI 설계 및 구현
<br/><br/><br/>

## 📝 프로젝트 설명

### 💼 GYM KIOSK의 기능
1. 사용자가 헬스장에서 가장 많이 구매하는 세 가지 상품을 대상으로 간편하게 구매할 수 있는 키오스크 구현
2. 상품의 수량을 자유롭게 조절 가능
<br/><br/><br/>




### 💻 기술 스택
- **FrameWork:** &nbsp;&nbsp;![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
- **Style:** &nbsp;&nbsp;![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
- **Language:** &nbsp;&nbsp;![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
- **Tools:** &nbsp;&nbsp;![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
<br/><br/>

### 🛠️ 기능에 대한 사용 기술
- Flask 서버와 React 클라이언트를 사용하여 구현
- Gemini API를 사용하여 LLM모델 선택 후 LangChain 기술을 사용하여 체인으로 연결된 응답 생성과정 구현
- Pandas를 통해 관광정보 API의 csv파일을 전처리
- RAG기술을 통해 전처리된 데이터를 학습시켜 정확한 답변 생성
- 답변을 서버에서 클라이언트로 전달하여 여행지 추천 화면 구현
- 답변 데이터의  위도,경도값을 통해 클라이언트에서 KakaoMap API를 통한 위치정보 구현
- MySQL 를 사용하였고 외래키를 통한 연결테이블 구현
- 회원 기능과 여행지 스크랩 기능을 DB를 통해 구현
- 자연스러운 UI 구현 및 다크모드 구현<br/><br/><br/>


### ✨ 주요 기능 및 이미지

#### 📌 메인 페이지<br/>
<img width=100% src="https://github.com/user-attachments/assets/76f130f2-6861-4a88-8a10-e32f7417cb0f"><br/><br/>
- **상품 주문:** 상품을 클릭하면 주문내역에 상품이 추가<br/>
- **주량 조절:** 상품 이미지를 클릭하거나 주문내역에서 상품명 옆의 +, -버튼을 누르면 수량 조절 가능
- **전체삭제:** 결제하기 옆의 버튼을 클릭하면 주문내역 내의 상품이 모두 삭제
- **총 가격:** 주문내역에 있는 상품 가격의 합이 총 가격에 출력  <br/><br/><br/>



### 🛠 문제 해결 과정
⚠️ 데이터베이스 설계<br/>
<table>
  <tr>
    <td>
    <strong>문제</strong>
    </td>
    <td>
    <strong>주문하기 버튼을 눌러도 DB가 없기에 저장이 되지 않음</strong>  
    </td>
  </tr>
  <tr>
    <td>원인</td>
    <td>과거 php를 사용하여 DB를 구축하려했으나 숙련도가 낮아 어려움이 있었음</td>
  </tr>
  <tr>
    <td>해결</td>
    <td>프로젝트를 진행하며 얻은 지식과 숙련도를 활용하여 node.js를 이용해서 서버를 구축하고 DB를 연동할 계획</td>
  </tr>
</table><br/><br/>


