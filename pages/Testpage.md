---
title: Testpage
permalink: /testpage/
description: ""
variant: markdown
---
<div class="yck-component">
    <figure>
        <div class="masthead" id="schsongbg">
					<details>
						<summary class="yck-h2">YCKSS School Song</summary>
            <p>Our School is Yio Chu Kang.<br>
                Together we learn and grow.<br>
                Pursuit of knowledge, service to all,<br>
                With gratitude and character, we show.<br>
                Wholeheartedly, our Home.</p>
            <p>Through our hopes and dreams,<br>
                We see the best in all.<br>
                With heart and soul, we lead<br>
                And strive for excellence.<br>
                Wholeheartedly, our School.<br>
                Wholeheartedly, our Home.</p>
            <figcaption>Musics &amp; Lyrics by: Mr Michael William Cartwright &amp; Ms Lio Dan Wei
            </figcaption>
					</details>
        </div>
    </figure>
</div>

<style>
:root {
    --yck-text-line-height: 1.6em;
    --yck-heading-line-height: 1.2em;
    --yck-heading-letter-spacing: -0.02em;
    --yck-spacing-unit: 1em;
    --yck-box-shadow: 0 2px 4px rgba(0, 0, 0, 0.25);
    --yck-transition-timing: cubic-bezier(0.4, 0, 0.2, 1);

    --yck-step--2: clamp(0.7813rem, 0.9263rem + -0.1872vw, 0.8889rem);
    --yck-step--1: clamp(0.9375rem, 1.0217rem + -0.1087vw, 1rem);
    --yck-step-0: clamp(1.125rem, 1.125rem + 0vw, 1.125rem);
    --yck-step-1: clamp(1.2656rem, 1.2363rem + 0.1467vw, 1.35rem);
    --yck-step-2: clamp(1.4238rem, 1.3556rem + 0.3412vw, 1.62rem);
    --yck-step-3: clamp(1.6018rem, 1.4828rem + 0.5951vw, 1.944rem);
    --yck-step-4: clamp(1.802rem, 1.6174rem + 0.9231vw, 2.3328rem);
    --yck-step-5: clamp(2.0273rem, 1.7587rem + 1.3427vw, 2.7994rem);

    --yck-space-s-xl: clamp(0.75rem, 0.2143rem + 3.9286vw, 3.75rem);
    interpolate-size: allow-keywords;
    scroll-behavior: smooth;
    text-rendering: optimizeSpeed;
    height: 100vh;
}

::selection {
    text-shadow: none;
    background: yellow;
}

audio,
canvas,
iframe,
img,
svg,
video {
    vertical-align: middle;
}

.yck-component {
    line-height: var(--yck-text-line-height);
    letter-spacing: normal;
    font-size: var(--yck-step-0);
    margin-bottom: var(--yck-space-s-xl);
}

.yck-component h1,
.yck-component h2,
.yck-component h3,
.yck-component h4,
.yck-component h5,
.yck-component h6,
.yck-component p {
    overflow-wrap: break-word;
}

.yck-component h1,
.yck-component h2,
.yck-component h3,
.yck-component h4,
.yck-component h5,
.yck-component h6 {
    text-wrap: balance;
}

.yck-component p,
.yck-component ol,
.yck-component ul {
    text-wrap: pretty;
    margin-bottom: calc(var(--yck-spacing-unit)*1.5);
}

.yck-component p:last-child,
.yck-component ul li:last-child,
.yck-component ol li:last-child {
    margin-bottom: var(--yck-space-s-xl);
}

.yck-component .yck-h1,
.yck-component h1 {
    font-size: var(--yck-step-5);
    margin-bottom: var(--yck-spacing-unit);
    line-height: var(--yck-heading-line-height);
    letter-spacing: var(--yck-heading-letter-spacing);
}

.yck-component .yck-h2,
.yck-component h2 {
    font-size: var(--yck-step-4);
    margin-bottom: calc(var(--yck-spacing-unit) * 0.85);
    text-transform: capitalize;
    line-height: var(--yck-heading-line-height);
    letter-spacing: var(--yck-heading-letter-spacing);
}

.yck-component .yck-h3,
.yck-component h3 {
    font-size: var(--yck-step-3);
    margin-bottom: calc(var(--yck-spacing-unit) * 0.75);
    text-transform: capitalize;
    line-height: var(--yck-heading-line-height);
    letter-spacing: var(--yck-heading-letter-spacing);
}

