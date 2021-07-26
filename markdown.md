ReadMe 팁 : vscode 내장된 Markdown : Open Preview 사용해서 미리보기 가능

<!-- Heading -->

# Heading 1

(사용방법 # Heading 1)

## Heading 2

(사용방법 ## Heading 2)

### Heading 3

(사용방법 ### Heading 3)

#### Heading 4

(사용방법 #### Heading 4)

##### Heading 5

(사용방법 ##### Heading 5)

<!-- Line -->

---

(라인 사용방법 : \_\_\_ ) ( \_ 3번 )

---

<!-- Text -->

## Text

bold **Text** 입니다. </br>
(bold 사용법 : \*\*문장\*\*) </br>
<br>
italic _Text_ 입니다. </br>
(bold 사용법 : \*문장\*) </br>
<br>
strikethrough ~~Text~~ 입니다. </br>
(bold 사용법 : \~\~문장\~\~) </br>

<!-- Line  _ 3번 -->

---

<!-- Quote -->

## Quoto

> Quoto 입니다. <br>
> (Quoto 사용법 : > Quoto)

<!-- Line   -->

---

<!-- Bullet list -->

## List

리스트 :
(사용방법 : \* 리스트1 or - 리스트1)

- 리스트1
- 리스트2

---

<!-- Number List -->

숫자 리스트 :
(사용방법 : 1. 리스트1)

1. 리스트1
2. 리스트2
3. 리스트3

---

## Before release

- [x] List1
- [] List2

---

<!-- Link -->

## Link

Click [link](https://github.com/AnJuHwan/ReadMe_File_Note) </br>
Click link 사용방법 : [link]\(주소입력)

---

<!-- Image -->

## Image

image 태그로 사용 가능 : width 지정가능 <br>
<img src="https://avatars.githubusercontent.com/u/54831033?s=400&v=4" width="200">

![image description](https://avatars.githubusercontent.com/u/54831033?s=400&v=4)
</br>
<br>
image 사용법 : ![image description]\(주소) <br>
img 태그로 사용: \<img src="https://avatars.githubusercontent.com/u/54831033?s=400&v=4" width="200">

---

<!-- Table -->

## Table

왼쪽 정렬 :

| Header | Descripttion |
| ------ | ------------ |
| Cell1  | Cell1        |
| Cell2  | Cell2        |

오른쪽 정렬 :

| Header | Descripttion |
| -----: | -----------: |
|  Cell1 |        Cell1 |
|  Cell2 |        Cell2 |

가운대 정렬 :
| Header | Descripttion |
| :-----: | :-----------: |
| Cell1 | Cell1 |
| Cell2 | Cell2 |

---

## 사용법

왼쪽 정렬 :<br>
| Header | Descripttion | <br>
| :-- | :-- | <br>
| Cell1 | Cell1 |<br>
| Cell2 | Cell2 |<br>

<br>

오른쪽 정렬 : <br>
| Header | Descripttion | <br>
| --: | --: | <br>
| Cell1 | Cell1 | <br>
| Cell2 | Cell2 | <br>

<br>
가운대 정렬 : <br>
| Header | Descripttion | <br>
| :--: | :--: | <br>
| Cell1 | Cell1 | <br>
| Cell2 | Cell2 | <br>

---

<!-- code -->

## Code

이것은 코드 `console.log('hello message');` 입니다. <br>
이것은 text console.log('hello message'); 입니다. <br>

사용법 : \`console.log('aaa);`

---

<!-- Code Block -->

## Code Block

```js
console.log('javascript1');
console.log('javascript2');
```

```h
print('C언어');
```

사용법 :

\```사용 언어 확장자 (ex: js , ts , h , java...) <br>
console.log('javascript1'); <br>
console.log('javascript2'); <br>
\``` <br>
