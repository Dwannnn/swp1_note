swp1_note
20150910.md

<br>줄 띄우기
div는 특정 부분을 감싸는 투명한 막과 같다. div를 이용해서 css을 효율적으로 사용할 수 있음
class는 종료, id는 고유한 이름임
한 태그는 하나의 id, 여러 class를 가질 수 있다
div는 특정 부분을 지정하는 거라고 하면, class/id는 특정 부분을 지정하기보다 카테고리를 만들어서 관리하기 위한 용도라고 볼 수 있다
css 관리 :  class는 앞에 . / id는 앞에 #
link : html파일에서 외부 파일 불러올 때 사용
rel=“stylesheet” : css파일 불러오는 것
media=“all” 모든 디바이스에서 불러올 때 사용
href=“css/style.css” 불러올 파일의 경로
#시멘틱 태그
바디 안에 <header> : 상단 제목 달 때
padding : 내부 여백
<footer> 하단 꼬리말 같은거
<nav> 네비게이션 사이트 메뉴 역할
*css:overflow 영역을 벗어나는 요소들을 어떻게 보여줄 것인지
float : text-align과 비슷한데, 텍스트가 아니라 요소 자체를 정렬함
nav랑 section이 나뉘어 있는데 여백이 왜 있지?
h1에 기본 padding이 깔려 있기 때문임 -> id 지정해서 margin
블록:한줄다(문장에서 독립) vs 인라인:단어만(문장에 소속된 상태로)
b, strong 볼드체 / i, em 이탤릭체 - 후자가 웹표준
span 이름표 역할
->외부 스타일시트에서 class(ex. red)만들어서 span에 적용시티는 방식으로 사용
a href 에서 target=“_blank” 넣으면 새 탭에서 띄움
ol은 순서O / ul은 순서X / li는 한줄 
ol,ul 속성 설정 가능 ex. A, a, I, i, 1 / disc, circle, square
<a href=“#li-tag”>를 통해서 클릭시 그쪽으로 이동할 수 있음 id가 여러개면 어떡함??
input type=“radip” : 선택 
select 선택2
background: url(“~~”) no-repeat; -> 영역초과시 바둑판식배열 방지
background: cover
box-sizing : padding, margin 등의 간섭 방지
font-weight : 폰트굵기
opacity : 0.5 = 50%
hover -> .class:hover {~~~}
@media (max-width: 768px) { .content {width: 100%;}}
->반응형 웹

githubㅡㅡ 
git는 추가한 부분만 저장
git init 
git status 
RE tab 자동완성
git이 아직 안쫓고있다는 상태 : untracked 
git add ~~파일명 -> 쫓기 시작함
git commit -m “아무거나” -> 
git log

github는 웹하드라고 생각하면댐

git remote add origin https://github.com/Dwannnn/swp1_note.git
git push -u origin master

git add . 추가된 파일 쫓기 시작
git status 상태
git commit -m “~~” 제목 
git push 웹에 넣기