.yck-component .yck-h4,
.yck-component h4 {
    font-size: var(--yck-step-2);
    margin-bottom: calc(var(--yck-spacing-unit) * 0.5);
    text-transform: capitalize;
    line-height: var(--yck-heading-line-height);
    letter-spacing: var(--yck-heading-letter-spacing);
}

.yck-component .yck-h5,
.yck-component h5 {
    font-size: var(--yck-step-1);
    margin-bottom: calc(var(--yck-spacing-unit) * 0.25);
    text-transform: uppercase;
    line-height: var(--yck-heading-line-height);
    letter-spacing: var(--yck-heading-letter-spacing);
}

.yck-component .yck-h6,
.yck-component h6 {
    font-size: var(--yck-step-0);
    margin-bottom: var(--yck-spacing-unit);
    text-transform: uppercase;
    line-height: var(--yck-heading-line-height);
    letter-spacing: var(--yck-heading-letter-spacing);
}

.yck-component hr,
hr {
    border: 1px dotted rgba(0, 0, 0, 0.25);
    margin-block: clamp(1rem, 2vw, 2.5rem);
}

.yck-component a {
    text-decoration: none;
    color: #e37f2a;
    position: relative;
    padding-bottom: 2px;
}

.yck-component a::after {
    content: '';
    position: absolute;
    width: 0;
    height: 2px;
    bottom: 0;
    left: 0;
    background-color: currentColor;
    transition: width 1s var(--yck-transition-timing);
}

.yck-component a:hover::after {
    width: 100%;
}

.yck-component a:hover {
    text-decoration: none;
}

.yck-component .video-container {
    position: relative;
    width: 100%;
    padding-bottom: 56.25%;
    /* 16:9 aspect ratio */
    height: 0;
    overflow: hidden;
    margin-bottom: var(--yck-spacing-unit);
}

.yck-component .video-container iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}

.yck-component .isomer-card,
.yck-component .column {
    break-inside: avoid;
    /* Prevents content from breaking across columns */
    page-break-inside: avoid;
    /* For older browsers */
    padding: 20px;
    border-radius: 5px;
    box-shadow: var(--yck-box-shadow);
}

.yck-component .yck-flexbox-grid {

    --yck-gap: 1em;
    display: flex;
    flex-wrap: wrap;
    list-style: none;
    gap: var(--yck-gap);
    padding: 0;
    margin-block: var(--yck-spacing-unit);
}

.yck-component .yck-flexbox-grid>* {
    flex-grow: 1;
    flex-shrink: 0;
    flex-basis: calc((100% - var(--yck-gap)) / 4);
    min-width: calc((100% - var(--yck-gap)) / 2);
    list-style: none;
}

@media (max-width:1000px) {
    .yck-component .yck-flexbox-grid>* {
        flex-basis: 100%;
    }
}

.yck-component .yck-flexbox-grid .isomer-card {
    text-decoration: none;
    margin: 0 auto;
    padding: 0;
    border: 1px solid #e0e0e0;
    border-radius: 8px;
    overflow: hidden;
    transition: transform 0.3s var(--yck-transition-timing), box-shadow 0.3s var(--yck-transition-timing);
}

.yck-component .yck-flexbox-grid .isomer-card:hover {
    transform: translateY(-5px);
    box-shadow: var(--yck-box-shadow);
}

.yck-component .yck-flexbox-grid .isomer-card:hover .isomer-card-body .isomer-card-link {
    color: #e37f2a;
}

.yck-component .yck-flexbox-grid .isomer-card .isomer-card-image {
    width: 100%;
    object-fit: cover;
}

.yck-component .yck-flexbox-grid .isomer-card .isomer-card-body {
    padding: var(--yck-spacing-unit);
}

.yck-component .yck-flexbox-grid .isomer-card .isomer-card-body .isomer-card-title {
    color: #4a4a4a;
    font-weight: 700;
    font-size: var(--yck-step-1);
    overflow-wrap: break-word;
    text-wrap: balance;
}

.yck-component .yck-flexbox-grid .isomer-card .isomer-card-body .isomer-card-description {
    color: #484848;
    font-size: var(--yck-step-0);
}

.yck-component .yck-flexbox-grid .isomer-card .isomer-card-body .isomer-card-link {
    font-size: var(--yck-step-0);
    text-decoration: underline;
    color: #e37f2a;
    display: inline-block;
    margin-top: 0.5rem;
}

