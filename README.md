안녕하세요. 첫 번째 개발 프로젝트입니다.

## 개발 환경 구축 실습 기록

### 1. 개발 환경
- 운영체제 환경: Windows + WSL 2 Ubuntu
- 버전 관리: Git, GitHub
- 컨테이너 도구: Docker Desktop
- Docker 버전: 29.9.2
- Docker Compose 버전: 5.6.1

### 2. Linux 명령어 실습
- `pwd`: 현재 위치 확인
- `ls`, `ls -la`: 파일 목록과 숨김 파일 확인
- `mkdir`: 폴더 만들기
- `touch`: 빈 파일 만들기
- `echo`: 파일에 내용 쓰기
- `cat`: 파일 내용 확인
- `cp`: 파일 복사
- `mv`: 파일 이름 변경
- `rm`: 파일 삭제
- `chmod 600 permission-test.txt`: 파일 권한 변경

### 3. Docker 실습
- `docker --version`: Docker 버전 확인
- `docker run hello-world`: Docker 실행 확인
- Dockerfile을 작성해 웹사이트 이미지 빌드
- 컨테이너를 실행하고 포트 8080으로 웹사이트 확인
- Bind Mount로 호스트 파일과 컨테이너 연결
- Docker Volume에 데이터를 저장하고 다시 읽어 확인
- `docker ps`, `docker images`, `docker logs`로 상태 확인

### 4. 웹사이트 실습
- `index.html` 작성
- `Dockerfile` 작성
- 이미지 이름: `my-first-web`
- 컨테이너 이름: `my-web`
- 브라우저 주소: http://localhost:8082
- Bind Mount 테스트 주소: http://localhost:8081

### 5. 문제 해결 기록
- 문제: Ubuntu에서 `wsl` 명령어를 실행할 수 없음
  - 원인: `wsl`은 Windows PowerShell에서 사용하는 명령어임
  - 해결: PowerShell에서 `wsl`을 실행해 Ubuntu에 진입

- 문제: Docker 명령어를 찾을 수 없음
  - 원인: Docker Desktop과 WSL Ubuntu의 연결 상태 문제
  - 해결: Docker Desktop의 WSL Integration 설정을 확인하고 재시작한 뒤 Docker 버전을 확인

### 6. 추가 Linux 파일 실습
- `linux-practice` 폴더 생성
- `first.txt` 파일 생성 및 내용 확인
- 파일 복사와 이름 변경
- 숨김 파일 `.secret.txt` 생성
- `documents` 폴더에 파일 복사
- `ls -la`로 파일 권한과 숨김 파일 확인

### 7. 실습 체크리스트
- [x] Git 및 GitHub 저장소 설정
- [x] Docker 설치 및 실행 확인
- [x] Dockerfile로 웹사이트 이미지 빌드
- [x] 포트 연결 후 웹사이트 확인
- [x] Bind Mount 실습
- [x] Docker Volume 데이터 저장 및 확인
- [x] Linux 파일 및 폴더 관리
- [x] 파일 권한 및 숨김 파일 확인
- [x] README 실습 기록 작성

## 개발 환경 구축 실습 기록

### Linux 실습
- [x] 현재 위치 확인: pwd
- [x] 파일 목록 확인: ls, ls -la
- [x] 폴더 생성: mkdir
- [x] 파일 생성 및 내용 확인: touch, echo, cat
- [x] 파일 복사 및 이름 변경: cp, mv
- [x] 파일 삭제: rm
- [x] 숨김 파일 확인: .secret.txt
- [x] 파일 권한 변경: chmod 600

### Docker 실습
- [x] Docker 버전 확인: 29.9.2
- [x] hello-world 실행
- [x] Dockerfile 작성 및 이미지 빌드
- [x] 웹사이트 실행: http://localhost:8082
- [x] Bind Mount 실습: http://localhost:8081
- [x] Docker Volume 데이터 저장 및 확인

### 문제 해결 기록
- Windows PowerShell과 Ubuntu의 명령어 및 경로 차이를 학습함
- Docker Desktop의 WSL Integration 설정을 확인함
