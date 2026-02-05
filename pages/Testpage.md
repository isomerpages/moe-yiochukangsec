---
title: Testpage
permalink: /testpage/
description: ""
variant: markdown
---
<div class="yck-component">
	<div class="regular-flow">
		<article>
			<section>
<div class="card">
  <div class="gradient"></div>
  <p class="title">Key Personnel In-Charge</p>
  <p class="label">
    Subject Head<br>Student Leadership &amp; Student Well-Being
  </p>
  <div class="ico">
    <div>
      Mr Chen Weiguo Jeremy (Ext: 149)
    </div>
  </div>
</div>
			</section>
		</article>
	</div>
</div>

<style>
	/* ==========================================================================
   1. Custom Props
========================================================================= */

:root {
    --font-antique:
        Superclarendon, Bookman Old Style, URW Bookman, URW Bookman L, Georgia Pro, Georgia, serif;
    --font-classical-humanist:
        Optima, Candara, Noto Sans, source-sans-pro, sans-serif;
    --font-didone:
        Didot, Bodoni MT, Noto Serif Display, URW Palladio L, P052, Sylfaen, serif;
    --font-geometric-humanist:
        Avenir, Montserrat, Corbel, URW Gothic, source-sans-pro, sans-serif;
    --font-handwritten:
        Segoe Print, Bradley Hand, Chilanka, TSCu_Comic, casual, cursive;
    --font-humanist:
        Seravek, Gill Sans Nova, Ubuntu, Calibri, DejaVu Sans, source-sans-pro,
        sans-serif;
    --font-industrial:
        Bahnschrift, DIN Alternate, Franklin Gothic Medium, Nimbus Sans Narrow,
        sans-serif-condensed, sans-serif;
    --font-monospace-code:
        Dank Mono, Operator Mono, Inconsolata, Fira Mono, ui-monospace, SF Mono,
        Monaco, Droid Sans Mono, Source Code Pro, Cascadia Code, Menlo, Consolas,
        DejaVu Sans Mono, monospace;
    --font-monospace-slab-serif: Nimbus Mono PS, Courier New, monospace;
    --font-neo-grotesque:
        Inter, Roboto, Helvetica Neue, Arial Nova, Nimbus Sans, Arial, sans-serif;
    --font-old-style:
        Iowan Old Style, Palatino Linotype, URW Palladio L, P052, serif;
    --font-rounded-sans:
        ui-rounded, Hiragino Maru Gothic ProN, Quicksand, Comfortaa, Manjari,
        Arial Rounded MT, Arial Rounded MT Bold, Calibri, source-sans-pro,
        sans-serif;
    --font-slab-serif:
        Rockwell, Rockwell Nova, Roboto Slab, DejaVu Serif, Sitka Small, serif;
    --font-system-ui: system-ui, sans-serif;
    --font-transitional: Charter, Bitstream Charter, Sitka Text, Cambria, serif;
    /* Neutral */
    --neutral-100: #fcfcfa;
    --neutral-200: #eae8e4;
    --neutral-300: #d7d3ce;
    --neutral-400: #c5bfb9;
    --neutral-500: #b3aba4;
    --neutral-600: #8f8883;
    --neutral-700: #6c6663;
    --neutral-800: #494442;
    --neutral-900: #262322;
    /* Accent: Algal Fuel */
    --yck-green100: #f2fffb;
    --yck-green200: #bcfee6;
    --yck-green300: #83f8c7;
    --yck-green400: #4ae79d;
    --yck-green500: #16c768;
    --yck-green600: #079f45;
    --yck-green700: #02772b;
    --yck-green800: #004e17;
    --yck-green900: #002609;
    /* Primary: Chaat Masala */
    --yck-orange000: #fff4e6;
    --yck-orange100: #ffe8cc;
    --yck-orange200: #ffd8a8;
    --yck-orange300: #ffc078;
    --yck-orange400: #ffa94d;
    --yck-orange500: #ff922b;
    --yck-orange600: #fd7e14;
    --yck-orange700: #f76707;
    --yck-orange800: #e8590c;
    --yck-orange900: #d9480f;
    --yck-orange110: #bf400d;
    --yck-orange120: #99330b;
    --yck-orange130: #802b09;
    /* Fluid Typography & Spacing */
    /* @link https://utopia.fyi/type/calculator?c=320,12,1.2,1400,20,1.25,5,2,&s=0.75|0.5|0.25,1.5|2|3|4|6,s-l&g=s,l,xl,12 */
    --yck-step--1: clamp(0.625rem, 0.5139rem + 0.5556vw, 1rem);
    --yck-step--2: clamp(0.5208rem, 0.4381rem + 0.4136vw, 0.8rem);
    --yck-step-0: clamp(0.75rem, 0.6019rem + 0.7407vw, 1.25rem);
    --yck-step-1: clamp(0.9rem, 0.7037rem + 0.9815vw, 1.5625rem);
    --yck-step-2: clamp(1.08rem, 0.8213rem + 1.2935vw, 1.9531rem);
    --yck-step-3: clamp(1.296rem, 0.9566rem + 1.6969vw, 2.4414rem);
    --yck-step-4: clamp(1.5552rem, 1.1118rem + 2.2171vw, 3.0518rem);
    --yck-step-5: clamp(1.8662rem, 1.2889rem + 2.8866vw, 3.8147rem);
    /* Fluid spacing */
    --yck-space-s-xl: clamp(1rem, -0.239rem + 4.32vw, 3rem);
    --yck-orange-shadow: 0 2px 4px rgba(255, 233, 193, 1);
    --yck-box-shadow: 0 2px 4px rgba(0, 0, 0, 0.25);
    --yck-box-shadow1: 0 1px 2px rgba(0, 0, 0, 0.15);
    --yck-rounded-corners: 10px;
    --yck-heading-letter-spacing: -0.02em;
    --yck-heading-line-height: 1.2em;
    --yck-text-line-height: 1.6em;
    --yck-transition-timing: cubic-bezier(0.4, 0, 0.2, 1);
    --yck-spacing-unit: 1rem;
    interpolate-size: allow-keywords;
    scroll-behavior: smooth;
    text-rendering: optimizeSpeed;
}

