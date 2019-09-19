# 2D Animations with CSS3
## Simple 2D CSS3 Animation
### Keywords
**CSS3**

**HTML5**

**SASS**

**animation**: [name] [duration] [timing-funciton] [delay] [iteration-count] [direction] [fill-mode] [play-state]

**@keyframes**: [from] [to] | [0%] [n%] [n+m%] [100%]

**transform**: [property]([value], [value], ...)

**transitions**: 

---

**transform: translate(x, y)**
---
x, y: [px], [em], [rem], [%], [vw], [vh]
> E.g., transform: translate(50px, 25px)

**transform: scale(x, y)**
---
x, y: [n], [n]
> transform: scale(2, 1.5)

**transform: rotate(xDeg, yDeg)**
---
xDeg, yDeg: [deg], [grad], [rad], [turn]
> transform:rotate(30deg, 45deg)

**transform: skew(xDeg, yDeg)**
---
xDeg, yDeg: [deg], [grad], [rad]
> transform: skew(45deg, 0)

**transform: matrix([scaleX(x<sub>1</sub>)], [skewY(y)], [skewX(x)], [scaleY(y)], [translateX(x)], [translateY](y))**
---
> transform: translate(100px, 50px) rotate(-25deg, 30deg) scale(1.5, 0.5) skew(25deg 30deg)
