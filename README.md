# 15_Lesson

#nav-icon4 {
width: 60px;
height: 45px;
position: relative;
margin: 30px auto;
transform: rotate(0deg);
transition: .5s ease-in-out;
cursor: pointer;
}
#nav-icon4 span {
display: block;
position: absolute;
height: 9px;
width: 100%;
background: #337AB7;
border-radius: 9px;
opacity: 1;
left: 0;
transform: rotate(0deg);
transition: .25s ease-in-out;
}
#nav-icon4 span:nth-child(1) {
top: 0px;
transform-origin: left center;
}
#nav-icon4 span:nth-child(2) {
top: 18px;
transform-origin: left center;
}
#nav-icon4 span:nth-child(3) {
top: 36px;
transform-origin: left center;
}
#nav-icon4.open span:nth-child(1) {
transform: rotate(45deg);
top: -3px;
left: 8px;
}
#nav-icon4.open span:nth-child(2) {
width: 0%;
opacity: 0;
}
#nav-icon4.open span:nth-child(3) {
transform: rotate(-45deg);
top: 39px;
left: 8px;
}

HTML код

?
1
2
3
4
5

<div id="nav-icon4">
    <span></span>
    <span></span>
    <span></span>
</div>