.yck-component .yck-flexbox-grid .isomer-card .isomer-card-body .isomer-card-title:has(+.isomer-card-description) {
    margin-bottom: 0.75rem
}

.yck-component .yck-flexbox-grid .isomer-card .isomer-card-body .isomer-card-title:has(+.isomer-card-link),
.yck-component .yck-flexbox-grid .isomer-card .isomer-card-body .isomer-card-description:has(+.isomer-card-link) {
    margin-bottom: 1.5rem
}

.yck-component figure {
    display: flex !important;
    flex-flow: column !important;
    max-width: 100%;
    margin: auto !important;
}

.yck-component figure img {
    border-radius: 8px;
    box-shadow: var(--yck-box-shadow);
    margin-bottom: var(--yck-spacing-unit);
}

.yck-component figcaption {
    color: #333;
    font: italic var(--yck-step--1) sans-serif;
    padding: 5px;
    text-align: center;
}

.ken-burns-container {
    max-width: 100%;
    overflow: hidden;
    position: relative;
    border-radius: 8px;
}

.ken-burns-image {
    width: 100%;
    height: 100%;
    object-fit: cover;
    animation: kenBurns 35s ease-in-out infinite alternate;
}

@keyframes kenBurns {
    from {
        transform: scale(1);
    }

    to {
        transform: scale(1.35);
    }
}

.fade-in {
    -webkit-animation: fade-in 1.2s cubic-bezier(0.390, 0.575, 0.565, 1.000) both;
    animation: fade-in 1s cubic-bezier(0.390, 0.575, 0.565, 1.000) both;
}

/**
                             * ----------------------------------------
                             * animation fade-in
                             * ----------------------------------------
                             */
@-webkit-keyframes fade-in {
    0% {
        opacity: 0;
    }

    100% {
        opacity: 1;
    }
}

@keyframes fade-in {
    0% {
        opacity: 0;
    }

    100% {
        opacity: 1;
    }
}

@-webkit-keyframes fade-out {
    0% {
        opacity: 1;
    }

    100% {
        opacity: 0;
    }
}

@keyframes fade-out {
    0% {
        opacity: 1;
    }

    100% {
        opacity: 0;
    }
}

@media (prefers-reduced-motion: reduce) {
    * {
        animation-duration: 0.01ms !important;
        animation-iteration-count: 1 !important;
        transition-duration: 0.01ms !important;
        scroll-behavior: auto !important;
    }
}

@supports (content-visibility: auto) {
    details {
        content-visibility: auto;
    }
}

@supports (animation-timeline: view()) {

    .yck-component .yck-flexbox-grid .isomer-card,
    .yck-component .isomer-card-grid,
    .yck-component .col-container {
        animation: fade-in-bottom linear both;
        animation-timeline: view();
        animation-range: entry 25% cover 50%;
    }
}

details {
    overflow: hidden;
}

details * {
    margin: 0 !important;
}

details>p,
details ul li,
details div {
    animation: fade-in 1s ease-out;
    padding-top: calc(var(--yck-spacing-unit) * 0.5);
}

summary {
    margin-inline-start: 1.5rem !important;
    list-style-position: outside;
    list-style: none;
    cursor: pointer;
    user-select: none;
    outline: none;
    font-size: var(--yck-step-1);
    font-weight: 500;
}

/* A specific rule for Chrome/Safari */
summary::-webkit-details-marker {
    display: none;
}

