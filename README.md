# 방학이보이는 나이스 도우미 다운로드

나이스 자동입력과 교과 성적 일람표 마스킹을 한곳에서 사용하는 Windows 프로그램입니다.

## 설치 없이 실행

**[무설치 EXE 바로 다운로드 — 고정 주소](https://github.com/moonsugugu/neis-tools-download/releases/latest/download/neis-tools.exe)**

파일 하나를 내려받아 실행하세요. 설치나 Python 설치가 필요하지 않습니다.

고정 주소에는 버전 번호가 없으며, 최신 릴리스마다 같은 파일 이름을 사용합니다. 이전에 공유한 `neis-tools-5.0.0-portable.exe`, `neis-tools-5.0.2-setup.exe`, `neis-tools-5.0.2-x64.zip`의 `/releases/latest/download/…` 주소도 호환용 파일 이름으로 최신 내용을 제공합니다. 호환 파일 이름에 적힌 예전 버전과 실제 앱 버전은 다를 수 있습니다.

- [폴더형 ZIP](https://github.com/moonsugugu/neis-tools-download/releases/latest/download/neis-tools-5.0.3-x64.zip): 전체 압축을 풀고 `방학이보이는나이스도우미.exe`를 실행하세요. 내부 파일 `neis-tools-runtime.exe`를 직접 실행하지 마세요.
- [Windows 설치형](https://github.com/moonsugugu/neis-tools-download/releases/latest/download/neis-tools-5.0.3-setup.exe)
- [항상 최신 릴리스](https://github.com/moonsugugu/neis-tools-download/releases/latest)
- [SHA-256 체크섬](https://github.com/moonsugugu/neis-tools-download/releases/latest/download/SHA256SUMS.txt)

5.0.3은 바탕화면·임시 폴더의 AppContainer 권한 때문에 이전 무설치판이 시작 전에 종료되던 문제를 보완했습니다. 실행기가 앱 폴더의 필요한 읽기·실행 권한만 확인하며 보안 샌드박스는 유지합니다. 바탕화면·임시 폴더 전체 권한은 바꾸지 않습니다.

## 주요 기능

- 나이스 자동입력: 엑셀·한셀 내용 붙여넣기, Tab 횟수·속도·전학 처리, F8 비상정지
- 일람표 마스킹: xlsx·hwp·hwpx의 학교·학년반·학생 이름 삭제, 과목명으로 저장
- 파일 선택과 끌어놓기 지원, 원본 및 이전 결과 보존
- 마스킹 파일은 PC 안에서 처리하며 외부 서버로 전송하지 않습니다.

나이스의 **학급담임 → 성적 → 성적조회 → 교과별성적조회 → 엑셀로 저장**으로 저장한 엑셀 파일을 마스킹 탭에 올리세요. 생성된 마스킹 파일을 성적처리기에 올리면 학생 번호순으로 평어를 생성할 수 있습니다.

마스킹은 ‘교과 성적 일람표’ 양식을 기준으로 처리합니다. 결과에 경고가 있으면 개인정보가 지워졌는지 확인해 주세요. 암호·배포용 한글 문서는 지원하지 않습니다.

이 저장소는 공개 다운로드와 버전별 실행 파일 배포용입니다.

made by [제작자소개](https://moonsunezipbrand.vercel.app) · [Instagram](https://www.instagram.com/moonsune.zip/) · [문수네집 컨텐츠사이트](https://moonsunezip.com)
