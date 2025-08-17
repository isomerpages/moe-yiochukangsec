---
title: Organisation Chart
permalink: /our-family/our-staff/organisation-chart/
description: ""
variant: markdown
image: /images/YCKLogo.svg
third_nav_title: Our Staff
---
<style>
/* ==========================================================================
   1. Global Styles & Resets
   ========================================================================== */

:root {
    --yck-text-line-height: 1.6em;
    --yck-heading-line-height: 1.2em;
    --yck-heading-letter-spacing: -0.02em;
    --yck-spacing-unit: 1em;
    --yck-box-shadow: 0 2px 4px rgba(0, 0, 0, 0.25);
    --yck-box-shadow1: 0 1px 2px rgba(0, 0, 0, 0.15);
    --yck-inset-shadow1: rgba(50, 50, 93, 0.25) 0px 30px 60px -12px inset, rgba(0, 0, 0, 0.3) 0px 18px 36px -18px inset;
    --yck-inset-shadow2: rgb(204, 219, 232) 3px 3px 6px 0px inset, rgba(255, 255, 255, 0.5) -3px -3px 6px 1px inset;
    --yck-transition-timing: cubic-bezier(0.4, 0, 0.2, 1);

    --yck-step--2: clamp(0.7813rem, 0.9263rem + -0.1872vw, 0.8889rem);
    --yck-step--1: clamp(0.9375rem, 1.0217rem + -0.1087vw, 1rem);
    --yck-step-0: clamp(1.125rem, 1.125rem + 0vw, 1.125rem);
    --yck-step-1: clamp(1.2656rem, 1.2363rem + 0.1467vw, 1.35rem);
    --yck-step-2: clamp(1.4238rem, 1.3556rem + 0.3412vw, 1.62rem);
    --yck-step-3: clamp(1.6018rem, 1.4828rem + 0.5951vw, 1.944rem);
    --yck-step-4: clamp(1.802rem, 1.6174rem + 0.9231vw, 2.3328rem);
    --yck-step-5: clamp(2.0273rem, 1.7587rem + 1.3427vw, 2.7994rem);

    --yck-space-s-xl: clamp(1em, 0.2143em + 3.9286vw, 3.5em);
    interpolate-size: allow-keywords;
    scroll-behavior: smooth;
    text-rendering: optimizeSpeed;
}