summary::before {
    content: ''; /* This is the chevron icon */
    position: absolute;
    font-size: var(--yck-step-2);
    left: 0.05rem;
    top: 1.55rem;
	  width: 1.5rem;
	  height: 3rem;
	  background-image: url("data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjEwMCUiIHdpZHRoPSIzMCUiIHZpZXdCb3g9IjAgMCAzMjAgMzIwIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPjxwYXRoIGNsYXNzPSJzdmctZWxlbS0xIiBkPSJNMTQxLjUgMS42MjdjLTM4LjEwMyA1LjczMi02Ny43MjMgMjAuMTIzLTkzIDQ1LjE4My03My41ODEgNzIuOTUtNTguNTYyIDE5NS4yMjggMzAuNSAyNDguMzEgODAuMjU1IDQ3LjgzMyAxODYuMDc0IDE1LjA5MSAyMjQuOTk2LTY5LjYxNyAyNS40OTktNTUuNDk1IDE1LjkwNS0xMjUuNDc4LTIzLjE2OS0xNjkuMDAzLTIuNDY5LTIuNzUtNS4zNTMtNi4wNTMtNi40MDgtNy4zMzktMTEuMDU3LTEzLjQ3OC00Mi4xMTktMzIuOTUyLTY0Ljg0Ni00MC42NTQtMTYuNzk3LTUuNjkyLTUyLjE5Mi05LjI2OS02OC4wNzMtNi44OG03IDcuOTk1Yy00Ny43MzYgNS4wNjktODguMTI4IDI4LjU0MS0xMTIuNzA5IDY1LjQ5Ni01OS43NTUgODkuODM1LTEwLjU4NSAyMDguNjU2IDk1LjYwNSAyMzEuMDMzIDE0LjQ4OCAzLjA1MyA0Mi43MiAzLjA1MyA1Ny4yMDggMCAxMzAuODU4LTI3LjU3NiAxNjUuNDAyLTE5NS40ODYgNTUuNzI0LTI3MC44NjNDMjE3LjczMyAxNy4wMTEgMTc4LjMyNCA2LjQ1NiAxNDguNSA5LjYyMm0tNiAxMS44ODFjLTIyLjAzOCA0LjE2NS00MS44MTcgMTYuNzc1LTU3LjU3MiAzNi43MDhsLTMuODQ4IDQuODY3IDQuNTE5IDcuNjQzYzE4LjAwNSAzMC40NTUgNDIuODg1IDQ1LjYxOSA3NC45MDEgNDUuNjUxIDMyLjI5NC4wMzMgNTYuNzkxLTE2Ljc3OSA3Mi42Ny00OS44NzFsNC4xNDEtOC42MjktNS45MDYtNi4wMzFjLTE4LjU4Mi0xOC45OC0zNy44ODItMjguNTAyLTYzLjUwMi0zMS4zMjlsLTUuNTk2LS42MTgtLjY1NCA5LjIwN2MtLjM1OSA1LjA2My0uNjYgMTcuMTI1LS42NjggMjYuODAzLS4wMiAyMi40OTktMS40NjcgMjUuMjI2LTIuMzQgNC40MDYtLjM2NC04LjY5NS0uOTQ5LTIxLjMyMy0xLjMtMjguMDZMMTU2LjcwOCAyMGwtMy42MDQuMDljLTEuOTgyLjA1LTYuNzU0LjY4Ni0xMC42MDQgMS40MTNtODQgODMuOTc1Yy00NC4xMjcgMzEuNjctODkuMjcgMzIuMDI1LTEzNS41MjMgMS4wNjctNC41NjQtMy4wNTYtOC4zODEtNS40NDEtOC40OC01LjMtMi45MzggNC4xNDktOS43MDggMTkuMTM1LTguNzkyIDE5LjQ2MiA5LjkzOCAzLjU0NCA0MS4zNzIgMjYuMjUxIDU0LjMxOSAzOS4yMzkgMTcuOTMyIDE3Ljk4OCAyNC45MTMgNDAuMzEgMjQuOTU4IDc5LjgwNEwxNTMgMjU2aDIwLjg1NGwtLjU2OC0xMi43NzdjLTEuMDA5LTIyLjcgMi43MTUtNDkuNDIyIDkuMDY5LTY1LjA1OCA0Ljg3OS0xMi4wMDggMTcuNTA1LTI3LjI5NiAzMy4xNTEtNDAuMTQyIDYuNzk1LTUuNTc5IDI5LjU2Mi0yMS41NDYgMzEuNzczLTIyLjI4MyAxLjAyNy0uMzQyLTkuOTYxLTE2Ljc1MS0xMS4yMDQtMTYuNzMxLS4zMTYuMDA1LTQuNjI1IDIuOTE2LTkuNTc1IDYuNDY5bTMyLjIxMSAzMC4wNjNjLTM4LjM2MyA2LjA1OC02Ni44MzQgMzMuNDQxLTcxLjc4NiA2OS4wNDMtMi42MTMgMTguNzg2IDMuNTM3IDQwLjE2MyAxNy4yOTYgNjAuMTIyIDYuNzk1IDkuODU2IDYuNDkgOS42ODMgMTMuNzI0IDcuODA4IDI0LjQ3NS02LjM0MiA0OC4zNzMtMjMuNDkgNTkuNDMxLTQyLjY0M2wyLjY3Mi00LjYyOS0yMy43NzQtMTMuMjljLTM0LjE1MS0xOS4wOTEtMzMuODIzLTE5LjM0MiAyLjY1NC0yLjAzIDE3LjUyOSA4LjMxOSAyMy42MzUgMTAuNzk5IDI0LjI0NiA5Ljg0OC40NDktLjY5OCAxLjc1Ni0zLjc0NSAyLjkwNC02Ljc3IDguNjAzLTIyLjY3NSA3LjYzOS00Ni41NTEtMi45MDMtNzEuOTQxbC0yLjcyNC02LjU1OS02LjQ3Ni0uMTczYy0zLjU2MS0uMDk2LTEwLjQzLjQ1MS0xNS4yNjQgMS4yMTRtLTIxNi41NzggNS44OTJjLTExLjQ1MyAyNS44OTEtMTIuNzk3IDUxLjI4LTMuOTA3IDczLjgxNyAxLjY4MSA0LjI2MiAzLjQ3MiA3Ljc1IDMuOTc5IDcuNzUuOTg3IDAgNC40MTgtMS41NDggMjMuMjk1LTEwLjUxIDI0LjI2Ni0xMS41MiAyNi43MDYtMTIuNjE3IDI3LjEyNy0xMi4xOTcuMjM2LjIzNy0yLjYyMSAyLjA3LTYuMzQ5IDQuMDc1QzgyLjU1IDIwNi4zNzMgNzQuNzc1IDIxMC43MDcgNjkgMjE0Yy01Ljc3NSAzLjI5My0xMy41MzggNy42MjEtMTcuMjUgOS42MTctNy44NyA0LjIzMy03Ljg3IDQuMjM0LTMuMDgyIDExLjM5NiA4Ljg4NSAxMy4yOTEgMjEuNzc1IDI0LjU2MiAzNi4xNTMgMzEuNjEyIDkuNjQxIDQuNzI4IDIyLjgzOCA5LjM3NSAyNi42MjIgOS4zNzUgNC42OTYgMCAxNy44NDMtMjEuMTg3IDIzLjI2OS0zNy41IDMuODA5LTExLjQ0NyA0LjAwMy0zMi40NDIuMzk4LTQzLTExLjk1Ni0zNS4wMjEtNDAuOTEyLTU2LjE1Mi03OS43NS01OC4xOTlsLTExLjE0LS41ODctMi4wODcgNC43MTkiIHN0cm9rZT0iI2VmNTYyZCIgZmlsbC1ydWxlPSJldmVub2RkIiBmaWxsPSIjZWY1NjJkIj48L3BhdGg+PHBhdGggY2xhc3M9InN2Zy1lbGVtLTIiIGQ9Ik0xNDYgMS42MzljLTEuMzc1LjIwMi01Ljg3NS44NS0xMCAxLjQ0Qzc0LjUwMSAxMS44NzMgMjIuMTk0IDU5LjAyNCA3LjAwMSAxMTkuMzY0LTIyLjcxOSAyMzcuMzk0IDgzLjE0OCAzNDEuOTYzIDIwMS41IDMxMS40OGM0Ny44ODctMTIuMzM0IDg5LjA1OC00OS45NzcgMTA2Ljg5NC05Ny43MzYgMTIuMDAzLTMyLjE0MSAxMi42OS02OS44OTcgMS44OTctMTA0LjI0NC0xNS40NjktNDkuMjI0LTU5LjkzOS05MC42NTUtMTExLjA3LTEwMy40ODFDMTgyLjkwMiAxLjkyNiAxNTguMDA2LS4xMjMgMTQ2IDEuNjM5bS05LjM4MiA5LjAwNkM3Ni43NDcgMTkuMjk5IDI4LjM4NCA2NC43ODIgMTIuODk0IDEyN2MtMy4yMDkgMTIuODktMy41MjMgNDguNjMxLS41NCA2MS41IDE3LjI5NCA3NC42MDcgNzguMTc3IDEyMi41ODYgMTUyLjUyMiAxMjAuMTk2IDcwLjQ3Mi0yLjI2NiAxMjYuMzM1LTQ5LjI5NiAxNDIuNzctMTIwLjE5NiAzLjE1Mi0xMy42MDEgMi42OTEtNDguNjc1LS44MjMtNjIuNTFDMjg2Ljg2IDQ3LjM3OSAyMTUuNzcyLS43OTYgMTM2LjYxOCAxMC42NDVtOTQuODgyIDkxLjdjLTUuNjQ5IDQuNjY5LTIwLjU2NyAxMy41NjctMzAgMTcuODk0LTM1LjQ4NyAxNi4yNzgtNzEuNTI1IDEyLjA4Mi0xMDkuNzg5LTEyLjc4My00LjgzNC0zLjE0MS04LjkyMi01LjU0MS05LjA4NS01LjMzNC0uMTYzLjIwOC0yLjM5NyA0LjI3NC00Ljk2MyA5LjAzNWwtNC42NjcgOC42NTcgNi43NTIgMy43MDljMjcuOTg2IDE1LjM3MSA1NC43ODQgMzguOTE2IDYyLjYyMyA1NS4wMjQgNy4zMzQgMTUuMDY5IDEwLjk0MiAzNS4yIDExLjA1OSA2MS43MDNsLjA3IDE1Ljc1IDEwLS4wMDIgMTAtLjAwMS4wMTktMjIuMjQ4Yy4wNDEtNDguMzQzIDkuMTUxLTY5LjEyNCA0Mi4zNC05Ni41ODMgNi40MjktNS4zMTkgMjEuNTAzLTE1Ljc3NiAyOC4zODUtMTkuNjlsMy43NDQtMi4xMjktNS43NDQtOC4xNTdjLTYuNjc1LTkuNDc4LTUuNjgxLTkuMDMtMTAuNzQ0LTQuODQ1IiBzdHJva2Utd2lkdGg9IjMiIHN0cm9rZT0iIzBhNTMyYyIgZmlsbC1ydWxlPSJldmVub2RkIiBmaWxsPSIjMGE1MzJjIj48L3BhdGg+PC9zdmc+");
            background-repeat: no-repeat;
            background-position: center;
	
    transform: translateY(-50%) rotate(0deg); /* Sets the starting rotation */
    transition: transform 0.3s ease-in-out; /* This makes the rotation smooth! */
}

