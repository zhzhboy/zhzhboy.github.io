---
title: "WSL 개발환경 구축"
date: 2019-12-16T10:22:00-05:00
categories:
  - 개발환경
tags:
  - zsh
  - OpenFOAM
---
### - Ubuntu source list 변경
  **파일위치:** /etc/apt/sources.list

  **변경내용:** archive.ubuntu.com > mirror.kakao.com
  {: .notice--info}

  ***Shell***
  ```bash
  #sources.list 열기
  > sudo vi /etc/apt/sources.list
  ```

  ***vi***
  ```bash
  #주소 변경
  > :%s/archive.ubuntu.com/mirror.kakao.com

  #저장 후 종료
  > :wq
  ```
***

### - zsh 설치
  **PowerShell이 아닌 WSL 내부에서 작업 수행**
  {: .notice--info}

  ```bash
  #zsh 설치
  > sudo apt-get install zsh
  ```
***