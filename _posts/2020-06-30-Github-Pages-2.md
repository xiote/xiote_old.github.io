---
layout: post
title: Github Pages 가지고 놀기 - Jekyll 연결
---

```bash
# Github사이트에서 [xiote.github.io] repository 생성

# 현재 위치
pwd
/Users/xiote/github.com/xiote/xiote.github.io

# Jekyll 프로젝트 push
git remote add origin https://github.com/xiote/xiote.github.io.git
git push -u origin master

# 확인
curl https://xiote.github.io/
```

참고
---
[Jekyll 가지고 놀기 - Setup](Jekyll-3.html)
