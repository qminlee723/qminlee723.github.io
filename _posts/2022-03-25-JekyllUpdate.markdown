---
layout: post
title:  "brief note on blog updates for my own reference"
date:   2022-03-25 01:27:26 +0900
categories: jekyll update
---

* 이미지파일 추가
```
<img data-action="zoom" src='{{ "/folder_name/image_name.jpg" | relative_url }}' alt='absolute'>
```

* 첨부파일 추가
```
\[BUTTON_NAME][\1]
\[1]:{{ yoursite.url }}/folder_name/file_name.pdf
```

* 폰트 사이즈, 색상 
```
<span style="font-size:1em; color:orchid">*Samsung*</span><br>
```

* markdown에서 이모지 사용할 수 있게
```
gem install 'jemoji'
_config.yml 안 plungin:에 - jemoji 추가해주기
```

  * :smile: :sparkles: :+1:

정리는 나중에할거야....


