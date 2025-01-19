<div align="left">
  
  # Doggle project (B2C, B2B)
</div>

### <div align="right"><b>Team Project</b></div>
<br><br>
## 프로젝트 개요
<div align="center"></div>
<b>Doggle</b>은 <b>반려견 주인들을 위한 종합 관리 플랫폼</b>으로, 반려견 양육의 모든 측면을 한 곳에서 간편하게 관리할 수 있는 서비스를 제공합니다.
반려견 인구의 증가와 함께 호텔 예약, 간식 추천, 건강 관리, 그리고 일상적인 케어 등 다양한 서비스에 대한 수요도 급증하고 있습니다.
하지만 현재 시장에 나와 있는 서비스들은 개별적인 기능에만 집중되어 있어, 반려견 주인들이 여러 플랫폼을 번갈아 가며 사용하는 불편함이 있었기에 <b>Doggle</b>은 이러한 문제를 해결하기 위해 <b>다양한 기능을 통합한 올인원 솔루션</b>을 제공합니다. 
<br><br>

## 통합 관리: <br>
<b>Doggle</b>은 반려견 호텔 예약, 맞춤형 간식 추천, 건강 관리 등을 하나의 플랫폼에서 모두 제공하는 <b>통합 시스템</b>입니다. <br>
이는 사용자가 여러 앱을 번갈아 가며 사용할 필요 없이, 하나의 앱으로 모든 서비스를 해결할 수 있어 경쟁 서비스와 차별화됩니다.
<br><br>

## 개인화된 서비스: <br>
<b>Doggle</b>은 반려견의 알러지, 체중, 건강 상태를 개별적으로 분석하여 <b>맞춤형 간식</b>과 <b>건강 관리 서비스</b>를 제공합니다. <br>
이는 반려견의 특성을 고려하지 않는 기존 서비스보다 더 <b>세밀하고 개인화된 경험을 제공</b>하는 것이 차별화된 점입니다.

<br><br><br><br>
# 팀원 소개
|팀원|담당|담당|깃허브|
|:---:|---|---|---|
|한기범(팀장)|FRONT|BACK|https://github.com/hgb926|
|이찬희|FRONT|BACK|https://github.com/chanhee7|
|김예진|FRONT|BACK|https://github.com/zinit95|
|주우빈|FRONT|BACK|https://github.com/binwoojoo|
|조경곤|FRONT|BACK|https://github.com/ckk914|
|김주성|FRONT|BACK|https://github.com/kkimjuseong|
|<b>임제훈</b>|FRONT|FRONT|https://github.com/jehoonje|

<br><br>
# 기술 스택 및 선정 이유
<div align="center">

