---
permalink: /tests/
title: "Tests"
---

:root{
    --color1: #117D83;
    --color2: #076769;
}
.main-timeline{ font-family: 'Poppins', sans-serif; }
.main-timeline:after{
    content: '';
    display: block;
    clear: both;
}
.main-timeline .timeline{
    width: 50%;
    padding: 0 70px 0 0;
    margin: 0 5px 15px 0;
    float: left;
}
.main-timeline .timeline-content{
    color: #999;
    background: var(--main-color);
    min-height: 120px;
    padding: 0 30px 0 0;
    border-right: 2px solid var(--color1);
    display: block;
    position: relative;
    z-index: 1;
}
.main-timeline .timeline-content:hover{ text-decoration: none; }
.main-timeline .timeline-content:before,
.main-timeline .timeline-content:after{
    content: '';
    background-color: var(--color2);
    height: 8px;
    width: 8px;
    border-radius: 50%;
    position: absolute;
    right: -5px;
    top: 0;
}
.main-timeline .timeline-content:after{
    top: auto;
    bottom: 0;
}
.main-timeline .timeline-icon{
    color: #fff;
    background-color: var(--color1);
    font-size: 40px;
    text-align: center;
    line-height: 93px;
    height: 93px;
    width: 93px;
    border-radius: 30px;
    box-shadow: -5px -5px 5px rgba(0,0,0,0.2), -8px -8px 0 var(--color2);
    transform: translateY(-50%);
    position: absolute;
    right: -120px;
    top: 50%;
}
.main-timeline .timeline-year{
    font-size: 32px;
    font-weight: 300;
}
.main-timeline .title{
    color: var(--color1);
    font-size: 20px;
    font-weight: 600;
    letter-spacing: 1px;
    text-transform: uppercase;
    margin: 0 0 7px;
}
.main-timeline .description{
    color: #444;
    font-size: 13px;
    font-weight: 500;
    line-height: 21px;
    letter-spacing: 0.5px;
    margin: 0;
}
.main-timeline .timeline:nth-child(even){
    padding: 0 0 0 70px;
    margin: 0 0 15px 5px;
    float: right;
}
.main-timeline .timeline:nth-child(even) .timeline-content{
    padding: 0 0 0 30px;
    border-left: 2px solid var(--color1);
    border-right: none;
}
.main-timeline .timeline:nth-child(even) .timeline-content:before,
.main-timeline .timeline:nth-child(even) .timeline-content:after{
    right: auto;
    left: -5px;
}
.main-timeline .timeline:nth-child(even) .timeline-icon{
    box-shadow: 5px -5px 5px rgba(0,0,0,0.2), 8px -8px 0 var(--color2);
    left: -120px;
    right: auto;
}
.main-timeline .timeline:nth-child(2){
    --color1: #D31C4C;
    --color2: #B11042;
}
.main-timeline .timeline:nth-child(3){
    --color1: #EC431C;
    --color2: #C83011;
}
.main-timeline .timeline:nth-child(4){
    --color1: #2486D9;
    --color2: #1D6CAE;
}
@media screen and (max-width:767px){
    .main-timeline .timeline,
    .main-timeline .timeline:nth-child(even){
        width: 100%;
        padding: 115px 0 0;
        margin: 0 0 50px;
    }
    .main-timeline .timeline-content,
    .main-timeline .timeline:nth-child(even) .timeline-content{
        text-align: center;
        padding: 15px 0 0 0;
        border: none;
        border-top: 2px solid var(--color1);
    }
    .main-timeline .timeline-content:before{
        right: auto;
        left: 0;
        top: -5px;
    }
    .main-timeline .timeline-content:after,
    .main-timeline .timeline:nth-child(even) .timeline-content:after{
        left: auto;
        right: 0;
        top: -5px;
    }
    .main-timeline .timeline-icon,
    .main-timeline .timeline:nth-child(even) .timeline-icon{
        transform: translateY(0) translateX(-50%);
        top: -115px;
        left: 50%;
    }
}