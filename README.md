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

Applying scale, skew, translate transforms can be replaced using the matrix() transform.

**transform: matrix([scaleX(x<sub>1</sub>)], [skewY(y<sub>2</sub>)], [skewX(y<sub>x</sub>)], [scaleY(<sub>y1</sub>)], [translateX(x<sub>3</sub>)], [translateY(y<sub>3</sub>)])**
---
If you need to apply multiple transforms including the **rotate()** transform, specify each one individually:
> transform: translate(100px, 50px) rotate(-25deg, 30deg) scale(1.5, 0.5) skew(25deg 30deg)
