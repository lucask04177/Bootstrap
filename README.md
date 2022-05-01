# Bootstrap
Wow Finally Bootstrap
<4/30 ~ 5/1>
일단은 CSS 뽀개기 먼저하고 하기
(레이아웃을 먼저 다 확실히 잡은 후 진행)

Float -> clear both



<Shadow Dom CSS edit -> -webkit-appearnce : none; 이 들어가야 적용됨
  혹은 html 태그에 <style></style> 적용

input[type=range] {
    -webkit-appearance: none;
}

input[type=range]::-webkit-slider-thumb {
    background-color: red;
    appearance: none;
    width: 50px;
    height: 50px;
    -webkit-appearance: none;
}
