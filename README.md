# 앱 문서

플레이 스토어에 올린 앱들의 **개인정보처리방침과 지원 안내**를 두는 곳이다.

앱 소스 저장소는 비공개로 두더라도 이 주소들은 항상 열려 있어야 한다 —
스토어 등록정보에 넣는 링크이고, 사용자가 언제든 열어 볼 수 있어야 하기 때문이다.
그래서 이 저장소만 공개로 둔다.

## 주소

GitHub Pages로 서비스한다 (`main` 브랜치 루트).

| 문서 | 주소 |
|---|---|
| 앱 목록 | https://yongminlee2.github.io/legal/ |
| 왁뿌볼 ASMR | https://yongminlee2.github.io/legal/waxball/ |
| — 개인정보처리방침 | https://yongminlee2.github.io/legal/waxball/privacy.html |
| — 지원 안내 | https://yongminlee2.github.io/legal/waxball/support.html |
| 삐약푸쉬 / Peep Push | https://yongminlee2.github.io/legal/peeppush/ |
| — 개인정보처리방침 | https://yongminlee2.github.io/legal/peeppush/privacy.html |
| — 지원 안내 | https://yongminlee2.github.io/legal/peeppush/support.html |

## 구조

```
index.html          앱 목록
style.css           공용 스타일 (밝은/어두운 화면 모두 대응)
waxball/
  index.html        앱 소개 — 스토어의 "웹사이트" 칸에 넣는 주소
  privacy.html      개인정보처리방침 (한국어·영어)
  support.html      지원 안내와 자주 묻는 것 (한국어·영어)
peeppush/
  index.html
  privacy.html
  support.html
  store-listing.md  플레이 콘솔에 그대로 붙여 넣을 등록정보 (스토어에 안 뜸)
```

## 앱을 추가할 때

1. 앱 이름으로 폴더를 만들고 `waxball/` 의 세 파일을 복사해 내용을 고친다
2. `index.html` 의 카드 목록에 한 줄 추가한다
3. 스타일은 `../style.css` 를 그대로 참조한다

## 고칠 때 주의

개인정보처리방침은 **앱이 실제로 하는 일과 맞아야 한다.** 앱에 광고나 결제,
분석 도구를 넣으면 방침 내용도 같이 고쳐야 하고, 플레이 콘솔의
"광고 포함 여부"와 "데이터 보안" 신고도 다시 해야 한다.
고친 날짜(최종 수정일)도 함께 갱신한다.
