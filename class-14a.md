# **[ CSS Transforms, Transitions, and Animations ]**

![css](https://miro.medium.com/max/960/1*R2IxrEjMVm6QiRYdEo-lvQ.png)

<hr>

## **#1 [ Transforms ]**

### **What is CSS transforms?**
With CSS3 came new ways to position and alter elements. All of these new techniques are made possible by the transform property.

### **How to use it?**

    div {
    -webkit-transform: scale(1.5);
        -moz-transform: scale(1.5);
        -o-transform: scale(1.5);
            transform: scale(1.5);
    }
Notice how the transform property includes multiple vendor prefixes to gain the best support across all browsers. 

### **What can we do with it?**
We can control many things such as:
* 2D Transforms
* 3D Transforms
* Perspective
* Combination between Transforms
* Styling Transforms

<hr>

## **#1 [ Transitions & Animations ]**
(One evolution with CSS3 was the ability to write behaviors for transitions and animations. With CSS3 transitions you have the potential to alter the appearance and behavior of an element.)

![css](https://freefrontend.com/assets/img/css-animation-examples/css-animation-indoors-or-outdoors.gif)

### **1. Transitions**
For a transition to take place, an element must have a change in state, and different styles must be identified for each state.  uch as when it is hovered over, focused on, active, or targeted.

In the example below the box will change its background color over the course of 1 second in a linear fashion:

    .box {
    background: #2db34a;
    transition-property: background;
    transition-duration: 1s;
    transition-timing-function: linear;
    }
    .box:hover {
    background: #ff7b29;
    }

**What can we manipulate in transitions?** <br>
Well, not all properties are available but some common examples are:
* background-color
* border-width
* border-color
* font-size

(And more that you might find in the source article)

**Transition Duration:** The duration in which a transition takes place is set using the transition-duration property. The value of this property can be set using general timing values, including seconds (s) and milliseconds (ms). These timing values may also come in fractional measurements, .2s for example.

**Transition Timing:** The transition-timing-function property is used to set the speed in which a transition will move. 

### **2. Animations**

When more control is required, transitions need to have multiple states. In return, this is where animations pick up where transitions leave off.

**Animations Keyframes:** To set multiple points at which an element should undergo a transition, use the @keyframes rule. The @keyframes rule includes the animation name, any animation breakpoints, and the properties intended to be animated.

    @keyframes slide {
    0% {
        left: 0;
        top: 0;
    }
    50% {
        left: 244px;
        top: 100px;
    }
    100% {
        left: 488px;
        top: 0;
    }
    }

**Animation Duration, Timing Function, & Delay:**
Once you have declared the animation-name property on an element, animations behave similarly to transitions. They include a duration, timing function, and delay if desired.

    .stage:hover .ball {
    animation-name: slide;
    animation-duration: 2s;
    animation-timing-function: ease-in-out;
    animation-delay: .5s;
    }

* There are many other properties related to animation, don't hesitate to look more into it.

<hr>

Sources:
* [Transforms](https://learn.shayhowe.com/advanced-html-css/css-transforms/#backface-visibility)

* [Transitions & Animations](https://learn.shayhowe.com/advanced-html-css/transitions-animations/)


Additional codes sources:
* [8 simple CSS3 transitions that will wow your users](https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users)

* [6 Buttons animated](https://codepen.io/retyui/pen/ByoaXV)

* [CSS3 Animations: Keyframes](https://codepen.io/akshaychauhan/pen/oAfae)

* [404](https://codepen.io/kieranfivestars/pen/MYdQxX)

* [Pure CSS Bounce Animation](https://codepen.io/dp_lewis/pen/gCfBv)