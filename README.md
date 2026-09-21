# 📱 제작진 모바일 전표처리 가이드

제작진이 촬영 현장이나 이동 중 스마트폰으로 영수증 증빙 기준과 전표 작성법을 빠르게 확인할 수 있는 모바일 최적화 웹 매뉴얼입니다.

- 🌐 **모바일 배포 URL**: [https://pap5608.github.io/jejakbillmanual/](https://pap5608.github.io/jejakbillmanual/)
- 📦 **GitHub 저장소**: [https://github.com/pap5608/jejakbillmanual](https://github.com/pap5608/jejakbillmanual)

---

## 🚀 GitHub Pages 배포 설정 확인 (최초 1회)

본 저장소에는 GitHub Actions 자동 배포 워크플로우(`.github/workflows/deploy.yml`)가 포함되어 있습니다.

만약 `https://pap5608.github.io/jejakbillmanual/` 접속 시 404가 뜨는 경우 아래 설정을 1회 확인해 주세요:
1. 저장소 상단 **Settings** (⚙️) ➔ 좌측 사이드바 **Pages** 클릭.
2. **Build and deployment** > **Source** 항목에서:
   - **`GitHub Actions`** 를 선택 (권장, 푸시할 때마다 자동 배포됨)
   - 또는 **`Deploy from a branch`** 선택 후 Branch를 **`main` / `/(root)`** 로 지정 후 Save.

---

## 📲 스마트폰 홈 화면에 바로가기 앱 추가 방법
제작진 단톡방이나 슬랙에 URL(`https://pap5608.github.io/jejakbillmanual/`)을 공유한 후:
- **아이폰(iOS Safari):** 하단 중앙 공유 버튼(네모+화살표) ➔ **[홈 화면에 추가]**
- **갤럭시(Android Chrome):** 우측 상단 메뉴(`⋮`) ➔ **[홈 화면에 추가]** 또는 **[앱 설치]**

---

## 🛠️ 실무 규정 수정 안내
`index.html`을 수정하여 커밋 및 푸시하면 즉시 사이트에 반영됩니다:
- **식대/음료 한도:** `1인 1식 12,000원 이하`
- **야근 인정 기준 시간:** `20:00 이후` / `23:00 이후 심야 택시`
- **정산 마감일:** `매월 25일 18:00`
- **증빙 서류 규정:** 간이영수증 건당 3만원 이하, 현금영수증 지출증빙용 필수
