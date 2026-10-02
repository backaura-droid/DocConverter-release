# DocConverter

한글(HWP·HWPX)·PDF·워드(DOCX)·엑셀(XLSX) 문서를 Markdown으로 바꾸는 Windows 앱입니다. 신구대조표 만들기, 양식 칸 채우기, Markdown을 공문서 HWPX로 만들기도 할 수 있습니다.

## 내려받기

**[최신 설치파일 받기 → Releases](https://github.com/backaura-droid/DocConverter-release/releases/latest)**

`DocConverter-Setup-<버전>.exe`를 내려받아 실행합니다.

- Windows 10·11 64비트에서 동작합니다. 다른 프로그램을 따로 설치할 필요가 없고, 관리자 권한도 필요 없습니다.
- 처음 실행할 때 "Windows의 PC 보호" 창이 뜨면 **추가 정보 → 실행**을 누릅니다. 코드 서명을 하지 않은 앱이라 나오는 경고입니다.

## 주요 기능

| 기능 | 하는 일 |
|---|---|
| 문서 변환 | 문서를 Markdown(.md)으로 바꿉니다. 폴더를 넣으면 하위 폴더까지 찾아 각 문서 옆에 .md를 만듭니다. 스캔 PDF는 OCR로 읽습니다. |
| 신구대조 | 현행 문서와 개정 문서의 바뀐 부분만 대조표로 만듭니다. |
| 양식 추출 | 양식 문서의 빈칸·누름틀 목록을 뽑습니다. |
| 양식 채우기 | 양식 칸에 값을 넣어 서식을 그대로 살린 HWPX를 만듭니다. |
| HWPX 생성 | Markdown 문서를 공문서 서식의 HWPX로 만듭니다. |

탐색기에서 파일이나 폴더를 창 위로 끌어다 놓으면 바로 들어갑니다. 왼쪽 메뉴에 마우스를 올리면 기능 설명이 보입니다.

## 변환 엔진 업데이트

변환은 [kordoc](https://github.com/chrisryugj/kordoc) 엔진이 합니다. 앱을 켤 때마다 엔진 새 버전을 확인하고, 새 버전이 있으면 왼쪽 아래에 **엔진 업데이트** 버튼이 나타납니다. 앱을 다시 설치하지 않아도 엔진만 바뀝니다.

인터넷이 필요한 경우는 두 가지입니다. 엔진을 업데이트할 때와, OCR을 처음 쓸 때 인식 모델(약 18MB)을 한 번 내려받을 때입니다. 일반 변환은 인터넷 없이 됩니다.

## 문의

오류나 개선 요청은 [Issues](https://github.com/backaura-droid/DocConverter-release/issues)에 남겨 주세요.

## 포함된 구성 요소의 라이선스

- 변환 엔진 kordoc: MIT
- 서체 SUIT: SIL Open Font License 1.1
- 엔진 업데이트에 쓰는 npm: Artistic-2.0
- Microsoft Visual C++ 런타임: Microsoft 재배포 허용 파일
- 앱 셸 Electron: MIT

© Backaura