### FRONT
<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Appliance</th>
      <th>Version</th>
      <th>선정 이유</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>React</td>
      <td>프론트엔드 라이브러리</td>
      <td>18.3.1</td>
      <td>컴포넌트 기반 UI 구축을 위해 사용했으며, 가독성과 유지보수성을 고려하여 선택했습니다.</td>
    </tr>
    <tr style="background-color: #f5f5f5;">
      <td>react-router-dom</td>
      <td>클라이언트 라우팅</td>
      <td>6.26.0</td>
      <td>SPA 환경에서 효율적인 페이지 전환과 라우팅 관리를 위해 사용했습니다.</td>
    </tr>
    <tr>
      <td>axios</td>
      <td>API 통신</td>
      <td>0.27.2</td>
      <td>비동기 HTTP 요청을 보다 간결하게 처리하고, 브라우저 호환성이 높아 선택했습니다.</td>
    </tr>
    <tr style="background-color: #f5f5f5;">
      <td>Redux</td>
      <td>전역 상태 관리</td>
      <td>5.0.1</td>
      <td>예측 가능한 데이터 플로우를 유지할 수 있고, 글로벌 상태 관리가 필요한 기능에 활용하기 위해 선택했습니다.</td>
    </tr>
    <tr>
      <td>Redux-actions</td>
      <td>액션 관리</td>
      <td>2.6.5</td>
      <td>createAction과 handleActions을 활용하여 Redux 액션을 간결하게 관리하기 위해 사용했습니다.</td>
    </tr>
    <tr style="background-color: #f5f5f5;">
      <td>Redux-thunk</td>
      <td>비동기 상태 관리 미들웨어</td>
      <td>2.4.1</td>
      <td>Redux 내에서 비동기 API 호출을 효율적으로 관리하기 위해 적용했습니다.</td>
    </tr>
    <tr>
      <td>SWR</td>
      <td>Data Fetching</td>
      <td>1.3.0</td>
      <td>Redux 기반 상태 관리 시 코드가 길어지고, 불필요한 GET 요청이 반복되는 문제를 개선하기 위해 SWR을 적용하여 캐싱 및 데이터 자동 갱신을 활용했습니다.</td>
    </tr>
    <tr style="background-color: #f5f5f5;">
      <td>Styled-components</td>
      <td>CSS-in-JS 스타일링</td>
      <td>6.1.12</td>
      <td>CSS를 컴포넌트 단위로 관리하여 유지보수성을 높이고, 동적 스타일링이 용이하여 선택했습니다.</td>
    </tr>
    <tr>
      <td>Sass</td>
      <td>CSS 전처리기</td>
      <td>1.77.6</td>
      <td>CSS의 가독성을 높이고, 변수 및 중첩 스타일링을 활용하여 개발 속도를 높이기 위해 사용했습니다.</td>
    </tr>
    <tr style="background-color: #f5f5f5;">
      <td>swiper</td>
      <td>슬라이더 라이브러리</td>
      <td>11.1.9</td>
      <td>다양한 커스텀 옵션을 제공하며, 부드러운 슬라이드 효과를 구현할 수 있어 선택했습니다.</td>
    </tr>
    <tr>
      <td>framer-motion</td>
      <td>애니메이션 라이브러리</td>
      <td>11.3.21</td>
      <td>React 기반으로 간결한 코드로 자연스러운 애니메이션을 구현할 수 있어 사용했습니다.</td>
    </tr>
    <tr style="background-color: #f5f5f5;">
      <td>mui/x-date-pickers</td>
      <td>날짜 선택 컴포넌트</td>
      <td>7.11.0</td>
      <td>캘린더 및 날짜 선택 기능이 필요했으며, Material UI와의 호환성이 좋아 선택했습니다.</td>
    </tr>
    <tr>
      <td>mui/material</td>
      <td>UI 라이브러리</td>
      <td>5.7.0</td>
      <td>디자인 시스템이 정돈되어 있으며, 다양한 UI 컴포넌트를 제공하여 개발 생산성을 높일 수 있어 사용했습니다.</td>
    </tr>
    <tr style="background-color: #f5f5f5;">
      <td>AWS EC2</td>
      <td>클라우드 서버 호스팅</td>
      <td>-</td>
      <td>확장성과 가용성이 뛰어나며, 직접 서버를 설정하고 최적화할 수 있어 선택했습니다.</td>
    </tr>
    <tr>
      <td>GitHub Actions</td>
      <td>CI/CD 자동화</td>
      <td>-</td>
      <td>코드 변경 사항에 대한 테스트 및 배포를 자동화하여 개발 효율성을 높이기 위해 사용했습니다.</td>
    </tr>
  </tbody>
</table>
</div>
<br><br><br>


  
## 개발 일정
<b>- 2024.07.01 ~ 2024.08.26</b>

  <br>
  <br>
  <br>
  



## 프로젝트 소개
  
### ✅ 로그인, 회원가입, 마이페이지

