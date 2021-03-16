---
title: "WSL2 설정법"
date: 2019-12-16T10:10:00-05:00
categories:
  - 개발환경
tags:
  - WSL
  - OpenFOAM
---
### - Windows 빌드 버전 확인
  **요구사항:** WSL2를 사용하기 위해 Windows 10 빌드 18917 이상인지 확인
  {: .notice--info}

  ```bash
  #Windows 빌드 확인
  > ver
  ```
***

### - WSL 활성화 명령어
  가상 컴퓨터 플랫폼 옵션 구성 요소 사용 설정 / WSL 사용 설정
  {: .notice--info}
  ```bash
  #Windows 가상 머신 활성화
  > dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
  > dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
  ```
***

### - Linux 배포판 설치
  * Microsoft Store에서 다운로드 및 설치
  * 명령줄/스크립트에서 다운로드 및 설치
  * 다운로드 및 수동으로 압축을 푼 후 설치
  {: .notice--info}
***

### - Linux 배포판을 WSL2로 설정 
  ```bash
  #Linux 배포판 WSl2 설정
  # <Distro>에 Linux 배포판 이름 삽입
  > wsl --set-version <Distro> 2
  ```
***

### - Linux 배포판 WSL 버전 확인
  ```bash
  #Linux 배포판 WSL 버전 확인
  > wsl -l -v
  ```
***
