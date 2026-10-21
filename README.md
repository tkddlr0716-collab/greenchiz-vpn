# 그린치즈 VPN · GREENCHIZ VPN

**글클메 시작 전, 연결부터 준비하세요.**

글로벌 메이플스토리 클래식 월드 출시를 준비하는 한국 Windows 이용자를 위한 무료 VPN 테스트 서비스입니다. 서비스 운영자가 제공하는 공개 안내입니다.

[출시 준비 가이드](https://greenchiz.com/maplestory-classic?utm_source=github&utm_medium=readme&utm_campaign=classic_launch_20261022) · [무료 회원가입](https://greenchiz.com/member/signup) · [Windows 다운로드](https://greenchiz.com/download) · [고객지원](https://greenchiz.com/bugs)

![글클메 출시 준비 · 그린치즈 VPN](images/greenchiz-classic-launch-20261022.png)

## 출시 시간

넥슨 공식 FAQ의 정식 오픈 시각은 **2026년 10월 21일 11:00 AM PDT**, 한국 시간으로 **10월 22일 목요일 오전 3시(KST)**입니다. 실제 오픈과 변경 여부는 [넥슨 공식 FAQ](https://www.nexon.com/maplestory/news/general/45385)를 확인하세요. 2026-10-20 확인.

## 시작 순서

1. [사이트 회원가입](https://greenchiz.com/member/signup)에서 이메일 인증과 비밀번호 설정을 마치세요.
2. [NEXT 0.8.9 시험판 ZIP](https://greenchiz.com/download) 전체를 짧은 경로에 풀고 GreenchizNext.exe를 실행하세요.
3. 넥슨 런처를 설치하고 한 번 실행한 뒤 완전히 종료하세요.
4. 그린치즈 계정으로 로그인하고 **라이브러리 앱 클릭 → 내 앱에 추가(사용 OFF) → 사용할 앱 ON → 통합 VPN 켜기** 순서로 진행하세요. 넥슨·메이플 전용 연결은 앱의 별도 안내를 따르세요.

넥슨 게임 계정과 그린치즈 계정은 별도입니다. 넥슨 비밀번호를 그린치즈에 입력하지 마세요.

## 지원 범위

| 항목 | 현재 상태 |
| --- | --- |
| 이용 요금 | 무료 테스트 운영 |
| 운영체제 | Windows |
| 현재 기본 다운로드 | NEXT 0.8.9-dev · Windows x64 시험판 ZIP |
| 게임·브라우저·런처 선택 | 앱 추가 창에서 설치·실행 중인 앱 여러 개 선택 |

환경에 따라 연결 품질과 호환성이 다를 수 있으며 게임 접속, 지연 시간 감소 또는 제재 면제를 보장하지 않습니다. 그린치즈는 넥슨과 제휴하지 않은 독립 서비스입니다.

## 도움이 되는 안내

- [회원가입부터 연결까지](https://greenchiz.com/guides/greenchiz-start)
- [넥슨 런처를 설치했는데 연결이 안 될 때](https://greenchiz.com/guides/nexon-launcher)
- [실제 개발판 앱 화면](https://greenchiz.com/#app-preview)
- [공유 이미지와 소개 문구](https://greenchiz.com/press)
- [안내 RSS](https://greenchiz.com/feed.xml)

## 공유 자료

`images/`의 자체 제작 브랜드 이미지와 `copy/`의 소개 문구는 서비스 소개 목적으로 무료 공유할 수 있습니다. 홍보가 허용된 공간에서 운영자 제공 자료임을 밝혀 주세요. 넥슨 공식 홍보나 이용 후기처럼 표현하지 마세요. 게임 로고·게임 이미지는 포함하지 않습니다.

## English summary

Greenchiz is a Korean Windows VPN service in free testing. The current download is the NEXT 0.8.9-dev Windows x64 trial ZIP with selected-application routing for installed games, browsers and launchers. This host release updates version labels and retains the 0.8.8 approval-guidance behavior. The privileged connection engine remains 0.8.7; all 96 bundled privileged resources are byte-identical. Server stability changes are applied separately: WAL and read snapshots, isolation of individual relay-socket failures, and temporary-busy responses compatible with unchanged clients. Server changes are not installed by this customer ZIP. A 130.14-second synthetic 50-member local test exercised renewals and authenticated echoes; it does not demonstrate 50 real PCs or long-running game continuity. Extract the entire ZIP and run GreenchizNext.exe. Nexon connection-file groups require explicit file preview and confirmation; VPN activation remains separate. The legacy 0.1.38 client remains a separate download. This repository contains public guides and original promotional assets, not private application/server source or credentials. No game access, latency or sanction-exemption guarantees are made. Independent from Nexon.

## 최신 시험판 다운로드

[NEXT 0.8.9 릴리스 안내와 파일](https://github.com/tkddlr0716-collab/greenchiz-vpn/releases/tag/next-0.8.9-dev) · [홈페이지 다운로드](https://greenchiz.com/download)

Windows x64 · 44,528,335 bytes · ZIP 전체 압축 해제 후 GreenchizNext.exe 실행. `_internal` 폴더를 함께 유지하세요. 기존 버전과 동시에 VPN을 제어하지 마세요.

0.8.9는 앱과 Windows 파일 정보의 버전 표시를 맞췄으며, 0.8.8의 승인 안내 창 정리를 유지합니다. 실제 연결 엔진은 **0.8.7**, 관리자 연결 리소스 **96개는 이전 배포본과 모두 동일**합니다. Chrome·Edge VPN 기능이나 클라이언트 연결·재시도 코드는 변경하지 않았습니다.

서버 안정화 변경은 별도로 반영합니다. 회원 원장의 WAL·읽기 스냅샷 분리, 개별 중계 소켓 오류의 영향 범위 분리와 익명 오류 진단을 포함합니다. 일시적인 사용 중 응답은 기존 앱이 인식하는 HTTP 503/`service_unavailable`로 전달하며, 권한 만료·철회 기준은 유지합니다. 서버 반영 후에는 기존 0.8.8 앱도 같은 호환 방식을 사용합니다. 이 고객 ZIP이 서버 변경을 설치하는 것은 아닙니다.

임시 SQLite와 메모리 전송에서 합성 회원 50명의 130.14초 시험을 완료했습니다. 갱신 350회·작업 완료 350회·인증된 데이터 왕복 24,800회·원장 읽기 1,210회와 쓰기 잠금 중 읽기 21회를 확인했습니다. 실제 회원이나 외부 목적지는 사용하지 않았으며, 실제 50대 PC·인터넷 속도·장시간 게임 연결을 보장하는 시험은 아닙니다. 고객 ZIP의 CRC·소스 제외·리소스 핀·읽기 전용 시작·WebView 확인도 통과했습니다.

프로젝트 전체 소스·Python/C++ 원본·개발 문서·계정 저장소는 고객 ZIP에 포함하지 않습니다. 실행용 화면 파일과 타사 라이선스·정확한 Proton 드라이버 대응 소스는 유지합니다.

배포 ZIP SHA-256: `ce8de945066f641783726e08247eb2b5493e4c8963155e94e0928a0866397a27`.

### 이전 버전 기록 · 0.8.8

[NEXT 0.8.8 릴리스 안내와 파일](https://github.com/tkddlr0716-collab/greenchiz-vpn/releases/tag/next-0.8.8-dev) · [홈페이지 다운로드](https://greenchiz.com/download)

Windows x64 · 44,527,131 bytes · ZIP 전체 압축 해제 후 GreenchizNext.exe 실행. `_internal` 폴더를 함께 유지하세요. 기존 버전과 동시에 VPN을 제어하지 마세요.

0.8.8은 앱 시작 때 불필요한 Windows 연결 안내 창을 숨기고, 연결·정리 작업 전체가 끝나면 승인 안내 창을 숨기도록 정리했습니다. 수동 승인 요청과 알림 영역을 사용할 수 없는 경우의 안내는 유지합니다. 화면과 Windows 파일 정보의 버전 표시도 맞췄습니다.

일반 사용자 권한의 앱 실행부만 갱신했으며, 실제 연결 엔진은 **0.8.7**입니다. 관리자 연결 리소스 **96개는 이전 0.8.7 배포본과 모두 동일**합니다. 이 배포에서 드라이버·연결 경로·계정 처리 방식을 변경하지 않았습니다. 새 안내 창 동작을 사용하려면 새 실행 파일을 실행해야 합니다.

안내 창 동작 7개, 버전 정보 3개, 빌드 범위 1개 시험과 배포 ZIP 검사·읽기 전용 시작·WebView 확인을 통과했습니다. 실제 게임 중 장애 복구나 모든 PC·게임의 접속과 장시간 안정성을 검증한 결과는 아닙니다.

배포 ZIP SHA-256: `0ecbb09ab756581d80ff5f476b763279391befb03fe8514ce2692e024b7d0a4e`.

### 이전 버전 기록 · 0.8.7

0.8.7은 일시적인 서버 응답·경로 손실에서 기존 연결 정보를 유지하며 재시도하는 동작과 문의용 진단을 보완했습니다. 기존 서버 인증과 이용 권한이 유효한 범위에서만 유지하며, 권한 만료·인증 거부·파일 검증 실패 등의 종료 조건은 유지합니다. 앱 변경 응답을 놓친 경우 같은 요청을 다시 확인하며, 불확실한 변경을 성공으로 표시하지 않습니다. 당시 연결 실행부를 재빌드했고 커널 드라이버와 네이티브 연결 컨트롤러는 유지했습니다.

당시 오류 주입은 메모리·로컬 루프백 시험에서 수행했습니다. 이 PC에서 앱 실행과 세 통신 경로 응답을 관찰했으며, 실제 게임 중 장애를 일으켜 복구를 시험한 것은 아닙니다.

### 이전 버전 기록 · 0.8.6

0.8.6은 앱 안의 공식 서비스 공지, 제휴 문의 안내와 팝업 여백을 정리한 버전입니다. 공지 조회에는 계정 토큰·이메일·기기 식별자를 붙이지 않으며, 공지를 읽는 동작은 VPN 연결이나 앱 선택을 바꾸지 않습니다. 기존 0.8.5의 VPN 실행 리소스 96개와 연결 파일 확인 방식은 유지합니다. 새 기능을 사용하려면 새 ZIP을 내려받아 실행해야 합니다.

### 이전 버전 기록 · 0.8.5

0.8.5에서는 넥슨 런처와 게임의 **연결 파일 확인 → 목록 검토 → 확인한 파일 저장**을 제공합니다. 넥슨 런처 본체·런타임·웹 모듈 3개와 설치 정보에서 확인한 클래식 월드 본체 1개를 각각 검증합니다. 미리보기나 저장만으로 VPN을 켜지 않으며, 저장 후 사용할 앱 ON → 통합 VPN ON으로 적용합니다. 저장된 파일 목록과 실제 적용이 확인된 파일 목록을 구분해 표시합니다.

당시 0.8.5로 한 PC에서 사용자가 런처와 게임을 실행한 뒤 동작을 확인했습니다. 당시 적용 확인 응답은 4개 실행 파일이었고, 읽기 전용 연결 관찰에서 넥슨 웹 모듈의 TCP 연결 16개와 메이플 본체의 TCP 연결 4개가 터널 주소를 사용하는 것을 확인했습니다. 해당 시점에 관찰한 두 프로세스의 다른 출구 TCP 연결은 없었습니다. 이는 해당 PC·프로세스·관찰 시점의 결과이며 0.8.9의 새 게임 입장 검증이나 모든 트래픽·다른 PC·모든 게임의 접속을 검증한 결과는 아닙니다.

0.8.3부터 라이브러리에서 앱을 누르면 내 앱에 추가만 합니다. 새 앱은 사용 OFF로 저장되고, 이미 추가된 카드를 눌러도 사용 상태나 연결은 바뀌지 않습니다. 상단 내 앱에서 사용할 앱을 ON으로 고른 뒤 통합 VPN으로 연결하세요. 넥슨·글클메 설치 탐지를 보강하고, 경로를 못 찾은 항목도 직접 찾기 안내로 표시합니다. 이 PC의 실제 배포 EXE가 두 앱을 탐지함을 확인했습니다. 같은 PC에서 계정별 목록과 선택을 저장하며 다른 PC의 설정 동기화나 실제 게임 접속 성공을 검증한 결과는 아닙니다. 프로젝트 전체 소스 ZIP은 공개 배포하지 않습니다. 실행용 화면 파일과 타사 드라이버 대응 소스는 포함됩니다.


### 이전 버전 기록 · 0.8.4

0.8.4는 문의용 진단을 보강한 버전입니다. 중계 시험 응답과 터널 송수신량, 선택한 실행 파일 항목, 마지막 VPN ON 상태를 개인정보 없이 확인할 수 있습니다. 마지막 ON 기록은 앱 메모리에만 보관하며 계정 변경·로그아웃 시 삭제합니다. 터널 시험과 송수신량은 넥슨 런처 접속 성공을 의미하지 않습니다. 당시 버전은 연결 경로·드라이버·DNS·넥슨 보조 실행 파일 자동 등록을 변경하지 않았으며, 보고된 넥슨 인터넷 확인 오류가 해결됐다고 확인한 버전은 아닙니다.
