[Street Light](https://iamodh.github.io/street-light/)
=

> PC

![street-light-pc](https://github.com/iamodh/welcome-page/assets/68431235/81523c00-1c71-4f30-a7d2-dd892e24c331)

> Mobile

![street-light-mobile](https://github.com/iamodh/welcome-page/assets/68431235/465d7a9e-40b8-4496-85d3-fb327393eab2)

## Table of Contents
- [Built with](#built-with)
- [Project](#project)
- [Features](#features)

## Built with
### Front-end
- `HTML`
- `CSS`

## project    
> 1. Animations
- `light` element는 `height` 값을 0인 상태에서 boredr값을 조정해 삼각형 형태로 만들었습니다.
```Javascript
// div를 삼각형 형태로 스타일
.light {
  width: 0px;
  height: 0;
  border-left: 240px solid transparent;
  border-right: 80px solid transparent;
  border-bottom: 280px solid #f3e8c5;
}
```
- `lightFlickering` keyframe에서 `opacity`를 조정해 `animation`을 설정했습니다.
- 도로 표시선들을 가지고 있는 `lines` 컨테이너를 위치에 맞게 `tarnslate` 후 배경과의 `z-index`값을 조정하여 표시선이 무한이 이동하는 것처럼 보이도록 만들었습니다.
> 2. Responsive Web
- 화면의 `max-width` 값이 600px 이하가 될 때 element들의 위치를 수정하는 media query를 제작하였습니다.

## Features
- [x] Web Design
- [x] Animation

