---
share: "true"
frontmatter: 이게 정식 제목이 되는거다.
---

# 이 파일은 draft 에 있는 파일이다. 


그럼 이렇게 글자를 입력하고
그냥 엔터만 쳤는데 다음칸으로 넘어갔나??
그러면 이제 두칸을 넘겨보자..   
이러면 되나?? 

### #ShortCut
> checkBox :  CMD + L

| `[[somenote#가고싶은 헤딩이름]]`  | 가고 싶은 헤딩으로 링크 걸때                                               |
| --------------------------------- | -------------------------------------------------------------------------- |
| `[[somenote^가고싶은 블럭선택]]`  | 가고 싶은 블럭을 링크걸때, 임베딩도 가능 와우!, `^f41dd4` 이 형식으로 입력 |
| `[[somenote#^my-own-block_name]]` | 이렇게 넣을 수도 있다.                                                     |
| ctrl + hovering                   | 링크의 내용 볼 수 있다.                                                    |
| `[[^^가고싶은 블럭선택]]`         | 모든 곳에서 가고 싶은 블럭 선택.. 근데 이건 좀 찾기가 힘들 듯.             |

| cmd + P                          | 명령어                                  |
| -------------------------------- | --------------------------------------- |
| shift + cmd + K                  | delete current line                     |
| ctrl + enter                     | Bullet List or - 기호                   |
| >                                | 인용, 요약정리                          |
| cmd + B                          | bold                                    |
| cmd + H                          | highlight                               |
| cmd + L                          | checkbox                                |
| ==ctrl + L==                     | ==link 페이지==                         |
| ~~cmd + E~~                      | ~~reading mode~~                        |
| shift + ctrl + Enter             | Numberred List                          |
| ==cmd + enter or click==         | ==Tag 다 보여줌==                       |
| cmd + O                          | 노트 찾기                               |
| shift + cmd + F                  | 찾기                                    |
| ==optn + cmd + ← or →==          | ==이전 페이지==                         |
| cmd + 1 or 2                     | 해당 줄이나 블록을 위아래로 swapping    |
| ==ctrl + option + cmd + ↑ or ↓== | ==a Whole FOLDing==                     |
| ==optn + cmd + ↑ or ↓==          | ==paragraph Folding==                   |
| ==cmd + F11==                    | ==open in Headings mode (괭장히 유용)== |
| cmd + F10                        | open review                             |
| cmd + shift + D                  | advanced table pane                     |
| ==F12==                          | ==디렉토리==                            |
|                        | 테이블 만든다.(알지?)                      |

___

### Function
- 폰트 사이즈 변경할 때 
```html
  Hello <small>world</small>, how are <big>you?</big>
```
```html
<font size=6>xxx</font>
<sup></sup> <sub>/</sub>
```
- 내용 삽입 원할 때 : ! 과 함께 링크노트 넣기
- [[MetaData|MetaData]]
- Graph View 에서 filters 에서 선택하면 그것만 나오는데 맨앞에 '-' 를 붙이면 그거만 빼고 나온다. 
  ex) ==-file:Programming==, -path:Journal