body {
    min-height: 100vh;
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

/* ==========================================================================
   2. Base Typography
   ========================================================================== */

.yck-component {
    line-height: var(--yck-text-line-height);
    letter-spacing: normal;
    font-size: var(--yck-step-0);
    margin-bottom: var(--yck-space-s-xl);
    position: relative;
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
    margin-bottom: var(--yck-spacing-unit);
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

.yck-component small,
small {
    font-size: var(--yck-step--2);
    line-height: var(--yck-spacing-unit);
}

.yck-component a {
    text-decoration: none;
    color: #e37f2a;
}

.yck-component a.text-link {
    position: relative;
    padding-bottom: 2px;
    text-decoration: none;
}

.yck-component a.text-link::after {
    content: " ";
    position: absolute;
    width: 0;
    height: 2px;
    bottom: 0;
    left: 0;
    background-color: currentColor;
    transition:
        width 1s cubic-bezier(0.25, 1, 0.5, 1),
        color 1.2s ease-out;
}

.yck-component a.text-link:hover::after {
    width: 100%;
    color: rgba(0, 122, 247, 0.25);
}

.yck-component a[target="_blank"]:not(.text-link):after {
    display: none;
    margin: 0;
    padding: 0;
}

.yck-component abbr {
    text-decoration: underline dotted #2c6139;
    text-decoration-thickness: 2px;
    text-underline-offset: 3px;
    color: #2c6139;
    font-weight: 600;
    cursor: help;
}

.yck-component abbr:hover {
    color: #4e835b;
}

.yck-component .dropcap-title {
    font-size: var(--yck-step-1);
    /* Base font size for the heading */
    font-weight: normal;
    margin-bottom: 0.5em;
    color: #555;
}

/* This is the core magic for the dropcap */
.yck-component .dropcap-title::first-letter {
    float: left;
    font-size: calc(var(--yck-step-5)*1.65);
    /* The size of the dropcap relative to the heading's font size */
    font-weight: bold;
    font-style: oblique;
    font-family: cursive;
    line-height: 0.9;
    /* Pulls the rest of the text up vertically */
    padding-right: 0.18em;
    /* Adds a little space next to the letter */
    color: #4e835b;
    /* A distinct color for the dropcap */
}

/* ==========================================================================
   3. Layout Components
   ========================================================================== */

.yck-component .regular-flow>*+* {
    margin-top: 1.125em;
}

.yck-component .col-container,
.yck-component .col3-container {
    width: 100%;
    max-width: 1000px;
    margin: 0 auto;
    column-count: 2;
    column-width: 360px;
    column-gap: 1.5em;
}

.yck-component .col3-container {
    columns: 3;
    column-width: 240px;
    column-gap: 1.5em;
    column-rule-style: dotted;
    column-rule-width: 0.5px;
    column-rule-color: rgba(170, 170, 170, 0.25);
}

/* --- Flexbox Grid System --- */
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

.yck-component .yck-img-array {
    --yck-gap: 1.25rem;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    align-content: flex-start;
    justify-content: flex-start;
    flex-wrap: wrap;
    list-style: none;
    gap: var(--yck-gap);
    padding: 0;
    margin: 0;
}

.yck-component .yck-img-array>* {
    flex-grow: 1;
    flex-shrink: 0;
    flex-basis: calc((100% - var(--yck-gap)) / 6);
    min-width: 240px;
    list-style: none;
}

.masonry-item {
    break-inside: avoid;
    margin-bottom: 1rem;
    display: inline-block;
    width: 100%;
}

.masonry-item img {
    width: 100%;
    height: auto;
    display: block;
}

/* ==========================================================================
   4. UI Components
   ========================================================================== */

/* --- Tables --- */
.yck-component .yck-table {
    border-collapse: collapse;
    width: 100%;
    max-width: 1000px;
    margin-top: 0.5em;
    margin-bottom: var(--yck-spacing-unit);
}

.yck-component .yck-th {
    background-color: #f2f2f2;
    text-align: left;
    border-bottom: 1px dotted #ddd;
    text-transform: uppercase;
    padding: calc(var(--yck-spacing-unit) * 0.75);
    font-weight: bold;
    font-size: var(--yck-step-0);
    line-height: 1.4;
    letter-spacing: 0.05em;
    vertical-align: top;
}

.yck-component .yck-th h4,
.yck-component .yck-th h5,
.yck-component .yck-th h6 {
    margin: 0 0 calc(var(--yck-spacing-unit) * 0.5) 0;
    text-wrap: balance;
    line-height: 1.3;
}

.yck-component .yck-td {
    border-bottom: 1px dotted #ddd;
    min-width: 120px;
    max-width: 100%;
    word-wrap: break-word;
    text-wrap: pretty;
    padding: calc(var(--yck-spacing-unit) * 0.75);
    vertical-align: top;
    font-size: var(--yck-step-0);
    line-height: 1.5;
}

.yck-component .yck-td>*,
.yck-component .yck-td p,
.yck-component .yck-td ul,
.yck-component .yck-td ol {
    margin-top: 0;
    margin-bottom: calc(var(--yck-spacing-unit) * 0.5);
}

.yck-component .yck-td ul,
.yck-component .yck-td ol {
    padding-left: calc(var(--yck-spacing-unit) * 1.5);
}

.yck-component .yck-td li {
    margin-bottom: calc(var(--yck-spacing-unit) * 0.25);
    line-height: inherit;
}

.yck-component .yck-td>*:last-child,
.yck-component .yck-td>p:last-child,
.yck-component .yck-td>ul:last-child,
.yck-component .yck-td>ol:last-child {
    margin-bottom: calc(var(--yck-spacing-unit) * 0.75);
}

.yck-component .yck-td ul:last-child li:last-child,
.yck-component .yck-td ol:last-child li:last-child {
    margin-bottom: calc(var(--yck-spacing-unit) * 0.25);
}

.yck-component .yck-table tbody tr:last-child .yck-td>*:last-child {
    margin-bottom: var(--yck-spacing-unit);
}

.yck-component .yck-table tbody tr:nth-child(even) {
    background-color: #fafafa;
}

/* --- Video Containers --- */
.yck-component .video-container {
    position: relative;
    width: 100%;
    padding-bottom: 56.25%;
    height: 0;
    overflow: hidden;
    margin-bottom: var(--yck-spacing-unit);
}

.yck-component .video-container iframe,
.yck-component .video-container object,
.yck-component .video-container embed {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}

.yck-component .widescreentv {
    aspect-ratio: 16/9;
    width: 100%;
}

.yck-component .tallscreentv {
    aspect-ratio: 9/16;
    width: 100%;
}

.yck-component .sdtv {
    aspect-ratio: 4/3;
    width: 100%;
}

/* --- Isomer Cards --- */
.yck-component .isomer-card,
.yck-component .column {
    break-inside: avoid;
    page-break-inside: avoid;
    padding: 20px;
    border-radius: 5px;
    box-shadow: var(--yck-box-shadow1);
}

.yck-component .column {
    margin-bottom: var(--yck-spacing-unit);
}

.yck-component .column ul,
.yck-component .column ol {
    list-style: none;
    line-height: 1.5em;
    margin: 0;
    padding: 0;
}

.yck-component .column ul li {
    margin-inline: 1em;
    padding-left: 1rem;
    border-bottom: 1px dotted rgba(0, 0, 0, 0.05);
}

.yck-component .isomer-card {
    text-decoration: none;
    margin: 0 auto;
    padding: 0;
    border: 1px solid rgba(224, 224, 224, 0.15);
    border-radius: 8px;
    overflow: hidden;
    transition:
        transform 0.8s var(--yck-transition-timing),
        box-shadow 0.8s var(--yck-transition-timing),
        background-color 0.5s ease;
}

.yck-component .isomer-card:hover {
    transform: translateY(-5px);
    box-shadow: var(--yck-box-shadow);
}

.yck-component .isomer-card:hover .isomer-card-body .isomer-card-link {
    color: #e37f2a;
}

.yck-component .isomer-card:has(img) {
    filter: brightness(100%);
    background-color: #fff;
    transition: filter 0.5s ease;
}

.yck-component .isomer-card:has(img):hover {
    filter: brightness(90%);
    background-color: #898989;
}

.yck-component .isomer-card .isomer-card-image {
    width: 100%;
    object-fit: cover;
}

.yck-component .isomer-card .isomer-card-body {
    padding: var(--yck-spacing-unit);
}

.yck-component .isomer-card .isomer-card-body .isomer-card-title {
    color: #4a4a4a;
    font-weight: 700;
    font-size: var(--yck-step-1);
    overflow-wrap: break-word;
    text-wrap: balance;
}

.yck-component .isomer-card .isomer-card-body .isomer-card-description {
    color: #484848;
    font-size: var(--yck-step-0);
}

.yck-component .isomer-card .isomer-card-body .isomer-card-link {
    font-size: var(--yck-step-0);
    text-decoration: underline;
    color: #e37f2a;
    display: inline-block;
    margin-top: 0.5rem;
}

.yck-component .isomer-card .isomer-card-body .isomer-card-title:has(+ .isomer-card-description) {
    margin-bottom: 0.75rem;
}

.yck-component .isomer-card .isomer-card-body .isomer-card-title:has(+ .isomer-card-link),
.yck-component .isomer-card .isomer-card-body .isomer-card-description:has(+ .isomer-card-link) {
    margin-bottom: 1rem;
}

/* --- Blockquotes & Figures --- */
.yck-component blockquote {
    position: relative;
    padding: 25px 35px;
    background-color: white;
    border-radius: 5px;
    box-shadow: var(--yck-box-shadow);
    margin-left: 0;
    margin-right: 0;
}

.yck-component blockquote>p,
.yck-component blockquote>div {
    color: #ff6b6b;
    font-style: italic;
    font-size: var(--yck-step-1);
    line-height: 1.5;
    margin: 0;
}

.yck-component blockquote::before {
    content: '"';
    position: absolute;
    top: 25px;
    left: 10px;
    color: #ff6b6b;
    font-size: 60px;
    font-family: Georgia, serif;
    opacity: 0.3;
}

.yck-component cite {
    display: block;
    margin-top: var(--yck-spacing-unit);
    font-size: var(--yck-step--1);
    font-style: italic;
    color: #555;
    text-align: right;
}

.yck-component figure,
.yck-component .figure {
    display: flex;
    flex-flow: column;
    max-width: 100%;
    margin: 0;
    padding: 0;
}

.yck-component figure img,
.yck-component .figure img {
    border-radius: 8px;
    box-shadow: var(--yck-box-shadow);
    margin-bottom: var(--yck-spacing-unit);
}

.yck-component figcaption {
    background-color: rgba(255, 255, 255, 0.75);
    color: #333;
    font: italic var(--yck-step--1) sans-serif;
    margin: 0;
    padding: 5px;
    text-align: center;
}

/* --- Org Chart --- */
.yck-component .orgchart {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    width: 100%;
    max-width: 1000px;
    margin: 0 auto;
    padding: 0;
}

.yck-component .section-title {
    font-size: var(--yck-step-3);
    font-weight: bold;
    margin-top: 30px;
    margin-bottom: var(--yck-spacing-unit);
    color: #222;
    border-bottom: 3px solid #555;
    padding-bottom: 8px;
    width: 100%;
    text-align: left;
}

.yck-component .person-container {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    flex-wrap: wrap;
    width: 100%;
    margin-bottom: var(--yck-space-s-xl);
    position: relative;
}

.yck-component .person {
    border-radius: 6px;
    padding: 10px 15px;
    margin: 10px;
    text-align: left;
    min-width: 200px;
    box-shadow: var(--yck-box-shadow);
    flex-grow: 0;
    flex-shrink: 0;
    flex-basis: calc(25% - 10px);
}

.yck-component .person-email {
    font-size: var(--yck-step--1);
    font-weight: normal;
    margin-inline-start: calc(var(--yck-space-s-xl) * 2);
    margin-bottom: var(--yck-spacing-unit);
    color: #333;
}

.yck-component .person-name {
    font-size: var(--yck-step-0);
    font-weight: normal;
    color: #333;
}

.yck-component .person-title {
    font-size: var(--yck-step-1);
    color: #555;
}

/* --- Details/Summary (Accordion) --- */
.yck-component details {
    overflow: hidden;
}

.yck-component details * {
    margin: 0 !important;
}

.yck-component details>p,
.yck-component details ul,
.yck-component details div {
    animation: fade-in 1s ease-out;
    padding-top: calc(var(--yck-spacing-unit) * 0.5);
}

.yck-component summary {
    margin-inline-start: 1.5rem;
    padding: 1rem;
    list-style-position: outside;
    cursor: pointer;
    user-select: none;
    outline: none;
    font-size: var(--yck-step-1);
    font-weight: 500;
    border-radius: 10px;
    transition: box-shadow 0.3s ease-in-out;
}

.yck-component summary:hover {
    box-shadow: var(--yck-inset-shadow2);
}

.yck-component summary::marker {
    font-size: var(--yck-step-2);
}
.yck-component summary::after {
    content: "+";
    position: absolute;
    font-size: var(--yck-step-2);
    right: 1rem;
    top: 1.25em;
    transform: translateY(-50%) rotate(0deg); 
    transition: transform 0.5s ease-in-out;
}

.yck-component details[open] > summary::after {
    transform: translateY(-50%) rotate(135deg); /* Rotates the icon 90 degrees */
}

.yck-component details::details-content {
    font-size: var(--yck-step-0);
    padding-left: 1.5rem;
    padding-right: var(--yck-space-s-xl);
    block-size: 0;
    transition:
        block-size 1s ease,
        content-visibility 1s ease;
    transition-behavior: allow-discrete;
}

.yck-component details[open]::details-content {
    block-size: auto;
}

.yck-component details>*:not(summary) {
    padding: 0.5rem 1rem 1rem 2rem;
    animation: fade-in 1s ease 1s;
    animation-fill-mode: both;
}

/* --- Integrated Navigation Bar Styles --- */
.yck-component .yck-nav-bar>* {
    margin: 0;
    padding: 0;
}

.yck-component .yck-nav-bar ul {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    list-style: none;
    background-color: #ffffff;
    border-radius: 0.75rem;
    box-shadow: var(--yck-inset-shadow2);
    
    justify-content: start;
    align-content: start;
    justify-items: center;
      align-items: start;
}

.yck-component .yck-nav-bar a {
    display: block;
    text-decoration: none;
    font-family: sans-serif;
    font-weight: 500;
    font-size: var(--yck-step-0);
    transition: all 0.3s var(--yck-transition-timing);
    margin: calc(var(--yck-spacing-unit) * 0.1);
    padding: 1rem;
    border-radius: 0.5rem;
    text-align: center;
    text-wrap: balance;
    overflow-wrap: break-word;
    color: #4a5568;
    position: relative;
}

.yck-component .yck-nav-bar a::after {
    content: '';
    position: absolute;
    width: 0;
    height: 2px;
    bottom: 10px;
    left: 50%;
    transform: translateX(-50%);
    background-color: #4299e1;
    /* Added background-color to the transition for the color fade effect */
    transition: width 0.7s var(--yck-transition-timing), background-color 0.7s var(--yck-transition-timing);
}


.yck-component .yck-nav-bar a.active {
    color: #2b6cb0;
}

.yck-component .yck-nav-bar a.active::after {
    width: 60%;
    background-color: #4299e1;
}


.yck-component .yck-nav-bar a:hover {
    color: #e37f2a;
}

.yck-component .yck-nav-bar a:hover::after {
    background-color: #e37f2a;
    width: 60%;
}



/* --- Buttons --- */
.yck-component .button-container {
    margin: 0;
    padding: 0;
    display: flex;
    text-align: center;
    width: 100%;
    justify-content: flex-end;
    align-items: flex-end;
}

.yck-component .button {
    background-color: #e37f2a;
    color: #fff;
    font-size: var(--yck-step-0);
    font-weight: 900;
    margin: 1rem;
    padding: 0.65rem;
    border-radius: 50px;
    box-shadow:
        0 10px 15px -3px rgba(0, 0, 0, 0.15),
        0 4px 6px -2px rgba(0, 0, 0, 0.05);
    transition: all 0.35s ease-in-out;
    border: none;
    cursor: pointer;
    text-decoration: none;
    display: inline-block;
}

.yck-component .button:hover {
    text-decoration: none;
    background-color: #fabe64;
    color: #fff;
    box-shadow:
        0 20px 25px -6px rgba(0, 0, 0, 0.12),
        0 10px 10px -5px rgba(0, 0, 0, 0.04);
    transform: scale(1.05);
}

.yck-component .button:focus {
    outline: none;
    box-shadow: 0 0 0 4px rgba(250, 190, 60, 0.5);
}

.yck-component .truncate {
    display: block;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
}

/* --- Backdrop --- */
.yck-component .backdrop {
    position: absolute;
    inset: 0;
    height: 200%;
    border-radius: 4px;
    background: hsl(0deg 0% 100% / 0.1);
    pointer-events: none;
    backdrop-filter: blur(16px);
    mask-image: linear-gradient(to bottom,
        black 0,
        black 50%,
        transparent 50%);
}

.yck-component .backdrop-edge {
    --thickness: 6px;
    position: absolute;
    inset: 0;
    height: 100%;
    transform: translateY(100%);
    background: hsl(0deg 0% 100% / 0.1);
    backdrop-filter: blur(8px) brightness(120%);
    pointer-events: none;
    mask-image: linear-gradient(to bottom,
        black 0,
        black var(--thickness),
        transparent var(--thickness));
}

/* ==========================================================================
   5. Animations & Transitions
   ========================================================================== */

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

.fade-in {
    animation: fade-in 1s ease-in-out both;
}

@keyframes kenBurns {
    from {
        transform: scale(1);
    }

    to {
        transform: scale(1.35);
    }
}

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

@keyframes fade-in-bottom {
    from {
        opacity: 0;
        transform: translateY(10vh);
    }

    to {
        opacity: 1;
        transform: translateY(0);
    }
}

/* ==========================================================================
   6. Accessibility & Media Queries
   ========================================================================== */

@media (max-width: 1000px) {
    .yck-component .yck-flexbox-grid>* {
        flex-basis: 100%;
    }
}

@media (max-width: 768px) {
    .yck-component .yck-table {
        font-size: calc(var(--yck-step-0) * 0.9);
    }

    .yck-component .yck-th,
    .yck-component .yck-td {
        padding: calc(var(--yck-spacing-unit) * 0.5);
    }
}

@media (max-width: 600px) {
    .yck-component .yck-flex-grid>* {
        flex-basis: auto;
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

    .yck-component .col-container,
    .yck-component .col3-container,
    .yck-component .isomer-card-grid {
        animation: fade-in-bottom ease both;
        animation-timeline: view();
        animation-range: entry 25% cover 50%;
    }
}

/* Main container for the entire organizational chart */
.org-chart {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 100%;
    max-width: 1600px;
    /* Allows for a wider chart */
}

/* Styling for major section titles like "School Leaders" */
.section-title {
    font-size: var(--yck-step-3);
    font-weight: bold;
    margin-top: 30px;
    margin-bottom: 20px;
    color: #222;
    border-bottom: 3px solid #555;
    padding-bottom: 8px;
    width: 100%;
    text-align: center;
}

/* Container for a group of people, e.g., all school leaders */
.person-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    width: 100%;
    margin-bottom: 25px;
    position: relative;
    /* Needed for the pseudo-element connector line */
}

/* A simple vertical line connecting a section title to its content below */
.person-container::before {
    content: '';
    position: absolute;
    top: -15px;
    /* Positioned just below the title */
    left: 50%;
    transform: translateX(-50%);
    width: 2px;
    height: 15px;
    background-color: #777;
}

/* Styling for department and staff group containers */
.department,
.staff-group {
    width: 100%;
    margin-bottom: 30px;
    padding: 15px;
    border: 1px solid #d0d0d0;
    border-radius: 8px;
    background-color: #fdfdfd;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
}

/* Titles for individual departments or non-teaching staff groups */
.department-name,
.group-name {
    font-size: var(--yck-step-2);
    font-weight: bold;
    color: #333;
    margin-bottom: 15px;
    text-align: center;
    border-bottom: 1px dashed #aaa;
    padding-bottom: 10px;
}

/* Grid layout for displaying people within a department or group */
.people-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 10px;
    /* Provides spacing between individual person cards */
}

/* Individual card for each person */
.person {
    background-color: #fff;
    border: 1px solid #ccc;
    border-radius: 6px;
    padding: 10px 15px;
    margin: 5px;
    text-align: center;
    min-width: 160px;
    max-width: 200px;
    box-shadow: 1px 1px 3px rgba(0, 0, 0, 0.1);
    flex-grow: 1;
    /* Prevents cards from growing to fill space */
    flex-shrink: 0;
    /* Prevents cards from shrinking */
    flex-basis: calc(20% - 10px);
    /* Aims for 5 cards per row, adjusting for gap */
}

/* Name of the person */
.person-name {
    font-size: var(--yck-step--1);
    font-weight: bold;
    margin-bottom: 4px;
    color: #333;
}

/* Title/role of the person */
.person-title {
    font-size: 0.85em;
    color: #555;
    margin-bottom: 8px;
    /* Add some space before the details tag */
}

.person details {
    font-size: 0.8em;
    cursor: pointer;
}

/* --- Tier-Specific Styling --- */

/* Special styling for school leader cards */
.school-leaders .person {
    background-color: #e0eafc;
    border-color: #abc4ff;
    flex-basis: calc(33% - 20px);
    /* Aims for 3 leaders per row */
}

/* Special styling for key personnel cards */
.key-personnel .person {
    background-color: #dcf0dc;
    border-color: #a0c0a0;
    flex-basis: calc(33.33% - 10px);
    /* Aims for 3 per row */
}

/* Styling for teaching staff cards within departments */
.department .person {
    background-color: #fff5e6;
    border-color: #ffd5ab;
    flex-basis: calc(25% - 10px);
    /* Aims for 4 per row */
}

/* Styling for non-teaching staff cards within groups */
.staff-group .person {
    background-color: #e6f2ff;
    border-color: #adccef;
    flex-basis: calc(25% - 10px);
    /* Aims for 4 per row */
}

/* --- Responsive Adjustments for Different Screen Sizes --- */

@media (max-width: 1200px) {
    .person {
        flex-basis: calc(25% - 10px);
        /* 4 cards per row */
    }

    .school-leaders .person {
        flex-basis: calc(50% - 20px);
        /* 2 leader cards per row */
    }
}

@media (max-width: 900px) {
    .person {
        flex-basis: calc(33.33% - 10px);
        /* 3 cards per row */
    }
}

@media (max-width: 600px) {
    .person {
        flex-basis: calc(50% - 10px);
        /* 2 cards per row */
    }

    .department-name,
    .group-name {
        font-size: 1.2em;
    }

    .section-title {
        font-size: 1.5em;
    }
}

@media (max-width: 400px) {
    .person {
        flex-basis: calc(100% - 10px);
        /* 1 card per row */
    }
}
</style>
<div class="yck-component">
                            <nav id="top" class="yck-nav-bar">
                                <ul>
                                    <li><a href="#School-Leaders">SCHOOL LEADERS</a></li>
                                    <li><a href="#Key-Personnel">KEY PERSONNEL</a></li>
                                    <li><a href="#Teaching-Staff">TEACHING STAFF</a></li>
                                    <li><a href="#Non-teaching-Staff">NON-TEACHING STAFF</a></li>
                                </ul>
                            </nav>
                        </div>
                        <div class="wrapper">
                            <div class="org-chart">
                                <div id="School-Leaders" class="section-title">School Leaders</div>
                                <div class="person-container school-leaders">
                                    <div class="person">
                                        <div class="person-name">Mrs Chow (Betty Chang)</div>
                                        <div class="person-title">PRINCIPAL</div>
                                        <details>
                                            <summary>Email Address:</summary>betty_chang@moe.edu.sg
                                        </details>
                                    </div>
                                    <div class="person">
                                        <div class="person-name">Mr Kevin Lim Hock Chye</div>
                                        <div class="person-title">VICE-PRINCIPAL</div>
                                        <details>
                                            <summary>Email Address:</summary>lim_hock_chye_kevin@moe.edu.sg
                                        </details>
                                    </div>
                                    <div class="person">
                                        <div class="person-name">Mr Pek Xu Hao Alvin</div>
                                        <div class="person-title">VICE-PRINCIPAL</div>
                                        <details>
                                            <summary>Email Address:</summary>pek_xu_hao_alvin@moe.edu.sg
                                        </details>
                                    </div>
                                </div>
                                <div id="Key-Personnel" class="section-title">Key Personnel</div>
                                <div class="person-container key-personnel">
                                    <div class="person">
                                        <div class="person-name">Mr Pang Tiangui Desmond</div>
                                        <div class="person-title">Staff Developer</div>
                                        <details>
                                            <summary>Email Address:</summary>
                                        </details>
                                    </div>
                                    <div class="person">
                                        <div class="person-name">Ms Lock Hwee Hong Alicia</div>
                                        <div class="person-title">HOD/Science</div>
                                        <details>
                                            <summary>Email Address:</summary>
                                        </details>
                                    </div>
                                    <div class="person">
                                        <div class="person-name">Mdm Chen Huijun</div>
                                        <div class="person-title">HOD/Hum</div>
                                        <details>
                                            <summary>Email Address:</summary>chen_huijun@moe.edu.sg
                                        </details>
                                    </div>
                                    <div class="person">
                                        <div class="person-name">Ms Chong Foong Harn</div>
                                        <div class="person-title">HOD/EL</div>
                                        <details>
                                            <summary>Email Address:</summary>chong_foong_harn@moe.edu.sg
                                        </details>
                                    </div>
                                    <div class="person">
                                        <div class="person-name">Mr Goh Chye Peng David</div>
                                        <div class="person-title">HOD/Student Mgmt</div>
                                        <details>
                                            <summary>Email Address:</summary>goh_chye_peng_david@moe.edu.sg
                                        </details>
                                    </div>
                                    <div class="person">
                                        <div class="person-name">Mr Chin Pin Chuen Brandon</div>
                                        <div class="person-title">HOD/ICT</div>
                                        <details>
                                            <summary>Email Address:</summary>chin_pin_chuen_brandon@moe.edu.sg
                                        </details>
                                    </div>
                                    <div class="person">
                                        <div class="person-name">Mdm Goh Shwu Jun</div>
                                        <div class="person-title">HOD/Math</div>
                                        <details>
                                            <summary>Email Address:</summary>goh_shwu_jun@moe.edu.sg
                                        </details>
                                    </div>
                                    <div class="person">
                                        <div class="person-name">Ms Goy Yap Ching</div>
                                        <div class="person-title">HOD/MTL</div>
                                        <details>
                                            <summary>Email Address:</summary>goy_yap_ching@moe.edu.sg
                                        </details>
                                    </div>
                                    <div class="person">
                                        <div class="person-name">Ms Heng Siew Hoon Irene</div>
                                        <div class="person-title">HOD PE &amp; CCA</div>
                                        <details>
                                            <summary>Email Address:</summary>heng_siew_hoon@moe.edu.sg
                                        </details>
                                    </div>
                                    <div class="person">
                                        <div class="person-name">Ms Hoon Siew Hui</div>
                                        <div class="person-title">HOD/Design &amp; Enterprise</div>
                                        <details>
                                            <summary>Email Address:</summary>hoon_siew_hui@moe.edu.sg
                                        </details>
                                    </div>
                                    <div class="person">
                                        <div class="person-name">Ms Cho Ling Ling Kelly</div>
                                        <div class="person-title">Year Head (LS)</div>
                                        <details>
                                            <summary>Email Address:</summary>
                                        </details>
                                    </div>
                                    <div class="person">
                                        <div class="person-name">Mr Mok Boon Foong</div>
                                        <div class="person-title">Year Head (US)</div>
                                        <details>
                                            <summary>Email Address:</summary>
                                        </details>
                                    </div>
                                    <div class="person">
                                        <div class="person-name">Ms Per Ching Yee</div>
                                        <div class="person-title">Administration Manager</div>
                                        <details>
                                            <summary>Email Address:</summary>
                                        </details>
                                    </div>
                                    <div class="person">
                                        <div class="person-name">Ms Sin Puay San</div>
                                        <div class="person-title"></div>
                                        <details>
                                            <summary>Email Address:</summary>
                                        </details>
                                    </div>
                                    <div class="person">
                                        <div class="person-name">Mr Kenny</div>
                                        <div class="person-title">Operations Manager</div>
                                        <details>
                                            <summary>Email Address:</summary>
                                        </details>
                                    </div>
                                    <div class="person">
                                        <div class="person-name">Mr Gan Hui Kok Martin</div>
                                        <div class="person-title">Operations Manager</div>
                                        <details>
                                            <summary>Email Address:</summary>
                                        </details>
                                    </div>
                                    <div class="person">
                                        <div class="person-name">Ms Lim Beiyi Michelle</div>
                                        <div class="person-title">LH/Math &amp; Student Well-Being</div>
                                        <details>
                                            <summary>Email Address:</summary>lim_beiyi_michelle@moe.edu.sg
                                        </details>
                                    </div>
                                    <div class="person">
                                        <div class="person-name">Ms Vidya Premapadmanabhan</div>
                                        <div class="person-title">LH/EL</div>
                                        <details>
                                            <summary>Email Address:</summary>
                                        </details>
                                    </div>
                                    <div class="person">
                                        <div class="person-name">Mr Chen Weiguo Jeremy</div>
                                        <div class="person-title">LH/Science</div>
                                        <details>
                                            <summary>Email Address:</summary>chen_weiguo_jeremy@moe.edu.sg
                                        </details>
                                    </div>
                                    <div class="person">
                                        <div class="person-name">Mr Wong Mingwei</div>
                                        <div class="person-title">SH/Student Leadership</div>
                                        <details>
                                            <summary>Email Address:</summary>wong_mingwei@moe.edu.sg
                                        </details>
                                    </div>
                                    <div class="person">
                                        <div class="person-name">Mdm Ng Hui Yin</div>
                                        <div class="person-title">SH/Discipline</div>
                                        <details>
                                            <summary>Email Address:</summary>ng_hui_yin@moe.edu.sg
                                        </details>
                                    </div>
                                    <div class="person">
                                        <div class="person-name">Ms Nurul Ain Bte Kamaldin</div>
                                        <div class="person-title">SH/PE &amp; CCA</div>
                                        <details>
                                            <summary>Email Address:</summary>nurul_ain_kamaldin@moe.edu.sg
                                        </details>
                                    </div>
                                    <div class="person">
                                        <div class="person-name">Mdm Alvina Loganathan</div>
                                        <div class="person-title">SH-CCE</div>
                                        <details>
                                            <summary>Email Address:</summary>
                                        </details>
                                    </div>
                                </div>
                                <div class="yck-component">
                                    <div class="button-container">
                                        <a href="#top" class="button">Back to Top</a>
                                    </div>
                                </div>
                                <hr>
                                <div class="section-title">Teaching Staff</div>
                                <div class="teaching-staff-section">
                                    <div class="department">
                                        <div class="department-name">Design and Enterprise Department</div>
                                        <div class="people-grid">
                                            <div class="person" id="michaelwilliamcartwright">
                                                <div class="person-name">Mr Michael William Cartwright</div>
                                                <div class="person-title">Music</div>
                                                <details>
                                                    <summary>Email Address:</summary>michael_william_cartwright@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="tanbockleongchristopherjimmy">
                                                <div class="person-name">Mr Tan Bock Leong Christopher Jimmy</div>
                                                <div class="person-title">Art</div>
                                                <details>
                                                    <summary>Email Address:</summary>tan_bock_leong_christopher@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="thamhwijindarren">
                                                <div class="person-name">Mr Tham Hwi Jin Darren</div>
                                                <div class="person-title">Art</div>
                                                <details>
                                                    <summary>Email Address:</summary>tham_hwi_jin_darren@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="yipsengyiam">
                                                <div class="person-name">Mr Yip Seng Yiam</div>
                                                <div class="person-title">Art</div>
                                                <details>
                                                    <summary>Email Address:</summary>yip_seng_yiam@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="adelenair">
                                                <div class="person-name">Mrs Adele Nair</div>
                                                <div class="person-title">NFS</div>
                                                <details>
                                                    <summary>Email Address:</summary>adele_louise_williams@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="weesohyepatrick">
                                                <div class="person-name">Mr Wee Soh Ye Patrick</div>
                                                <div class="person-title">D&amp;T</div>
                                                <details>
                                                    <summary>Email Address:</summary>wee_soh_ye_patrick@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="sutinahbtesujaair">
                                                <div class="person-name">Mdm Sutinah Bte Sujaair</div>
                                                <div class="person-title">NFS</div>
                                                <details>
                                                    <summary>Email Address:</summary>sutinah_sujaair@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="limliwhey">
                                                <div class="person-name">Ms Lim Li Whey</div>
                                                <div class="person-title">NFS</div>
                                                <details>
                                                    <summary>Email Address:</summary>lim_li_whey@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="albertong">
                                                <div class="person-name">Mr Albert Ong</div>
                                                <div class="person-title">D&amp;T</div>
                                                <details>
                                                    <summary>Email Address:</summary>ong_tiong_guan_albert@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="limcheewee">
                                                <div class="person-name">Mr Lim Chee Wee</div>
                                                <div class="person-title">D&amp;T</div>
                                                <details>
                                                    <summary>Email Address:</summary>lim_chee_wee@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="liuxuefang">
                                                <div class="person-name">Mdm Liu Xue Fang</div>
                                                <div class="person-title">D&amp;T</div>
                                                <details>
                                                    <summary>Email Address:</summary>liu_xuefang@moe.edu.sg
                                                </details>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="department">
                                        <div class="department-name">Humanities Department</div>
                                        <div class="people-grid">
                                            <div class="person" id="ngwanhweedoreen">
                                                <div class="person-name">Mdm Ng Wan Hwee Doreen</div>
                                                <div class="person-title">ST/Hist</div>
                                                <details>
                                                    <summary>Email Address:</summary>ng_wan_hwee_doreen@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="nirmaladevis">
                                                <div class="person-name">Mdm Nirmala Devi S Tasiveran</div>
                                                <div class="person-title">ST/SS</div>
                                                <details>
                                                    <summary>Email Address:</summary>nirmala_devi_s_tasiveran@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="tewtjinlianamelia">
                                                <div class="person-name">Ms Tew Tjin Lian Amelia</div>
                                                <div class="person-title">SS</div>
                                                <details>
                                                    <summary>Email Address:</summary>tew_tjin_lian_amelia@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="loketuckluen">
                                                <div class="person-name">Mr Loke Tuck Luen</div>
                                                <div class="person-title">Hist</div>
                                                <details>
                                                    <summary>Email Address:</summary>loke_tuck_luen@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="laujieruijezreel">
                                                <div class="person-name">Ms Lau Jie Rui Jezreel</div>
                                                <div class="person-title">Geog</div>
                                                <details>
                                                    <summary>Email Address:</summary>lau_jie_rui_jezreel@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="rohinidoayavoo">
                                                <div class="person-name">Ms Rohini D/O Ayavoo</div>
                                                <div class="person-title">Geog</div>
                                                <details>
                                                    <summary>Email Address:</summary>rohini_ayavoo@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="chuasockhuang">
                                                <div class="person-name">Mdm Chua Sock Huang</div>
                                                <div class="person-title">SS Teacher</div>
                                                <details>
                                                    <summary>Email Address:</summary>chua_sock_huang@moe.edu.sg
                                                </details>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="department">
                                        <div class="department-name">Mathematics and Principles of Accounts</div>
                                        <div class="people-grid">
                                            <div class="person" id="gauwriskumar">
                                                <div class="person-name">Ms Gauwri S Kumar</div>
                                                <div class="person-title"></div>
                                                <details>
                                                    <summary>Email Address:</summary>
                                                </details>
                                            </div>
                                            <div class="person" id="foosiankoksimon">
                                                <div class="person-name">Mr Foo Sian Kok Simon</div>
                                                <div class="person-title"></div>
                                                <details>
                                                    <summary>Email Address:</summary>foo_sian_kok_simon@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="georgecuthbertjoseph">
                                                <div class="person-name">Mr George Cuthbert Joseph</div>
                                                <div class="person-title">POA</div>
                                                <details>
                                                    <summary>Email Address:</summary>george_cuthbert_joseph@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="leechingfong">
                                                <div class="person-name">Mdm Lee Ching Fong</div>
                                                <div class="person-title"></div>
                                                <details>
                                                    <summary>Email Address:</summary>lee_ching_fong@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="tanthiamboon">
                                                <div class="person-name">Mr Tan Thiam Boon</div>
                                                <div class="person-title"></div>
                                                <details>
                                                    <summary>Email Address:</summary>tan_thiam_boon@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="ngmangchung">
                                                <div class="person-name">Mr Ng Mang Chung</div>
                                                <div class="person-title"></div>
                                                <details>
                                                    <summary>Email Address:</summary>ng_mang_chung@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="tanhanzhongmark">
                                                <div class="person-name">Mr Tan Han Zhong, Mark</div>
                                                <div class="person-title">Math, POA</div>
                                                <details>
                                                    <summary>Email Address:</summary>tan_han_zhong_mark@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="angpengjujude">
                                                <div class="person-name">Mr Ang Pengju Jude</div>
                                                <div class="person-title">POA</div>
                                                <details>
                                                    <summary>Email Address:</summary>ang_pengju_jude@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="anniematthews">
                                                <div class="person-name">Mdm Annie Matthews</div>
                                                <div class="person-title">Teacher</div>
                                                <details>
                                                    <summary>Email Address:</summary>annie_matthews@moe.edu.sg
                                                </details>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="department">
                                        <div class="department-name">Mother Tongue Languages Department</div>
                                        <div class="people-grid">
                                            <div class="person" id="sitiaishabteahmatyusop">
                                                <div class="person-name">Mdm Siti Aisha Bte Ahmat Yusop</div>
                                                <div class="person-title">ST/ML</div>
                                                <details>
                                                    <summary>Email Address:</summary>siti_aisha_ahmat_yusop@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="yeyuluan">
                                                <div class="person-name">Mdm Ye Yuluan</div>
                                                <div class="person-title">ST/CL</div>
                                                <details>
                                                    <summary>Email Address:</summary>ye_yuluan@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="gohyufan">
                                                <div class="person-name">Ms Goh Yu Fan</div>
                                                <div class="person-title">CL</div>
                                                <details>
                                                    <summary>Email Address:</summary>goh_yu_fan@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="limlimay">
                                                <div class="person-name">Ms Lim Li May</div>
                                                <div class="person-title">CL</div>
                                                <details>
                                                    <summary>Email Address:</summary>lim_li_may@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="tanchunbuei">
                                                <div class="person-name">Ms Tan Chun Buei</div>
                                                <div class="person-title"></div>
                                                <details>
                                                    <summary>Email Address:</summary>tan_chun_buei@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="chikingkiok">
                                                <div class="person-name">Mdm Chi King Kiok</div>
                                                <div class="person-title">CL</div>
                                                <details>
                                                    <summary>Email Address:</summary>chi_king_kiok@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="xuxiaohong">
                                                <div class="person-name">Ms Xu Xiaohong</div>
                                                <div class="person-title">CL</div>
                                                <details>
                                                    <summary>Email Address:</summary>xu_xiaohong@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="limhuiqi">
                                                <div class="person-name">Mdm Lim Hui Qi</div>
                                                <div class="person-title">CL Teacher</div>
                                                <details>
                                                    <summary>Email Address:</summary>lim_hui_qi@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="ammaniammalilango">
                                                <div class="person-name">Mrs Ammani Ammal Ilango</div>
                                                <div class="person-title">TL</div>
                                                <details>
                                                    <summary>Email Address:</summary>ammani_ammal_ilango@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="nurrafizahbtesafiee">
                                                <div class="person-name">Mdm Nur Rafizah Bte Safiee</div>
                                                <div class="person-title">ML</div>
                                                <details>
                                                    <summary>Email Address:</summary>nur_rafizah_safiee@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="muhammadfarhanbinzailani">
                                                <div class="person-name">Mr Muhammad Farhan Bin Zailani</div>
                                                <div class="person-title">ML Teacher</div>
                                                <details>
                                                    <summary>Email Address:</summary>muhammad_farhan_zailani@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="rathidebishanmugam">
                                                <div class="person-name">Mdm Rathidevi Shanmugam</div>
                                                <div class="person-title">TL</div>
                                                <details>
                                                    <summary>Email Address:</summary>rathidevi_shanmugam@moe.edu.sg
                                                </details>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="department">
                                        <div class="department-name">Physical Education Department</div>
                                        <div class="people-grid">
                                            <div class="person" id="weedaigi">
                                                <div class="person-name">Mr Wee Daigi</div>
                                                <div class="person-title"></div>
                                                <details>
                                                    <summary>Email Address:</summary>wee_daigi@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="leongngannyunanna">
                                                <div class="person-name">Ms Leong Ngan Nyun Anna</div>
                                                <div class="person-title"></div>
                                                <details>
                                                    <summary>Email Address:</summary>leong_ngan_nyun_anna@moe.edu.sg
                                                </details>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="department">
                                        <div class="department-name">Science Department</div>
                                        <div class="people-grid">
                                            <div class="person" id="limmengchooemily">
                                                <div class="person-name">Mdm Lim Meng Choo Emily</div>
                                                <div class="person-title">ST/Chem</div>
                                                <details>
                                                    <summary>Email Address:</summary>lim_meng_choo_emily@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="sarasvathyd">
                                                <div class="person-name">Mdm Sarasvathy D/O Sivalingam S</div>
                                                <div class="person-title"></div>
                                                <details>
                                                    <summary>Email Address:</summary>sarasvathy_sivalingam@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="teohweehong">
                                                <div class="person-name">Ms Teo Hwee Hong</div>
                                                <div class="person-title"></div>
                                                <details>
                                                    <summary>Email Address:</summary>teo_hwee_hong@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="mvijeyaakumaran">
                                                <div class="person-name">Mr M Vijeyaa Kumaran</div>
                                                <div class="person-title"></div>
                                                <details>
                                                    <summary>Email Address:</summary>m_vijeyaa_kumaran@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="foogermaine">
                                                <div class="person-name">Ms Foo Ger Maine</div>
                                                <div class="person-title"></div>
                                                <details>
                                                    <summary>Email Address:</summary>foo_ger_maine@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="ongxiaoyun">
                                                <div class="person-name">Ms Ong Xiao Yun</div>
                                                <div class="person-title"></div>
                                                <details>
                                                    <summary>Email Address:</summary>ong_xiao_yun@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="gohkokhoeoctave">
                                                <div class="person-name">Mr Goh Kok Hoe Octave</div>
                                                <div class="person-title">Science</div>
                                                <details>
                                                    <summary>Email Address:</summary>goh_kok_hoe_octave@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="yeosailinconnie">
                                                <div class="person-name">Mdm Yeo Sai Lin Connie</div>
                                                <div class="person-title"></div>
                                                <details>
                                                    <summary>Email Address:</summary>yeo_sai_lin_connie@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="teohweepeng">
                                                <div class="person-name">Mdm Teo Hwee Peng</div>
                                                <div class="person-title">Science</div>
                                                <details>
                                                    <summary>Email Address:</summary>teo_hwee_peng@moe.edu.sg
                                                </details>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="department">
                                        <div class="department-name">English Language Department</div>
                                        <div class="people-grid">
                                            <div class="person" id="chongnyukfoong">
                                                <div class="person-name">Mdm Chong Nyuk Foong</div>
                                                <div class="person-title">ST/EL</div>
                                                <details>
                                                    <summary>Email Address:</summary>chong_nyuk_foong@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="chyeyenyenaudrey">
                                                <div class="person-name">Ms Chye Yen Yen Audrey</div>
                                                <div class="person-title"></div>
                                                <details>
                                                    <summary>Email Address:</summary>chye_yen_yen_audrey@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="lohshihui">
                                                <div class="person-name">Ms Loh Shihui</div>
                                                <div class="person-title"></div>
                                                <details>
                                                    <summary>Email Address:</summary>loh_shihui@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="eepohlam">
                                                <div class="person-name">Mr Ee Poh Lam</div>
                                                <div class="person-title"></div>
                                                <details>
                                                    <summary>Email Address:</summary>ee_poh_lam@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="vijayadorajaratanam">
                                                <div class="person-name">Mdm Vijaya D/O Rajaratanam</div>
                                                <div class="person-title"></div>
                                                <details>
                                                    <summary>Email Address:</summary>vijaya_rajaratanam@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="ongjoohuaycindy">
                                                <div class="person-name">Mrs Ong Joo Huay Cindy</div>
                                                <div class="person-title"></div>
                                                <details>
                                                    <summary>Email Address:</summary>ong_joo_huay_cindy@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="chonglaikhar">
                                                <div class="person-name">Mdm Chong Lai Khar</div>
                                                <div class="person-title"></div>
                                                <details>
                                                    <summary>Email Address:</summary>chong_lai_khar@moe.edu.sg
                                                </details>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="yck-component">
                                    <div class="button-container">
                                        <a href="#top" class="button">Back to Top</a>
                                    </div>
                                </div>
                                <div class="section-title" id="Non-teaching-Staff">Non-Teaching Staff</div>
                                <div class="non-teaching-staff-section">
                                    <div class="staff-group">
                                        <div class="group-name">Student Support</div>
                                        <div class="people-grid">
                                            <div class="person" id="kohkwekchoong">
                                                <div class="person-name">Mr Koh Kwek Choong</div>
                                                <div class="person-title">Allied Educator (Counsellor)</div>
                                                <details>
                                                    <summary>Email Address:</summary>koh_kwek_choong@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="pohsheeyean">
                                                <div class="person-name">Ms Poh Shee Yean</div>
                                                <div class="person-title">Senior Allied Educator (Counsellor)</div>
                                                <details>
                                                    <summary>Email Address:</summary>poh_shee_yean@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="carmeliatriciaarriola">
                                                <div class="person-name">Ms Carmelia Tricia Arriola</div>
                                                <div class="person-title">Lead Allied Educator (LBS)</div>
                                                <details>
                                                    <summary>Email Address:</summary>carmelia_tricia_arriola@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="chowwonhow">
                                                <div class="person-name">Mr Chow Won How</div>
                                                <div class="person-title">Student Welfare Officer</div>
                                                <details>
                                                    <summary>Email Address:</summary>chow_won_how@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="pehyamkhim">
                                                <div class="person-name">Mr Peh Yam Khim</div>
                                                <div class="person-title">SEN Officer</div>
                                                <details>
                                                    <summary>Email Address:</summary>Peh_Yam_Khim@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="anbalaghid">
                                                <div class="person-name">Ms Anbalaghi D/O Saravanan</div>
                                                <div class="person-title">Uplift Support Staff</div>
                                                <details>
                                                    <summary>Email Address:</summary>anbalagi_saravanan@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="isaacling">
                                                <div class="person-name">Mr Isaac Ling</div>
                                                <div class="person-title">ECG Counsellor</div>
                                                <details>
                                                    <summary>Email Address:</summary>ling_liang_wei_isaac@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="nurhidayahbtemsaharudin">
                                                <div class="person-name">Ms Nur Hidayah Bte M Saharudin</div>
                                                <div class="person-title">SEN Officer</div>
                                                <details>
                                                    <summary>Email Address:</summary>nur_hidayah_m_saharudin@moe.edu.sg
                                                </details>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="staff-group">
                                        <div class="group-name">Administrative Support</div>
                                        <div class="people-grid">
                                            <div class="person" id="aminahbtesalamon">
                                                <div class="person-name">Mdm Aminah Bte Salamon</div>
                                                <div class="person-title">Corporate Support Officer</div>
                                                <details>
                                                    <summary>Email Address:</summary>aminah_salamon@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="zamabteadim">
                                                <div class="person-name">Ms Zama Bte Adim</div>
                                                <div class="person-title">Administrative Executive</div>
                                                <details>
                                                    <summary>Email Address:</summary>zama_adim@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="nurkhalidah">
                                                <div class="person-name">Mdm Nur Khalidah</div>
                                                <div class="person-title">Administrative Executive</div>
                                                <details>
                                                    <summary>Email Address:</summary>nur_khalidah_mohamed_khir@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="weekweelendoreen">
                                                <div class="person-name">Mdm Wee Kwee Len Doreen</div>
                                                <div class="person-title">Asst Support Officer</div>
                                                <details>
                                                    <summary>Email Address:</summary>wee_kwee_len_doreen@moe.edu.sg
                                                </details>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="staff-group">
                                        <div class="group-name">Technical Support</div>
                                        <div class="people-grid">
                                            <div class="person" id="kumkumvinodsingh">
                                                <div class="person-name">Mrs Kumkum Vinod Singh</div>
                                                <div class="person-title">ICT Manager</div>
                                                <details>
                                                    <summary>Email Address:</summary>kumkum_vinod_singh@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="gawpuaykeongpatrick">
                                                <div class="person-name">Mr Gaw Puay Keong Patrick</div>
                                                <div class="person-title">D&amp;T Workshop</div>
                                                <details>
                                                    <summary>Email Address:</summary>gaw_puay_keong_patrick@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="zulkarnainbinmahfudz">
                                                <div class="person-name">Mr Zulkarnain Bin Mahfudz</div>
                                                <div class="person-title">D&amp;T Workshop</div>
                                                <details>
                                                    <summary>Email Address:</summary>zulkarnain_mahfudz@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="hamizahbintehassan">
                                                <div class="person-name">Ms Hamizah Binte Hassan</div>
                                                <div class="person-title">Science Lab</div>
                                                <details>
                                                    <summary>Email Address:</summary>hamizah_hassan@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="tantecklinadeline">
                                                <div class="person-name">Mdm Tan Teck Lin Adeline</div>
                                                <div class="person-title">Science Lab</div>
                                                <details>
                                                    <summary>Email Address:</summary>tan_teck_lin_adeline@moe.edu.sg
                                                </details>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="staff-group">
                                        <div class="group-name">Operations Support</div>
                                        <div class="people-grid">
                                            <div class="person" id="suriatibtesuparthi">
                                                <div class="person-name">Mdm Suriati Bte Suparthi</div>
                                                <div class="person-title"></div>
                                                <details>
                                                    <summary>Email Address:</summary>suriati_suparthi@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="krishnamoorthys">
                                                <div class="person-name">Mr Krishnamoorthy S/O Sauraju</div>
                                                <div class="person-title"></div>
                                                <details>
                                                    <summary>Email Address:</summary>krishnamoorthy_saurajlu@moe.edu.sg
                                                </details>
                                            </div>
                                            <div class="person" id="devi">
                                                <div class="person-name">Mdm Devi</div>
                                                <div class="person-title"></div>
                                                <details>
                                                    <summary>Email Address:</summary>
                                                </details>
                                            </div>
                                            <div class="person" id="wongaunteck">
                                                <div class="person-name">Mr Wong Aun Teck</div>
                                                <div class="person-title"></div>
                                                <details>
                                                    <summary>Email Address:</summary>wong_aun_teck@moe.edu.sg
                                                </details>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="staff-group">
                                        <div class="group-name">Non-MOE Staff</div>
                                        <div class="people-grid">
                                            <div class="person" id="kohbakweikelvin">
                                                <div class="person-name">Mr Koh Bak Wei Kelvin</div>
                                                <div class="person-title">Desktop Engineer (NCS)</div>
                                                <details>
                                                    <summary>Email Address:</summary>
                                                </details>
                                            </div>
                                            <div class="person" id="nurnashiranadeem">
                                                <div class="person-name">Ms Nur Nashira Nadeem Bte Abdullah</div>
                                                <div class="person-title">Desktop Engineer (NCS)</div>
                                                <details>
                                                    <summary>Email Address:</summary>
                                                </details>
                                            </div>
                                            <div class="person" id="kwanyeowhweejeff">
                                                <div class="person-name">Mr Kwan Yeow Hwee Jeff</div>
                                                <div class="person-title">ICT/AV Executive</div>
                                                <details>
                                                    <summary>Email Address:</summary>
                                                </details>
                                            </div>
                                            <div class="person" id="yongchweeyock">
                                                <div class="person-name">Mdm Yong Chwee Yock</div>
                                                <div class="person-title">Kitchen Assistant</div>
                                                <details>
                                                    <summary>Email Address:</summary>
                                                </details>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="yck-component">
                                <div class="button-container">
                                    <a href="#top" class="button">Back to Top</a>
                                </div>
                            </div>
                        </div>