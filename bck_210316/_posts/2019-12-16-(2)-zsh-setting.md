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
  
{% capture notice-2 %}
* **파일위치:** /etc/apt/sources.list
* **변경내용:** archive.ubuntu.com > mirror.kakao.com
{% endcapture %}

<div class="notice">
  {{ notice-2 | markdownify }}
</div>

#### Shell
```bash
#sources.list 열기
> sudo vi /etc/apt/sources.list
```

#### vi
```bash
#주소 변경
> :%s/archive.ubuntu.com/mirror.kakao.com

#저장 후 종료
> :wq
```

#### Shell
```bash
#sources.list 업데이트
> sudo apt-get update
```
***

### - zsh 설치

```bash
#zsh 설치
> sudo apt-get install zsh
```

### - Oh my zsh 설치

```bash
#Oh my zsh 설치
> sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
***

### - zsh 테마 변경

#### shell
```bash
#zshrc 열기
> sudo vi ~/.zshrc
```
#### vi

{% capture notice-2 %}
* **기존내용:** ZSH_THEME="robyrussell"
* **변경내용:** ZSH_THEME="agnoster"
{% endcapture %}

<div class="notice">
  {{ notice-2 | markdownify }}
</div>

***