/* ASPECT RATIOS */
:where(html) {
    --ratio-golden: 1.618/1;
    --ratio-landscape: 4/3;
    --ratio-portrait: 3/4;
    --ratio-square: 1;
    --ratio-ultrawide: 18/5;
    --ratio-widescreen: 16/9;
	
    --ease-1: cubic-bezier(.25, 0, .5, 1);
    --ease-2: cubic-bezier(.25, 0, .4, 1);
    --ease-3: cubic-bezier(.25, 0, .3, 1);
    --ease-4: cubic-bezier(.25, 0, .2, 1);
    --ease-5: cubic-bezier(.25, 0, .1, 1);
    --ease-in-1: cubic-bezier(.25, 0, 1, 1);
    --ease-in-2: cubic-bezier(.50, 0, 1, 1);
    --ease-in-3: cubic-bezier(.70, 0, 1, 1);
    --ease-in-4: cubic-bezier(.90, 0, 1, 1);
    --ease-in-5: cubic-bezier(1, 0, 1, 1);
    --ease-out-1: cubic-bezier(0, 0, .75, 1);
    --ease-out-2: cubic-bezier(0, 0, .50, 1);
    --ease-out-3: cubic-bezier(0, 0, .3, 1);
    --ease-out-4: cubic-bezier(0, 0, .1, 1);
    --ease-out-5: cubic-bezier(0, 0, 0, 1);
    --ease-in-out-1: cubic-bezier(.1, 0, .9, 1);
    --ease-in-out-2: cubic-bezier(.3, 0, .7, 1);
    --ease-in-out-3: cubic-bezier(.5, 0, .5, 1);
    --ease-in-out-4: cubic-bezier(.7, 0, .3, 1);
    --ease-in-out-5: cubic-bezier(.9, 0, .1, 1);
    --ease-elastic-out-1: cubic-bezier(.5, .75, .75, 1.25);
    --ease-elastic-out-2: cubic-bezier(.5, 1, .75, 1.25);
    --ease-elastic-out-3: cubic-bezier(.5, 1.25, .75, 1.25);
    --ease-elastic-out-4: cubic-bezier(.5, 1.5, .75, 1.25);
    --ease-elastic-out-5: cubic-bezier(.5, 1.75, .75, 1.25);
    --ease-elastic-in-1: cubic-bezier(.5, -0.25, .75, 1);
    --ease-elastic-in-2: cubic-bezier(.5, -0.50, .75, 1);
    --ease-elastic-in-3: cubic-bezier(.5, -0.75, .75, 1);
    --ease-elastic-in-4: cubic-bezier(.5, -1.00, .75, 1);
    --ease-elastic-in-5: cubic-bezier(.5, -1.25, .75, 1);
    --ease-elastic-in-out-1: cubic-bezier(.5, -.1, .1, 1.5);
    --ease-elastic-in-out-2: cubic-bezier(.5, -.3, .1, 1.5);
    --ease-elastic-in-out-3: cubic-bezier(.5, -.5, .1, 1.5);
    --ease-elastic-in-out-4: cubic-bezier(.5, -.7, .1, 1.5);
    --ease-elastic-in-out-5: cubic-bezier(.5, -.9, .1, 1.5);
    --ease-step-1: steps(2);
    --ease-step-2: steps(3);
    --ease-step-3: steps(4);
    --ease-step-4: steps(7);
    --ease-step-5: steps(10);
    --ease-elastic-1: var(--ease-elastic-out-1);
    --ease-elastic-2: var(--ease-elastic-out-2);
    --ease-elastic-3: var(--ease-elastic-out-3);
    --ease-elastic-4: var(--ease-elastic-out-4);
    --ease-elastic-5: var(--ease-elastic-out-5);
    --ease-squish-1: var(--ease-elastic-in-out-1);
    --ease-squish-2: var(--ease-elastic-in-out-2);
    --ease-squish-3: var(--ease-elastic-in-out-3);
    --ease-squish-4: var(--ease-elastic-in-out-4);
    --ease-squish-5: var(--ease-elastic-in-out-5);
    --ease-spring-1: linear(0, 0.006, 0.025 2.8%, 0.101 6.1%, 0.539 18.9%, 0.721 25.3%, 0.849 31.5%,
        0.937 38.1%, 0.968 41.8%, 0.991 45.7%, 1.006 50.1%, 1.015 55%, 1.017 63.9%,
        1.001);
    --ease-spring-2: linear(0, 0.007, 0.029 2.2%, 0.118 4.7%, 0.625 14.4%, 0.826 19%, 0.902, 0.962,
        1.008 26.1%, 1.041 28.7%, 1.064 32.1%, 1.07 36%, 1.061 40.5%, 1.015 53.4%,
        0.999 61.6%, 0.995 71.2%, 1);
    --ease-spring-3: linear(0, 0.009, 0.035 2.1%, 0.141 4.4%, 0.723 12.9%, 0.938 16.7%, 1.017, 1.077,
        1.121, 1.149 24.3%, 1.159, 1.163, 1.161, 1.154 29.9%, 1.129 32.8%,
        1.051 39.6%, 1.017 43.1%, 0.991, 0.977 51%, 0.974 53.8%, 0.975 57.1%,
        0.997 69.8%, 1.003 76.9%, 1);
    --ease-spring-4: linear(0, 0.009, 0.037 1.7%, 0.153 3.6%, 0.776 10.3%, 1.001, 1.142 16%, 1.185,
        1.209 19%, 1.215 19.9% 20.8%, 1.199, 1.165 25%, 1.056 30.3%, 1.008 33%, 0.973,
        0.955 39.2%, 0.953 41.1%, 0.957 43.3%, 0.998 53.3%, 1.009 59.1% 63.7%,
        0.998 78.9%, 1);
    --ease-spring-5: linear(0, 0.01, 0.04 1.6%, 0.161 3.3%, 0.816 9.4%, 1.046, 1.189 14.4%, 1.231,
        1.254 17%, 1.259, 1.257 18.6%, 1.236, 1.194 22.3%, 1.057 27%, 0.999 29.4%,
        0.955 32.1%, 0.942, 0.935 34.9%, 0.933, 0.939 38.4%, 1 47.3%, 1.011,
        1.017 52.6%, 1.016 56.4%, 1 65.2%, 0.996 70.2%, 1.001 87.2%, 1);
    --ease-bounce-1: linear(0, 0.004, 0.016, 0.035, 0.063, 0.098, 0.141, 0.191, 0.25, 0.316, 0.391 36.8%,
        0.563, 0.766, 1 58.8%, 0.946, 0.908 69.1%, 0.895, 0.885, 0.879, 0.878, 0.879,
        0.885, 0.895, 0.908 89.7%, 0.946, 1);
    --ease-bounce-2: linear(0, 0.004, 0.016, 0.035, 0.063, 0.098, 0.141 15.1%, 0.25, 0.391, 0.562, 0.765,
        1, 0.892 45.2%, 0.849, 0.815, 0.788, 0.769, 0.757, 0.753, 0.757, 0.769, 0.788,
        0.815, 0.85, 0.892 75.2%, 1 80.2%, 0.973, 0.954, 0.943, 0.939, 0.943, 0.954,
        0.973, 1);
    --ease-bounce-3: linear(0, 0.004, 0.016, 0.035, 0.062, 0.098, 0.141 11.4%, 0.25, 0.39, 0.562, 0.764,
        1 30.3%, 0.847 34.8%, 0.787, 0.737, 0.699, 0.672, 0.655, 0.65, 0.656, 0.672,
        0.699, 0.738, 0.787, 0.847 61.7%, 1 66.2%, 0.946, 0.908, 0.885 74.2%, 0.879,
        0.878, 0.879, 0.885 79.5%, 0.908, 0.946, 1 87.4%, 0.981, 0.968, 0.96, 0.957,
        0.96, 0.968, 0.981, 1);
    --ease-bounce-4: linear(0, 0.004, 0.016 3%, 0.062, 0.141, 0.25, 0.391, 0.562 18.2%, 1 24.3%, 0.81,
        0.676 32.3%, 0.629, 0.595, 0.575, 0.568, 0.575, 0.595, 0.629, 0.676 48.2%,
        0.811, 1 56.2%, 0.918, 0.86, 0.825, 0.814, 0.825, 0.86, 0.918, 1 77.2%,
        0.94 80.6%, 0.925, 0.92, 0.925, 0.94 87.5%, 1 90.9%, 0.974, 0.965, 0.974, 1);
    --ease-bounce-5: linear(0, 0.004, 0.016 2.5%, 0.063, 0.141, 0.25 10.1%, 0.562, 1 20.2%, 0.783, 0.627,
        0.534 30.9%, 0.511, 0.503, 0.511, 0.534 38%, 0.627, 0.782, 1 48.7%, 0.892,
        0.815, 0.769 56.3%, 0.757, 0.753, 0.757, 0.769 61.3%, 0.815, 0.892, 1 68.8%,
        0.908 72.4%, 0.885, 0.878, 0.885, 0.908 79.4%, 1 83%, 0.954 85.5%, 0.943,
        0.939, 0.943, 0.954 90.5%, 1 93%, 0.977, 0.97, 0.977, 1);
    --ease-circ-in: cubic-bezier(.6, .04, .98, .335);
    --ease-circ-in-out: cubic-bezier(.785, .135, .15, .86);
    --ease-circ-out: cubic-bezier(.075, .82, .165, 1);
    --ease-cubic-in: cubic-bezier(.55, .055, .675, .19);
    --ease-cubic-in-out: cubic-bezier(.645, .045, .355, 1);
    --ease-cubic-out: cubic-bezier(.215, .61, .355, 1);
    --ease-expo-in: cubic-bezier(.95, .05, .795, .035);
    --ease-expo-in-out: cubic-bezier(1, 0, 0, 1);
    --ease-expo-out: cubic-bezier(.19, 1, .22, 1);
    --ease-quad-in: cubic-bezier(.55, .085, .68, .53);
    --ease-quad-in-out: cubic-bezier(.455, .03, .515, .955);
    --ease-quad-out: cubic-bezier(.25, .46, .45, .94);
    --ease-quart-in: cubic-bezier(.895, .03, .685, .22);
    --ease-quart-in-out: cubic-bezier(.77, 0, .175, 1);
    --ease-quart-out: cubic-bezier(.165, .84, .44, 1);
    --ease-quint-in: cubic-bezier(.755, .05, .855, .06);
    --ease-quint-in-out: cubic-bezier(.86, 0, .07, 1);
    --ease-quint-out: cubic-bezier(.23, 1, .32, 1);
    --ease-sine-in: cubic-bezier(.47, 0, .745, .715);
    --ease-sine-in-out: cubic-bezier(.445, .05, .55, .95);
    --ease-sine-out: cubic-bezier(.39, .575, .565, 1);

    --shadow-color: 220 3% 15%;
    --shadow-strength: 1%;
    --inner-shadow-highlight: inset 0 -.5px 0 0 #fff, inset 0 .5px 0 0 #0001;
    --shadow-1: 0 1px 2px -1px hsl(var(--shadow-color) / calc(var(--shadow-strength) + 9%));
    --shadow-2:
        0 3px 5px -2px hsl(var(--shadow-color) / calc(var(--shadow-strength) + 3%)),
        0 7px 14px -5px hsl(var(--shadow-color) / calc(var(--shadow-strength) + 5%));
    --shadow-3:
        0 -1px 3px 0 hsl(var(--shadow-color) / calc(var(--shadow-strength) + 2%)),
        0 1px 2px -5px hsl(var(--shadow-color) / calc(var(--shadow-strength) + 2%)),
        0 2px 5px -5px hsl(var(--shadow-color) / calc(var(--shadow-strength) + 4%)),
        0 4px 12px -5px hsl(var(--shadow-color) / calc(var(--shadow-strength) + 5%)),
        0 12px 15px -5px hsl(var(--shadow-color) / calc(var(--shadow-strength) + 7%));
    --shadow-4:
        0 -2px 5px 0 hsl(var(--shadow-color) / calc(var(--shadow-strength) + 2%)),
        0 1px 1px -2px hsl(var(--shadow-color) / calc(var(--shadow-strength) + 3%)),
        0 2px 2px -2px hsl(var(--shadow-color) / calc(var(--shadow-strength) + 3%)),
        0 5px 5px -2px hsl(var(--shadow-color) / calc(var(--shadow-strength) + 4%)),
        0 9px 9px -2px hsl(var(--shadow-color) / calc(var(--shadow-strength) + 5%)),
        0 16px 16px -2px hsl(var(--shadow-color) / calc(var(--shadow-strength) + 6%));
    --shadow-5:
        0 -1px 2px 0 hsl(var(--shadow-color) / calc(var(--shadow-strength) + 2%)),
        0 2px 1px -2px hsl(var(--shadow-color) / calc(var(--shadow-strength) + 3%)),
        0 5px 5px -2px hsl(var(--shadow-color) / calc(var(--shadow-strength) + 3%)),
        0 10px 10px -2px hsl(var(--shadow-color) / calc(var(--shadow-strength) + 4%)),
        0 20px 20px -2px hsl(var(--shadow-color) / calc(var(--shadow-strength) + 5%)),
        0 40px 40px -2px hsl(var(--shadow-color) / calc(var(--shadow-strength) + 7%));
    --shadow-6:
        0 -1px 2px 0 hsl(var(--shadow-color) / calc(var(--shadow-strength) + 2%)),
        0 3px 2px -2px hsl(var(--shadow-color) / calc(var(--shadow-strength) + 3%)),
        0 7px 5px -2px hsl(var(--shadow-color) / calc(var(--shadow-strength) + 3%)),
        0 12px 10px -2px hsl(var(--shadow-color) / calc(var(--shadow-strength) + 4%)),
        0 22px 18px -2px hsl(var(--shadow-color) / calc(var(--shadow-strength) + 5%)),
        0 41px 33px -2px hsl(var(--shadow-color) / calc(var(--shadow-strength) + 6%)),
        0 100px 80px -2px hsl(var(--shadow-color) / calc(var(--shadow-strength) + 7%));
    --inner-shadow-0: inset 0 0 0 1px hsl(var(--shadow-color) / calc(var(--shadow-strength) + 9%));
    --inner-shadow-1: inset 0 1px 2px 0 hsl(var(--shadow-color) / calc(var(--shadow-strength) + 9%)), var(--inner-shadow-highlight);
    --inner-shadow-2: inset 0 1px 4px 0 hsl(var(--shadow-color) / calc(var(--shadow-strength) + 9%)), var(--inner-shadow-highlight);
    --inner-shadow-3: inset 0 2px 8px 0 hsl(var(--shadow-color) / calc(var(--shadow-strength) + 9%)), var(--inner-shadow-highlight);
    --inner-shadow-4: inset 0 2px 14px 0 hsl(var(--shadow-color) / calc(var(--shadow-strength) + 9%)), var(--inner-shadow-highlight);
}

