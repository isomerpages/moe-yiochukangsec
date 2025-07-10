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
    content: '+'; /* This is the chevron icon */
    position: absolute;
    font-size: var(--yck-step-2);
    left: 0.25rem;
    top: 0.85rem;
    transform: translateY(-50%) rotate(0deg); /* Sets the starting rotation */
    transition: transform 0.3s ease-in-out; /* This makes the rotation smooth! */
}

details[open] > summary::before {
    transform: translateY(-50%) rotate(135deg); /* Rotates the icon 90 degrees */
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