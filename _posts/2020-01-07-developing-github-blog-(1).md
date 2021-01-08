---
layout: post
title: Github Blog 개발 일지 (1) - 개발환경 설정!
categories: ['Github Blog']
excerpt: <strong>Github Blog</strong> 개발 일지 - 개발환경 설정
tags: ['Github.io', 'jekyll']
toc: true
---

## **개요**  

필자는 웹에 대한 지식이 부족해 Github Blog를 만드는 데 여러 번의 시행착오를 겪었다. <br>예를 들어 만들다가 날린 repo만 10개가 넘고 아직도 이해하지 못한 부분도 있다. <br>그래도 우여곡절 끝에 지금의 Blog를 만들었고 나와 같은 상황에 놓인 사람들을 돕기 위해 작성하였다.

> 이번 Post에서는 Github Blog 개발에 앞서 필요한 개발환경을 설정하는 방법을 소개한다.<br>**내용 중에 오류 혹은 궁금한 점이 있으면 댓글로 알려주세요!**

> **개발환경 : Windows 10**

## 목차

1. [VScode 설치](#vscode-설치)
2. [Github Desktop 설치](#github-desktop-설치)
3. [Jekyll 설치](#jekyll-설치)

## VSCode 설치

> Github Blog 개발에 사용할 에디터를 정해야 한다.<br>다른 에디터를 사용해도 되지만 VSCode로 개발하여 VSCode 기준으로 작성했다.

VSCode 설치는 [https://code.visualstudio.com/](https://code.visualstudio.com/) 에 들어가서 하면 된다.

이 부분에서 주의할 점은 encoding: utf-8으로 해줘야 한다.<br>만약 파일 형식이 utf-8으로 되어있지 않다면 invalid utf-8 에러를 띄우면서 markdown 업로드가 되지 않는다.

## Github Desktop 설치

> 이 부분은 선호에 맞게 설치해도 되고 안해도 되는 부분이다.<br>필자는 이번 기회에 Github 사용법을 익히고자 설치하여 사용했다.<br>

Github Desktop을 설치하면 github 페이지에서 clone할 때 Open with Github Desktop으로 편리하게 clone 받아 사용할 수 있다.

또한 Github Desktop을 설치했다면 File-Options-Integrations에서 External editor를 Visual Studio Code로 변경해줘야 한다. 그러면 Github Desktop에서 

## Jekyll 설치

> 본인은 개발을 시작할 때 jekyll 설치가 어려워보여 안하고 시작했다. <br>블로그 디자인을 할 때는 문제가 없었지만 Post를 업로드 하거나, Blog layout을 변경할 때 에러가 난다는 것을 깨닫고 설치했다.

**[Jekyll 표준 문서](http://jekyllrb-ko.github.io/docs/installation/)** 에 들어가면 설치 방법이 자세하게 설명되어 있다.

필자는 Windows10에 Ubuntu를 설치해서 Ubuntu에 Jekyll을 설치해 사용하였다.

Ubuntu에서 실행할 경우 `cd /mnt/c/`를 해줘야지 윈도우 파일 시스템으로 이동할 수 있다.

예를 들어 필자와 같은 경우는  `cd /mnt/c/Users/temp/Desktop/github.io/`에 repo를 clone하여 local 환경에서 실행하였다.