details[open] > summary::before {
    transform: translateY(-50%) rotate(450deg); /* Rotates the icon 90 degrees */
}

details::details-content {
    font-size: var(--yck-step-0);
    padding-left: 1.5rem;
    height:  0;
    transition:
        height 1s cubic-bezier(0.390, 0.575, 0.565, 1.000),
        content-visibility 1s cubic-bezier(0.390, 0.575, 0.565, 1.000);
    transition-behavior: allow-discrete;
}

details[open]::details-content {
    height: auto;
}

.fade-in {
    -webkit-animation: fade-in 1.2s cubic-bezier(0.390, 0.575, 0.565, 1.000) both;
    animation: fade-in 1s cubic-bezier(0.390, 0.575, 0.565, 1.000) both;
}

/**
 * ----------------------------------------
 * animation fade-in
 * ----------------------------------------
 */
@-webkit-keyframes fade-in {
    0% {
        opacity: 0;
    }

    100% {
        opacity: 1;
    }
}

@keyframes fade-in {
    0% {
        opacity: 0;
    }

    100% {
        opacity: 1;
    }
}

@-webkit-keyframes fade-out {
    0% {
        opacity: 1;
    }

    100% {
        opacity: 0;
    }
}

@keyframes fade-out {
    0% {
        opacity: 1;
    }

    100% {
        opacity: 0;
    }
}
	
