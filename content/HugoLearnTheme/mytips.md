---
title: 사용팁
description : "실제 적용할 때 필요한 팁 정리"
weight: 1
---

{{% notice tip %}}
그냥 쓰다보면 꼭 그대로 잘 안되고 걸린다.
필요한 내용을 정리해 두자.
{{% /notice %}}

# 🥢 Hugo 활용시 팁 정리

### _index.md 파일은
- .Kind 는 .section 으로 선택되고,
- 레이아웃은 list.html 이 선택되어 변환된다.

### 테마 수정이 필요하면
- 직접 테마를 복사해서 수정하지 말고,
- Hugo 디렉토리 밑에 layouts 라는 디렉토리에 복사해서 수정하면 된다.
    - 여기에 동일한 파일이 있으면, 테마의 파일보다 우선해서 사용하게 되어 있다.
    - 자세한 내용은 ["Hugo 테마 깔끔하게 사용하기" 글](https://blog.lkaybob.pe.kr/post/tech/hugo-override-theme-template/) 참고
