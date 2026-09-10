# 택배운송장 템플릿 (Shipping Label Template)

**ActiveReportsJS Designer**로 제작된 택배운송장(Shipping Label) 샘플 보고서 템플릿입니다.
`.rdlx-json` 형식으로 제공되며, 택배 운송 시 필요한 정보(받는 사람 정보, 보내는 사람 정보, 상품 내역 등)를 담고 있는 양식의 형태로 설계되었습니다.

> 택배운송장은 택배를 보낼 때마다 데이터만 변경되는 일관된 레이아웃을 가진 양식입니다.
---

## 📌 주요 특징

- **고정 페이지 레이아웃**으로 일관된 레이아웃 설계
- **바코드** 컨트롤을 활용해 보고서 본문에 바코드 삽입
-  **Substring 함수**와 **Replace 함수**를 활용해 개인정보 일부분은 비공개로 처리

---

## 🗂️ 포함된 진단서 항목

| 구분 | 항목 |
|---|---|
| 운송장 정보 | 운송장번호, 지역, 배송코 |
| 받는 사 정보 | 이름, 전화번호, 주소 |
| 보내는 사람 정보 | 이름, 전화번호, 주 |
| 상품 정보 | 상품 내역 |

---

## 📄 보고서 구성 특징

| 구성 요소 | 설명 |
|---|---|
| 페이지 사이즈 설정 | 페이지의 치수 속성으로 원하는 크기로 조정 |
| 바코드 컨트롤 삽입 | 원하는 위치에 바코드 컨트롤 삽입 가능 |
| 개인정보 비공개 처리 | 표현식을 활용하여 개인정보 일부분을 비공개로 표시되도록 처리 |

---

## 🚀 사용 방법

ActiveReportsJS Viewer를 이용하여 아래와 같이 보고서를 불러올 수 있습니다.

```javascript
viewer.open("택배운송장.rdlx-json");
viewer.zoom = "FitPage";
```

`zoom` 속성을 활용하면 Viewer에서 렌더링되는 보고서의 확대 정도를 설정할 수 있습니다.
템플릿은 **ActiveReportsJS Designer**에서 열어 자유롭게 커스터마이징(항목 추가/수정, 레이아웃 변경, 데이터 소스 연결 등)하실 수 있습니다.

---

## 🛠️ 사용 기술

- [ActiveReportsJS](https://www.grapecity.com/activereportsjs) Designer
- `.rdlx-json` 리포트 포맷
- 바코드 컨트롤(Barcode Control)
- 표현식(Substring, Replace 함수), PDF 내보내기(PDF Export)

---

## 📝 라이선스

본 템플릿은 학습 및 참고 목적의 샘플로 자유롭게 사용 및 커스터마이징이 가능합니다.

---

## 🔖 Keywords / Tags

`ActiveReportsJS` `RDL` `rdlx-json` `Report Designer` `Reporting Tool` `보고서 템플릿` `택배운송장` `Shipping label` `택배송장` `Shipping Report` `PDF Export` `JavaScript Reporting` `Web Reporting`
