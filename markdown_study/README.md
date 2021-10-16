# 1. 제목(Header)

* 글머리 : 1 ~ 6 까지만 지원가능하다.

```
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6
```

# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6

####### This is a H7  (지원하지 않는다.)

# 2. 수평선 (Horizontal Rule)

* 각 기호를 3개 이상 입력

```
--- 
(hyphens)
*** 
(asterisks)
___ 
(underscores)
```

---

(hyphens)

***

(asterisks)

___

(underscores)

# 3. 목록

### 순서있는 목록(번호)

#### 순서있는 목록은 숫자와 점을 사용한다.

```
1. 첫번째
2. 두번째
3. 세번째
```

1. 첫번째
2. 두번째
3. 세번째

#### 어떤 번호를 입력해도 순서는 내림차순으로 정의된다.

```
1. 첫번째
3. 세번째
2. 두번째
```

1. 첫번째
3. 세번째
2. 두번째

### 순서없는 목록(글머리 기호: ```*```, ```+```, ```-``` 지원)

```
* 빨강
	* 녹색
		* 파랑
+ 빨강
	+ 녹색
		+ 파랑
- 빨강
	- 녹색
		- 파랑		
```

* 빨강
	* 녹색
		* 파랑

+ 빨강
	+ 녹색
		+ 파랑
- 빨강
	- 녹색
		- 파랑

### 혼합해서도 사용가능

```
* 빨강
	+ 녹색
		- 파랑
			* 노랑
```

* 빨강
  + 녹색
  	- 파랑
  		* 노랑

# 4. BlockQuote

* 이메일에서 사용하는 블럭인용문자 ```>``` 를 사용한다.

```
> This is a first blockquote.
>> This is a second blockquote.
>>> This is a third blockquote.
```

> This is a first blockquote.
> > This is a second blockquote.
> >
> > > This is a third blockquote.

#### 이 안에서는 다른 마크다운 요소를 포함할 수 있다. 

> This is a blockquote.
>
> * list
>
>   ```
>   example
>   ```

# 5. 링크

* 참조링크

```
[link keyword][id]

[id]: URL "Optional Title here"

// code
Link: [Google][googlelink]

[googlelink]: http://google.com "Go google"
```

Link: [Google][googlelink]

[googlelink]: http://google.com "Go google"

* 외부링크

```
사용문법: [Title](link)
적용 예: [Google](http://google.com, "google link")
```

Link: [Google](http://google.com, "google link")

* 자동연결

```
일반적인 URL 혹은 이메일주소인 경우 적절한 형식으로 링크를 형성한다.
* 외부링크: <http://example.com>
* 이메일링크: <address@example.com>
```

* 외부링크: <http://example.com>
* 이메일링크: <address@example.com>

# 6. 강조

```
* *single asterisks*
* _single underscores_
* **double asterisks**
* __double underscores__
* ~~cancelline~~
* <mark>highlighter</mark>
* <u>underline</u>
```

* *single asterisks*

* _single underscores_

* **double asterisks**

* __double underscores__

* ~~cancelline~~

* <mark>highlighter</mark>

* <u>underline</u>

  

  

