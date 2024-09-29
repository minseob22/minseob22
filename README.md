## Hi there 👋 I am currently studying react and Unity with interest.

<!--
**minseob22/minseob22** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- I am currently studying react and Unity with interest.
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->



###202033624 한민섭

## CLI
- 굉장히 빠르고 간결하다.
- 반복 작업에 유리하다.
- 리소스 활용도가 높다.

# Linux

- 유닉스와 비슷하게 만들어진 운영체제이다.
- 오픈소스로 많은 사람들이 관심을 갖고 있어 보안에 강하다.
  - 오픈소스 사용자들이 빠르게 보완한다.
- 서버로 사용 시, **업데이트 시 재부팅 없이 가능**하여 안정적(stable)이다.
- 우분투, 데비안 등과 같은 리눅스 배포판은 GUI 형태로 이용 가능하다.

# Linux의 구조

## Hardware
- 하드웨어는 물리적 장치를 의미한다.

## Kernel
- 하드웨어와 직접적으로 소통하면서 사용자의 명령을 수행한다.
- 사용자가 직접 접근하는 것은 아니다.

## Shell
- 사용자가 커널과 통신하는 도구이다.

### Shell 종류
- CLI 형태의 Shell
- GUI 형태의 Shell

# CLI vs GUI

## CLI의 장점과 단점
- **장점**:
  - 반응 속도가 빠르다.
  - 여러 단계의 명령을 단계적으로 수행 가능하다.
  - 개발자들이 선호한다.
- **단점**:
  - 명령어를 기억해야 한다.

## GUI의 장점과 단점
- **장점**:
  - 직관적 사용이 가능하며 명령어를 기억할 필요가 없다.
  - 일반 사용자가 선호한다.
- **단점**:
  - 반응 속도가 느리다.
  - 여러 단계를 직접 클릭해야 하므로 번거롭다.

# Linux Terminal 사용하기

- Linux나 Mac은 터미널을 실행하면 되지만, Windows에서는 Git Bash 사용이 필요하다. (Windows는 리눅스 환경이 아님)
- VM을 설치하여 Windows에 리눅스를 설치할 수 있다.

# 기본 명령어

## 현재 경로 확인
- `pwd`: 현재 디렉토리 위치 확인

## 디렉토리 이동
- `cd [디렉토리명]`: 디렉토리 변경
- `/`: 루트 디렉토리
- `.`: 현재 작업 중인 디렉토리
- `..`: 한 단계 상위 디렉토리
- `~`: 홈 디렉토리
- `/ [디렉토리 이름]`: 절대 경로로 작업
- `./ [디렉토리 이름]`: 현재 디렉토리 기준
- `../ [디렉토리 이름]`: 현재 디렉토리의 한 단계 위

## 파일 및 디렉토리 조회
- `ls`: 현재 디렉토리의 하위 디렉토리 및 파일 목록 조회
- `ls -l`: 자세한 정보와 함께 파일 및 디렉토리 목록 조회
- `ls -lh`: 사람이 이해할 수 있는 형태로 표시
- `/bin`: `/bin` 디렉토리의 파일 목록
- `-l /etc/bin`: `/bin` 및 `/etc` 디렉토리의 파일 목록을 자세히 표시
- `-la`: 숨김 파일 포함 모든 파일 표시

## 편리한 팁
- **Tab**: 자동 완성
- **화살표 위쪽**: 이전 명령어 불러오기
- `clear`: 화면 지우기 (기존 내용 삭제는 아님)

# 파일 조작 명령어

## 복사
- `cp [기존 폴더] [새 이름의 폴더]`: 기존 폴더와 같은 내용을 가진 새로운 폴더 생성 (이미 있는 폴더 이름을 사용하면 덮어쓰기됨)
- `cp -R [dir1] [dir2]`: 디렉토리를 복사

## 이동 및 이름 변경
- `mv [기존 이름] [새 이름]`: 파일 이름 변경
- `mv [파일 이름] [디렉토리]`: 파일을 해당 디렉토리로 이동

## 삭제
- `rm [file1] [file2]`: 파일 삭제 (영구적 삭제)
- `rm -r [디렉토리]`: 디렉토리 및 하위 내용 삭제

## 새 디렉토리 생성
- `mkdir [디렉토리 이름]`: 새로운 디렉토리 생성

## 한꺼번에 파일 이동
- `cp *.txt [dir name]`: 확장자가 `.txt`인 모든 파일을 특정 디렉토리에 복사