.masthead {
    display: flex;
    justify-content: center;
    align-items: flex-start;
    flex-direction: column;
    text-align: left;
    width: 100%;
    min-width: 500px;
    height: 75vh;
    /* if you don't want it to take up the full screen, reduce this number */
    overflow: hidden;
    background-size: cover !important;
    margin: 0 auto;
    padding: var(--yck-spacing-unit);

}

#schsongbg {
    background: linear-gradient(to left, rgba(255, 255, 255, 1) 0%, rgba(255, 255, 255, 0.6) 37%, rgba(255, 255, 255, 0.45) 60%, rgba(255, 255, 255, 0.85) 80%, rgba(255, 255, 255, 1) 100%), url(https://staging-lite.d3o5f2eggdqz6.amplifyapp.com/images/Our%20Story/School%20Song/Sch_SongBG.png) no-repeat center center scroll;
}

.masthead h2 {
    font-style: normal;
    font-weight: 700;
    color: #333;
    letter-spacing: 0.03em;
    font-size: var(--yck-step-4);
    text-shadow: 1px 2px 4px rgba(24, 24, 24, 0.5);
}

.masthead p {
    font-style: normal;
    font-weight: 500;
    color: #444;
    font-size: var(--yck-step-2);
    letter-spacing: 0.03em;
    line-height: 1.5;
    text-shadow: 1px 2px 2px rgba(24, 24, 24, 0.25);
}
</style>