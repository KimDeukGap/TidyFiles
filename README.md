# TidyFiles

간단하고 실용적인 **파일 자동 정리 스크립트**입니다.  
확장자별 또는 날짜별로 파일을 자동으로 정리해줍니다.

---

## 기능
- **확장자별 정리**: `.jpg`, `.pdf`, `.txt` 등 확장자별로 폴더 생성 후 이동
- **날짜별 정리**: 파일 생성 날짜 기준으로 `YYYY-MM-DD` 폴더에 정리
- 간단한 CLI 인터페이스 제공

---

## 설치 및 실행 방법
1. 레포지토리 클론
   ```bash
   git clone https://github.com/username/TidyFiles.git
   cd TidyFiles
2. 스크립트 실행 Bash셸 -> python tidyfiles.py
3. 입력값
- 정리할 폴더 경로 입력
- 정리 모드 선택: extension 또는 date

사용 예시:
- 정리할 폴더 경로를 입력하세요: C:/Users/성민/Documents
- 정리 모드 선택 (extension/date): extension

결과:
- report.pdf → C:/Users/성민/Documents/pdf 로 이동 완료
- photo.jpg → C:/Users/성민/Documents/jpg 로 이동 완료

요구사항
- Python 3.x
- 추가 라이브러리 없음 (표준 라이브러리만 사용)