### 개인화된 서비스:
Doggle은 반려견의 알러지, 체중, 건강 상태를 개별적으로 분석할수 있도록 사용자의 강아지를 데이터를 추가설정이 가능합니다. <br>
이는 반려견의 특성을 고려하지 않는 기존 서비스보다 더 세밀하고 개인화된 경험을 제공하는 것이 차별화된 점입니다. <br>
또한 호텔 예약 및 간식 구독 조회가 가능하며, 예약일자가 지난 호텔 및 구독 후 간식의 리뷰 작성, 및 조회가 가능합니다. <br><br>

### ✅ 호텔 예약 시스템

### 편리한 호텔 검색 기능: 
Doggle은 지역 기반 검색, 리뷰, 가격 비교 등의 기능을 통해 사용자가 자신에게 맞는 반려견 호텔을 쉽게 선택할 수 있습니다. <br>
복잡한 절차 없이 빠르고 효율적인 호텔 검색과 예약이 가능하다는 점에서 차별화됩니다.<br><br>
  
### ✅ 간식 구독 시스템

### 지속적인 케어 시스템: 
사용자는 Doggle의 간식 구독 서비스를 통해 자동으로 맞춤형 간식을 정기 배송받을 수 있습니다. <br>
이는 매번 간식을 고민하고 선택해야 하는 번거로움을 없애주며, 반려견의 지속적인 건강 관리가 가능하다는 점에서 차별화된 가치를 제공합니다.<br><br>
  
### ✅ 커뮤니티 서비스

### 커뮤니티 활성화: 
Doggle은 반려견 주인들이 정보를 공유하고 소통할 수 있는 커뮤니티 기능을 제공합니다. <br>
이는 단순한 서비스 제공을 넘어 반려동물 양육과 관련된 지식과 경험을 교환할 수 있는 플랫폼으로 확장하여 차별화를 이루었습니다.<br><br><br><br><br>


<br><br>
# 아키텍쳐 (Architecture)
![doggle_architecture](https://github.com/user-attachments/assets/206e697c-282f-48e1-8ac4-c5ae51020ace) 

<br><br>

# 트러블 슈팅 (Trouble shooting)

(Chrome DevTools 및 Lighthouse 성능 측정 기반)

### 1. Drawer 리렌더링 최적화로 FPS 및 UI 반응 속도 개선<br>

문제: Drawer 토글 시 메인 화면 전체가 리렌더링되어 FPS 30, Reflow 증가, 모바일 UX 저하<br>
조치: Styled-Components에서 shouldForwardProp을 적용해 불필요한 DOM 속성을 제거하고,<br>transform 범위를 줄여 Drawer만 애니메이션 처리하였습니다.<br>
결과: FPS 42% 향상(30→50~60FPS, DevTools 측정), Reflow 60% 감소, UI 반응 속도 0.15초 내 개선 → 모바일 UX 개선 및 이탈률 감소<br>

### 2. Redux 캐싱 및 API 요청 최적화<br>

문제: 페이지 전환마다 동일한 API가 반복 호출되어 트래픽이 늘고, 로딩 속도가 느려졌습니다.<br>
조치: Redux에 호텔/객실 데이터를 캐싱하고, useEffect 의존성 배열을 최적화했습니다. <br>또한 staleTime을 설정해 필요할 때만 서버와 통신하도록 만들었습니다.<br>
결과: API 호출 40% 감소, 로딩 시간 1.8초 → 1.0초로 단축, UX가 눈에 띄게 향상되었습니다.<br>

### 3. 공통 컴포넌트 모듈화<br>

문제: Modal, Footer 등 중복된 UI가 페이지마다 반복 작성되어 유지보수가 번거롭고, 수정 시 버그 위험이 컸습니다.<br>
조치: HotelModal, Footer 등을 공통 컴포넌트로 분리, 한 곳에서만 관리하도록 했습니다.<br>
결과: 중복 코드 20% 감소, 유지보수 시간 50% 단축, 빌드 속도도 소폭 개선되었습니다.<br>


<br><br>

## 📽 시연 영상

<div align="center">
<br>
  
[영상 링크](https://youtu.be/Ey6PqKtpbk4?feature=shared) 
</div>
<br><br><br><br><br><br>
