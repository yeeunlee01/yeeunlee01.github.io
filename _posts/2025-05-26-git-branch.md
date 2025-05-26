---
title: Git branch submodule 삭제하는법 
date: 2025-05-26 10:00:00 +0800
categories: [SW]
tags: [SW, Github]
---

오픈소스 프로젝트를 clone하여 수정한 후, 내 branch에 push하면 종종 예상치 못한 문제가 발생할 수 있습니다. 가장 흔한 문제는 clone한 오픈소스 코드가 push 시에 업로드되지 않는 현상입니다. 이는 해당 오픈소스 폴더가 내 브랜치의 Submodule로 인식되어 발생하는 문제입니다.

Submodule로 인식되면 부모 브랜치 저장소와 서브모듈 저장소가 별도로 관리되어, 코드를 한 곳에서 관리하기가 어려워집니다. 이 문제를 해결하기 위해서는 Submodule을 해제하고 수정한 코드를 함께 push해야 합니다. 구체적인 해결 방법은 아래에서 설명하겠습니다.



