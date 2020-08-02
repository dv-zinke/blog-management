---
title: Hexo로 만든 블로그 (theme - icarus) 글 작성할때 markdown
thumbnail: /gallery/thumbnails/200708_markdown.png
date: 2020-07-08 00:20:10           
tags:
    - Hexo
    - markdown
categories:
    - Life
    - Blog    
---


Hexo에서 마크다운(markdown) 사용하기

# Text  
입력 
```
# title // h1
## title // h2 
### title // h3
#### title // h4
##### title // h5 
###### title // h6
```

OutPut
# title // h1
## title // h2 
### title // h3
#### title // h4
##### title // h5 
###### title // h6
 

# 강조
입력
```
`강조텍스트`
```


Output
`강조텍스트`



# Link 
입력
```
[blog](https://dv-zinke.github.io/) 
```

OutPut
[blog](https://dv-zinke.github.io/) 

<!-- more -->

# Code highlight
```javascript
function test(){
    console.log("test");
}
```


# Table

### 입력 
```
| column | column | column |
|---:|---:|---:|
| row | row | row |
| row | row | row |
| row | row | row |
| row | row | row |

```

### OutPut
| column | column | column |
|---:|---:|---:|
| row | row | row |
| row | row | row |
| row | row | row |
| row | row | row |

# List 

### 입력 
```
1. 리스트
1. 리스트
1. 리스트 

```

### Output
1. 리스트
1. 리스트
1. 리스트 

### 입력 
```
- 리스트
    - 리스트
        - 리스트
```

### OutPut
- 리스트
    - 리스트
        - 리스트
           
