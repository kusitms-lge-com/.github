# KUSITMS x LGE

> 본 프로젝트는 LG 전자의 홈페이지 개선을 위해 LG 전자와 큐시즘이 협력하여 진행한 기업 프로젝트입니다.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f66fd594-9992-4f04-9939-77f90394b36e" />



## 🧐 문제 인식

가전은 가격이 높고, 설치 조건과 공간 제약이 있으며, 가족 구성이나 생활 방식까지 함께 고려해야 하는 **고관여 구매**입니다.
현재 LG닷컴은 이미 살 제품이 정해진 사용자에게는 잘 작동하지만, 아직 무엇을 살지 정하지 못한 사용자에게는 탐색을 시작하는 것부터 어렵습니다.
오프라인 매장에서는 자연스럽게 둘러보고 질문하며 판단을 이어갈 수 있지만, 온라인에서는 사용자가 혼자 기준을 세우고 제품을 비교해야 하기 때문에 탐색 흐름이 쉽게 끊깁니다.

저희는 LG닷컴의 핵심 문제가 **정보의 양이 아니라, 탐색과 판단 흐름의 단절**에 있다고 보았습니다.
사용자가 관심을 갖고 탐색을 시작한 뒤, 후보를 좁히고 확신을 만드는 흐름이 하나의 여정으로 자연스럽게 연결될 수 있도록 경험 구조 전체를 다시 설계하는 것을 목표로 삼았습니다.


## 💡 솔루션

**[1] 홈 화면 - 관심 단계**
> "부담 없이 탐색을 시작하세요"
- 라이프스타일 기반 콘텐츠로 구매 의도가 없는 사용자도 가볍게 진입할 수 있습니다.
- 베스트 제품과 카테고리 필터를 통해 자연스럽게 제품 탐색으로 이어집니다.

**[2] 쇼핑 페이지 - 탐색 단계**
> "내 생활 맥락에 맞게 탐색하세요"
- 거주 형태, 평수, 가구 구성 등 생활 맥락 기반의 탐색 구조를 제공합니다.
- 제품 스펙 중심이 아닌, 사용자의 상황에 맞는 기준으로 탐색을 시작할 수 있습니다.

**[3] 냉장고 리스트 - 후보 압축 단계**
> "원하는 제품을 빠르게 좁혀가세요"
- 필터와 정렬 기능을 통해 후보 제품을 빠르게 2~3개로 압축할 수 있습니다.
- 핵심 스펙을 한눈에 확인하여 탐색만 길어지는 경험을 줄였습니다.

**[4] 제품 비교 - 확신 단계**
> "차이가 내 생활에 어떤 의미인지 확인하세요"
- 단순 스펙 나열이 아닌, 레이더 차트와 바 차트로 제품 간 핵심 차이를 시각화합니다.
- 항목별 비교를 통해 마지막 확신을 만들 수 있도록 설계했습니다.



---

## 🛠️ System Architecture

<img width="1200" alt="image" src="https://github.com/user-attachments/assets/c749000f-b285-4cc2-90df-360dc1460f13" />


---

## 🌟 Preview

<table>
  <tr>
    <th>Home</th>
    <th>Shopping</th>
  </tr>
  <tr>
    <td>
      <a href="https://kusitms-lge-fe.vercel.app/home">
        <img width="500" alt="image" src="https://github.com/user-attachments/assets/05f80cbf-3316-45ef-9833-eaf573b21fcf" />
      </a>
    </td>
    <td>
      <a href="https://kusitms-lge-fe.vercel.app/category/refrigerators">
        <img width="500" alt="image" src="https://github.com/user-attachments/assets/cd681193-6740-4e50-8d3a-6dd40e3bac3e" />
      </a>
    </td>
  </tr>
  <tr>
    <th>Refrigerator List</th>
    <th>Compare Products</th>
  </tr>
  <tr>
    <td>
      <a href="https://kusitms-lge-fe.vercel.app/category/refrigerators/list">
        <img width="500" alt="image" src="https://github.com/user-attachments/assets/b183c3fe-b417-4db7-b32a-b2518c68e7a5" />

      </a>
    </td>
    <td>
      <a href="https://kusitms-lge-fe.vercel.app/compare">
        <img width="500" alt="image" src="https://github.com/user-attachments/assets/ecf6ffe4-9d10-41bb-a60d-9c77ba229276" />
      </a>
    </td>
  </tr>
</table>

---

## 🌃 FE Developer

| <img src="https://avatars.githubusercontent.com/u/105573067?v=4" width="150" height="150"/> | <img src="https://avatars.githubusercontent.com/u/165117972?v=4" width="150" height="150"/> |
|:---:|:---:|
| 김선화<br/>[@sunhwaaRj](https://github.com/sunhwaaRj) | 성태경<br/>[@sungtaegyeong](https://github.com/sungtaegyeong) |
| <small>• 홈 화면 구현<br/>• 비교하기 그래프/차트 구현<br/>• 냉장고 리스트 페이지 구현</small> | <small>• 쇼핑하기 페이지 구현<br/>• 제품 비교 페이지 구현<br/>• 배포 및 CI/CD 설정</small> |