@media (--OSdark) {
    :where(html) {
        --shadow-color: 220 40% 2%;
        --shadow-strength: 25%;
        --inner-shadow-highlight: inset 0 -.5px 0 0 #fff1, inset 0 .5px 0 0 #0007;
    }
}
	
/* Box Sizing */
*,
*::before,
*::after {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

html {
    font-size: 100%;
}

body {
    min-height: 100dvh;
    font-family: inherit;
    line-height: var(--yck-text-line-height);
    word-break: break-word;
    overflow-wrap: break-word;
    background-color: inherit;
}

/* Containers & Wrappers - div, article, main, section */
.yck-component {
    padding: 0;
    margin: 0;
    width: 100%;
    max-width: 1023px;
}

.yck-component * {
    font-size: var(--yck-step-0);
}

.yck-component :is(article, section) {
    width: 100%;
}

.yck-component article {
    margin-block: 1em;
}

.yck-component section {
    margin-block: var(--yck-space-s-xl);
}

/* Centering GRID */
.yck-component .deadctr-container {
    display: grid;
    margin: 0 auto;
    padding: 0;
    height: auto;
    justify-items: center;
    align-content: space-around;
    place-items: center;
}

/* QRCode Container */
.yck-component .qr-container {
    display: flex;
    gap: var(--yck-space-s-xl);
    height: 350px;

    .qr-img {
        max-width: 60%;
        min-width: 100px;
    }
}

.yck-component .regular-flow>*+* {
    margin-top: 1.125em;
}

/* ============ Base Typography ==================== */
.yck-component :is(div, p, li, td) {
    padding: 0;
    margin: 0;
    line-height: var(--yck-text-line-height);
    letter-spacing: normal;
    text-wrap: pretty;
}

/* ================= Headings ==================== */
.yck-component :is(h1,
.yck-h1,
h2,
.yck-h2,
h3,
.yck-h3,
h4,
.yck-h4,
h5,
.yck-h5,
h6,
.yck-h6,
p) {
    overflow-wrap: break-word;
}

.yck-component :is(heading,
nav,
h1,
.yck-h1,
h2,
.yck-h2,
h3,
.yck-h3,
h4,
.yck-h4,
h5,
.yck-h5,
h6,
.yck-h6) {
    text-wrap: balance;
}

.yck-component h1,
.yck-component .yck-h1 {
    font-size: var(--yck-step-5);
    font-weight: 800;
    line-height: var(--yck-heading-line-height);
}

.yck-component h2,
.yck-component .yck-h2 {
    font-size: var(--yck-step-4);
    font-weight: 700;
    line-height: var(--yck-heading-line-height);
}

.yck-component h3,
.yck-component .yck-h3 {
    font-size: var(--yck-step-3);
    font-weight: 600;
    line-height: var(--yck-heading-line-height);
}

.yck-component h4,
.yck-component .yck-h4 {
    font-size: var(--yck-step-2);
    font-weight: 500;
    line-height: var(--yck-heading-line-height);
}

.yck-component h5,
.yck-component .yck-h5 {
    font-size: var(--yck-step-1);
    font-weight: 500;
    line-height: var(--yck-heading-line-height);
    text-transform: uppercase;
}

.yck-component h6,
.yck-component .yck-h6 {
    font-size: var(--yck-step-0);
    line-height: var(--yck-heading-line-height);
    text-transform: uppercase;
}

.yck-component .small,
.yck-component .yck-small,
.yck-component small {
    font-size: var(--yck-step--2);
    line-height: calc(var(--yck-text-line-height) * 0.75);
}

/* Ordered and Unordered Lists */
.yck-component ol,
.yck-component ul {
    padding: 0;
    margin-block: 0;
    margin-left: 1.5em;
}

.yck-component ul li,
.yck-component ol li {
    padding-left: 0.25em;
    margin-block: 0.5em;
    line-height: 1.5;
}

.yck-component ul li:last-child,
.yck-component ol li:last-child {
    margin-bottom: 1.5em;
}

/* Removes the gap between nested lists (list within a list). */
.yck-component li ul,
.yck-component li ol {
    margin-top: 0;
}
	
/* Key Personnel In-Charge */
.yck-component .card {
  font-family: "Georgia", "Lato", "Poppins", sans-serif;
  width: fit-content;
  border-radius: 10px;
  background-image: linear-gradient(to top left, rgba(36, 36, 36, 0.95) 0%, rgba(0, 0, 0, 0.5) 100%);
  padding:1em 2em 1em 2em;
  display: flex;
  flex-direction: column;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  position: relative;
  overflow: hidden;
  cursor: pointer;
}

.yck-component .cls-1 {
  fill: #fff;
}

.yck-component .title {
  font-size: 32px;
  font-weight: 600;
  color: #ffffff;
  margin-bottom: 1em;
}

.yck-component .label {
  font-size: 20px;
  color: #efefef;
  opacity: 0.5;
  line-height: 1.4;
  font-weight: 200;
  margin-bottom: 3em;
  transition: right 0.5s ease-in-out, opacity 0.5s ease;
  margin-left: 1em;
}

.yck-component .ico {
  position: absolute;
  color: #efefef;
  font-family: "Verdana", "Tahoma", "Nunito", "Lato", sans-serif;
  font-size: 1.25em;
  font-weight: 500;
  bottom: 0.25em;
  left: 72px;
  display: flex;
  opacity: 0;
  transition: left 0.5s ease-in-out, opacity 0.3s ease;
}

.yck-component .card::before {
  content: "";
  position: absolute;
  left: 0;
  top: 0;
  bottom: 0;
  width: 10px;
  background-image: linear-gradient(to bottom, darkorange, yellow, lightyellow);
  border-radius: 10px 0 0 10px;
  transition: width 0.5s ease-in-out;
}

.yck-component .card:hover::before {
  width: 20px;
}

.yck-component .card:hover {
  border-left-width: 18px;
}

.yck-component .title,
.yck-component .label {
  transition: transform 0.5s ease-in-out;
}

.yck-component .card:hover .title,
.yck-component .card:hover .label {
  transform: translateX(20px);
}

.yck-component .card:hover .ico {
  left: 52px;
  opacity: 0.8;
}

.yck-component .gradient {
  position: absolute;
  top: -200px;
  left: -200px;
  width: 600px;
  height: 600px;
  background: #ffffff;
  border-radius: 50%;
  filter: blur(300px);
  opacity: 0;
  transition: opacity 0.5s ease-in-out;
}

.yck-component .card:hover .gradient {
  opacity: 0.4;
}
	
/* --- Carousel --- */

.yck-component .carousel.card {
  width: 100%;
  height: 100%;
  padding: 1em;
  border: 1px solid #ccc;
  border-radius: var(--yck-rounded-corners);
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  color: whitesmoke;
  text-align: center;
}

.yck-component .carousel.card p {
  font-size: var(--yck-step-0);
  color: var(--neutral-800);
}

.yck-component .carousel.slider {
  width: 100%;
  height: var(--height);
  overflow: hidden;
  mask-image: linear-gradient(to right, transparent, #000 10% 90%, transparent);
}
.yck-component .carousel.slider .list {
  display: flex;
  width: 100%;
  min-width: calc(var(--width) * var(--quantity));
  position: relative;
}
.yck-component .carousel.slider .list .item {
  width: var(--width);
  height: var(--height);
  position: absolute;
  left: 100%;
  animation: autoRun 30s linear infinite;
  transition: filter 1.5s;
  animation-delay: calc(
    (30s / var(--quantity)) * (var(--position) - 1) - 30s
  ) !important;
}
.yck-component .carousel.slider .list .item img {
  width: 100%;
}
@keyframes autoRun {
  from {
    left: 100%;
  }
  to {
    left: calc(var(--width) * -1);
  }
}
.yck-component .carousel.slider:hover .item {
  animation-play-state: paused !important;
  filter: grayscale(1);
}
.yck-component .carousel.slider .item:hover {
  filter: grayscale(0);
}
.yck-component .carousel.slider[reverse="false"] .item {
  animation: reversePlay 10s linear infinite;
}
@keyframes reversePlay {
  from {
    left: calc(var(--width) * -1);
  }
  to {
    left: 100%;
  }
}

</style>