---
title: kramo
description: "kramo's homepage: projects, links and contact information."
---

<style>
    @keyframes arrow-slide {
        from {transform: translateY(-1em);}
        80% {transform: translateY(-1em); animation-timing-function: ease-in;}
        to {transform: translateY(2em);}
    }

    @keyframes arrow-pulse {
        from {opacity: 0;}
        80% {opacity: 0;}
        90% {opacity: 1;}
    }

    @keyframes animate-path {
        from {stroke-dashoffset: 300;}
        to {stroke-dashoffset: 0;}
    }

    .arrow {
        margin-bottom: -1.5em;
        opacity: 0;
        animation: arrow-slide 4s infinite, arrow-pulse 4s infinite;
    }

    .appear-later {
        opacity: 0;
        animation: appear 0.5s forwards;
    }

    #animated-path {
        stroke-dasharray: 300;
        animation: animate-path 1s forwards;
    }

    /* Firefox doesn't seem to like the SVG animation while the fade in happens */
    body {
        opacity: initial;
        animation: initial;
    }

    img {
        width: 35em;
    }

    @media (prefers-reduced-motion) {
        .arrow {
            animation: appear 5s forwards;
        }
        .appear-later {
            opacity: initial;
            animation: initial;
        }
        #animated-path {
            animation: initial;
        }
    }
</style>

<svg role="img" aria-label="an animated logo of the letter k" id="animated-path" style="margin-top: 15vh;" width="61.95" height="57" fill="none" xmlns="http://www.w3.org/2000/svg">
    <path d="m3.5 3.5 25 25 25-25h-50v23.438L30.063 53.5H53.5l-25-25m-25-25 25 25 25-25h-50v23.438V3.5v23.438V3.5v50h26.563" stroke="var(--fg)" stroke-width="7"/>
</svg>


<h1 class="appear-later" style="animation-delay: 0.7s">kramo</h1>
<p class="appear-later" style="margin-bottom: 20vh; animation-delay: 1.2s;">design & free software</p>

<p class="appear-later" style="animation-delay: 2.5s;">my work</p>

<br>
<p class="arrow" style="animation-delay: .2s;" aria-hidden="true">v</p>
<p class="arrow" style="animation-delay: .1s;" aria-hidden="true">v</p>
<p class="arrow" style="margin-bottom: 35vh;" aria-hidden="true">v</p>

### cartridges

[check out the project](/cartridges/)

[![cartridges](/images/cartridges.webp)](/cartridges/)

<br>
<br>

### app icons

[view icons i designed](/app-icon-design/)

[![app icons](/images/app-icon-design.svg)](/app-icon-design/)

<br>
<br>

### vanilla os wallpapers

[download here](/vanilla-backgrounds/)

[![vanilla os wallpapers](/images/vanilla-default.svg)](/vanilla-backgrounds/)

<br>
<br>

### quick touchpad toggle

[check out the extension](/quick-touchpad-toggle/)

[![quick touchpad toggle](/images/quick-touchpad-toggle.webp)](/quick-touchpad-toggle/)