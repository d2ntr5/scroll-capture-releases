# 개인정보처리방침 · Privacy Policy

**스크롤 캡처 (Scroll Capture)** 크롬 확장 · 시행일 2026-11-16 (Effective 2026-11-16) · 게시자 d2ntr5

[English below](#english)

## 한국어

### 요약
- 이 확장은 사용자가 고른 웹페이지를 스크롤하며 찍어 사용자 컴퓨터에 PNG · PDF 로 저장합니다.
- **어떤 정보도 기기 밖으로 보내지 않습니다.** 네트워크 요청을 하지 않으며, 개발자는 서버를 운영하지 않고 어떤 정보도 개발자에게 오지 않습니다.
- 판매 · 광고 · 분석 도구가 없습니다. AI 기능이 없습니다.
- **개인 보관용입니다.** 캡처한 이미지 · PDF를 다른 사람에게 배포하거나 공개하려면 저작권자 허락과 각 사이트 이용약관을 확인해 주세요. 이 확장은 캡처를 외부로 보내지 않습니다.

### 다루는 정보와 두는 곳

| 정보 | 어디에 두나 | 언제 지워지나 | 어디로 보내나 |
|---|---|---|---|
| 캡처한 페이지 화면 (사용자가 캡처를 시작한 탭만) | 확장 안의 브라우저 저장소(IndexedDB). **마지막 캡처 한 번만** 보관 | 새로 캡처하거나 확인 화면에서 「버리기」 할 때, 확장을 지울 때 | 보내지 않음 |
| 사용자가 저장한 PNG · PDF | 사용자 컴퓨터의 다운로드 폴더 (설정한 하위 폴더) | 사용자가 직접 지움 | 보내지 않음 |
| 탭 제목 · 주소 | 팝업의 탭 목록에 보여 줄 때 메모리. 캡처한 탭의 제목 · 주소는 위 캡처 기록과 진행 상황(`chrome.storage.session`, 브라우저를 닫으면 지워짐)에. 탭 제목은 파일 이름에 쓰임 | 위와 같음 | 보내지 않음 |
| 설정 · 사이트별 숨김 규칙(사이트 주소 범위와 요소 선택자) · 파일명 프로파일 · 자르기 프로파일 | 브라우저 로컬 저장소 (`chrome.storage.local`, **동기화 안 됨**) | 사용자가 설정에서 지우거나 확장을 지울 때 | 보내지 않음 |
| 클립보드 | 사용자가 확인 화면에서 「복사」를 누를 때만 그 이미지를 넣음 | 운영체제 클립보드 규칙대로 | 보내지 않음 |

- 숨김 규칙을 적용하려고 열린 페이지의 주소를 그 페이지 안에서 규칙 범위와 비교합니다. 이 비교 결과는 저장하지 않습니다.
- 숨길 요소를 클릭해 고를 때는 그 요소의 선택자(태그 · id · class)만 규칙으로 저장합니다.
- 페이지 안의 글 · 입력값 · 쿠키 · 비밀번호는 읽거나 저장하지 않습니다. 캡처는 화면에 그려진 모습(이미지)만 찍습니다.

### 제3자
- 정보를 누구에게도 팔거나 넘기지 않습니다. 이 확장은 외부 서비스와 통신하지 않습니다.

### 지우기
- 확인 화면 「버리기」: 캡처 기록을 지웁니다.
- 설정 화면에서 숨김 규칙을, 파일명 만들기에서 파일명 프로파일을, 확인 화면의 좌우 자르기에서 자르기 프로파일을 지웁니다.
- 확장을 지우면 확장 안에 저장된 캡처 · 설정 · 규칙이 모두 지워집니다. 다운로드 폴더에 저장한 파일은 사용자가 직접 지웁니다.

### 저작권 · 이용약관
- 개인 보관용입니다. 캡처한 이미지 · PDF를 다른 사람에게 배포하거나 공개하려면 저작권자 허락과 각 사이트 이용약관을 확인해 주세요. 이 확장은 캡처를 외부로 보내지 않습니다.

### 크롬 웹 스토어 사용자 데이터 정책 (Limited Use)
- Google API 에서 받은 정보의 사용은 Limited Use 요건을 포함한 크롬 웹 스토어 사용자 데이터 정책을 따릅니다.

### 문의
- 크롬 웹 스토어 등록정보의 개발자 연락처.
- 이 방침이 바뀌면 이 문서를 고치고 시행일을 바꿉니다.

<a id="english"></a>

## English

### Summary
- This extension scrolls through web pages you choose, captures them, and saves PNG or PDF files on your computer.
- **No information ever leaves your device.** The extension makes no network requests. The developer runs no server, and no information is sent to the developer.
- No sales, no ads, no analytics. No AI features.
- **For personal archiving only.** To distribute or publish captured images or PDFs, obtain permission from the copyright holder and check each site's terms of use. This extension never sends captures anywhere.

### What is handled and where it is kept

| Information | Where it is kept | When it is deleted | Where it is sent |
|---|---|---|---|
| Captured page images (only tabs you start a capture on) | Browser storage inside the extension (IndexedDB). **Only the most recent capture** is kept | On a new capture, when you press "Discard" on the review page, or when the extension is removed | Not sent |
| PNG / PDF files you save | Your computer's Downloads folder (the subfolder you set) | You delete them yourself | Not sent |
| Tab titles and URLs | In memory to show the tab list in the popup. Titles and URLs of captured tabs are kept with the capture record above and in progress state (`chrome.storage.session`, cleared when the browser closes). Tab titles are used in file names | Same as above | Not sent |
| Settings, per-site hiding rules (site URL scopes and element selectors), file-name profiles, crop profiles | Local browser storage (`chrome.storage.local`, **not synced**) | When you delete them in the options page or remove the extension | Not sent |
| Clipboard | An image is placed there only when you press "Copy" on the review page | Per your operating system's clipboard | Not sent |

- To apply hiding rules, the address of an open page is compared with the rule scopes inside that page. The result of this comparison is not stored.
- When you click to pick an element to hide, only that element's selector (tag, id, class) is saved as a rule.
- The extension does not read or store page text, form input, cookies, or passwords. A capture records only how the page is drawn on screen (an image).

### Third parties
- Information is not sold or transferred to anyone. The extension does not communicate with any external service.

### Deleting data
- "Discard" on the review page deletes the capture record.
- Delete hiding rules in the options page, file-name profiles in the file-name builder, and crop profiles in the review page's crop mode.
- Removing the extension deletes all captures, settings, and rules stored inside it. Files saved to your Downloads folder are deleted by you.

### Copyright and terms of use
- For personal archiving only. To distribute or publish captured images or PDFs, obtain permission from the copyright holder and check each site's terms of use. This extension never sends captures anywhere.

### Chrome Web Store User Data Policy (Limited Use)
- The use of information received from Google APIs will adhere to the Chrome Web Store User Data Policy, including the Limited Use requirements.

### Contact
- The developer contact on the Chrome Web Store listing.
- If this policy changes, this document is updated along with its effective date.