- 기억하자. Hash [[Tag|Tag]] 는 Grouping 하기 위함이다. 
- 이미지 & 웹링크 복붙 가능, 아이패드로 그려서도 넣자. 
- Local Graph 명령어에서 찾아서 Pane 가능
- 코드블럭 넣는 건 [Prism 방식을 사용한다. 해당 링크에서 언어 확인](https://prismjs.com/#supported-languages)  
- 주석은 %%  이 주석은 Preview 에서 안보인다. %%
- 폴딩(Folding) 가능하다. 
- 노트를 Merge, Extract 할 수 있다. 
- Horizontal Line : __ 세번넣기
- 수식 입력 $ 두개 혹은 $ 네개 사이
- Diagram, 수식 입력, 
- `// 두개로 코드 입력`
- ` 2개로 코드 입력, 3개로 코드 블럭

	| name   | age |     address      |
	| ------ | --- |:----------------:|
	| 이성림 | 52  | 36 MayLand Trail |
	| 김기옥 | 76  | 20 WestLodge Ave |

- callout (마이크로 소프에서 영감 받았다고..)
  question, Warning, Failure, Danger, Bug, Example, Quote,  - + 넣으면 폴딩되고, 

> [!Bug] 이렇게 바로 넣으니깐 아이콘과 제목처럼 들어가네..

> [!INFO]-
  > Here's a callout block. 
  > It supports **Markdown**, [[Internal link|Wikilink]], and [[Embed files|embeds]]!  
  > ![[Pasted image 20230204100840.png|200]]
  
>[!note]+
>Here's a callout block. 
  > It supports **Markdown**, [[Internal link|Wikilink]], and [[Embed files|embeds]]!  
  > ![[Pasted image 20230204100840.png|30]]

>[!abstract]
___

>[!todo]

>[!tips]

>[!question]

>[!Warning]

>[!Failure]

>[!Danger]

>[!Bug]

>[!Example]

>[!Quote]

> [!menu] menu  
>> [!edit] edit  
>>> [!set default properties] set Default Properties, copy Properties, edit Properties
>>> 오른쪽 패널의 수정된 값을 기본값으로 만든다.


#### Search, Query, Inline Search Result
[Obsidian Help for Search & Query](https://help.obsidian.md/Plugins/Search)

##### content search
> 찾기에서 "selected text" 를 찾고 싶을 때, 반드시 이중 따옴표를 사용
```md
content: "selected text"
```


### Plug-In
- Highlightr : <mark style="background: #FF5582A6;">하이라이터</mark>
- Advanced Tables
- Annotator : 
- Anki : 
- Quick Switcher ++ 
- Spaced Repetition : 퀴즈처럼 기억하도록 도와준다. setting 에서 해시태그 확인
  
  Space Repetion 은 뭐하는 플러그인인가?:: 퀴즈
<!--SR:!2023-02-07,3,250-->
  Quick Switcher++ 는 뭐하는 플러그인인가?:: 헤더로 찾기
<!--SR:!2023-02-07,3,250-->
- FlashCard
- DataView : database  [링크](https://www.youtube.com/watch?v=LyOIvoHtRCM&t=491s)
- mindMap :
-  kanban board : 
- dictionary :  
- calendar :  
- admonition :  
- sync : ICloud 말고 Dropbox 로도 할 수 있다고???, 이건 유료, 
- Text Expander
- calendar :  [링크](https://www.youtube.com/watch?v=W7kTtn9empU&t=7s) 
- fancy calendar  
- Editor Syntax Highlight :  
- Outliner : 
- Periodic Note : 
- Obsidian Publish : 
- Readwise Official : 
- Templater :  

- 웹사이트 iframe 을 통해 embed 할 수 있다. 
<iframe src="http://www.lkpc.org"></iframe>
 
 - Youtube iframe 방법은 조금 다르다. 
<iframe src="https://www.youtube.com/embed/vStUKrOEuRc"></iframe>

 - [TwitFrame](https://twitframe.com) 을 사용하면 embed 를 할 수 있다. 

- image 넣는 방법 : "|" 를 이용해서 사이즈도 줄 수 있다. 
  ![Engelbart|300](https://history-computer.com/ModernComputer/Basis/images/Engelbart.jpg)

- local image 넣는 방법 : 그냥 이름 넣으니깐 바로 찾아지네..
  ![[Pasted image 20230204100840.png|200]]
 
 ___
 

### Appearance
- #### Theme 
	gruvbox : 

### Metadata
![](https://i.imgur.com/UkVpnb0.png)
#### Sample
```metadata
---
# Mandatory fields
id: "463c42d2-82e6-458e-8864-000e829c56fb"
# Optional fields
title: ""
tags: []
source: "https://www.youtube.com/watch?v=jAPn6yqrDxQ&t=4s"
source_title: "(602) ✨ How to use Obsidian MD, the *BEST* 2023 Studying and Note Taking App for Students and University✨ - YouTube"
source_description: "🎓 Revolutionize your school note taking and learning https://shop.johnmavrick.com/obsidian-university📃Get my FREE 4-part Obsidian beginner course with 20+ ..."
source_image_url: "https://i.ytimg.com/vi/jAPn6yqrDxQ/maxresdefault.jpg"
created_date: "2023-07-17"
modified_date: "2023-07-17"
deleted: true
---


```


### Templete


### Link
- [Obsidian Task Study](https://obsidian-tasks-group.github.io/obsidian-tasks/queries/filters/#dates)
- [Obsidian Publish Alternative - Markbase](https://www.reddit.com/r/ObsidianMD/comments/vkx33f/building_markbase_1_a_nontechnical_obsidian/) ⭐️⭐️⭐️⭐️⭐️ 
   [Markbase 도움말](![](https://i.imgur.com/Y0qpdS8.png))
- [FlowerShow.com](https://flowershow.app/) ⭐️⭐️⭐️⭐️⭐️
- [tally.so](https://tally.so/) 이런것도 있네.. obsidian 이 아예 필요없이 웹상에서 다 할 수 있네..


### Sync Error
> ICloud Sign out 해주고 다시 들어가니깐 된다. 
> 1. [Apple's System Status Page](https://www.apple.com/support/systemstatus/) 통해서 서비스가 이용가능한지 체크먼저 한다. 

#### Icloud 동기화 체크
```
killall bird
// 이런 간단한 방법이 있다니..
```
