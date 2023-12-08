# Study-practice

## 버전관리 이해
- 버전관리란? : 시간의 흐름에 따라 파일 집합에 대한 변경 사항을 추적, 관리
- 커밋(commit) : ~적어두다
- 버전관리의 커밋 : 저장소의 현 상태를 저장하는 행위, 파일 집합의 변경 내용을 깃 저장소에 기록하는 작업

## 깃과 깃허브 개요

### 깃허브 이해
- Github : 버전 관리를 위한 서버 저장소 및 프로젝트 개발을 위한 협업 관리 서비스(시스템 개발자와 운영을 담당하는 정보기술 전문가 사이의 소통, 협업, 통합 및 자동화 지원), 프로젝트 소스 공유와 협업 소프트웨어 빌드 플랫폼
- Git : 분산 버전 제어 SW
- Github : Git을 위한 웹 저장소(Repository)

## 깃 설정
  ### 주요 설정
  - $ git config --global user.name 이름 (사용자 이름)
  - $ git config --global user.email 이메일 주 (사용자 전자 메일)
  - $ git config --global core.autocrlf true (줄바꿈 자동변환)
  - $ git config --global core.safecrlf false (줄바꿈 안전 설정)
  - $ git config --global core.editor 'code --wait' (기본 편집기 설정)
  - $ git config --global init.defaultBranch main (기본 브랜치 이름)
  ### 저장소 생성
  - $ git init basic (저장소 생성)
  - $ cd basic (폴더 이동)
  - $ ls-al (파일 확인)

## 리눅스 명령
  ### 폴더 관련 명령
  - $ pwd (Print Working Directory 현재 폴더 표시)
  - $ cd (Change Directory)
  - $ ls (File or folder list 다양한 옵션)
  ### 파일 관련 명령  : 생성
  - $ touch fname (빈 파일 fname 생성)
  ### 파일 및 폴더 삭제
  - $ rm fname (파일 fname 삭제)
  - $ rm -rf dname (하부에 서브폴더와 파일이 있어도 폴더 삭제, 옵션 사용 / -f:강제로 파일이나 디렉토리를 삭제 / -r:디렉토리 내부의 모든 내용을 삭제

## 커밋
  ### 커밋(commit)
  - $ git commit (커밋 메세지를 입력할 기본 편집기 실행됨
  - $ git commit -m 'message' (커밋 메세지를 직접 입력)
  - $ git commit -a -m 'message'
  ### $ git log
  - $ git log (로그 이력 정보를 표시)
  - $ git log --oneline (로그 이력을 한 줄로 표시)
  ### 커밋 정보 git show
  - $ git show (마지막 커밋(HEAD)의 커밋 정보 표시)
  - $ git show --oneline (커밋 로그 한 줄과 파일 차이 표시)
  - $ git show -s (파일 차이는 표시되지 않음)
  - $ git show [HEAD] (지정한 HEAD의 커밋 정보 표시)
