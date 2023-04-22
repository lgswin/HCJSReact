## 선택자 우선순위
```
9999999..점 div {color: red !important} = 왠만하면 피해주어야 함
100점 #color_yellow {color: yellow;}
10점 .color_green {color: green}
1점 div {color: blue;}
0점 * {color: darkblue}
X점 body {color: violet}
21점 .list li.item {color: red;}
21점 .list li:hover {color: red;}
11점 .box::before {content: "Good"; color: red;}
101점 #submit span {color: red;}
22점 header .menu li:nth-child(2) {color: red;}
1점 h1 {color: red;}
10점 :not(.box) {color: red;}
1000점 inline css  = 왠만하면 피해주어야 함
```