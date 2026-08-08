# A Hundred Thousand Billion Poems

This is a digital, interactive adaptation of Raymond Queneau's *Cent mille milliards de poèmes* (1961). 

## Overview
The book consists of 10 sonnets (14 lines each). Each line of a sonnet can be independently swapped out for the corresponding line from any of the other 9 sonnets. Since there are 14 lines and 10 options per line, this creates **$10^{14}$ (100 trillion / a hundred thousand billion) possible poems.**

This interactive web version simulates a split-page physical book, allowing you to:
- Turn individual line "strips" to explore new combinations.
- **Pin** specific lines that you like, so they stay in place while you shuffle the rest.
- **Shuffle** the unlocked pages to instantly generate a completely unique sonnet.
- Share your specific poem via a unique URL hash or copy it to your clipboard.

## Demo
The project is live on GitHub Pages! You can view it here:
**[https://sh0tybumbati.github.io/100k-billion-poems/](https://sh0tybumbati.github.io/100k-billion-poems/)**

## Technical Details
This is a lightweight, zero-dependency project built entirely with vanilla web technologies:
- **HTML5:** For the structure and accessibility of the poem lines.
- **CSS3:** Featuring a modern dark mode, glassmorphism UI, and 3D CSS transforms for the page-flipping animations.
- **Vanilla JavaScript:** To handle the permutation math, shuffling logic, URL state management, and clipboard integration.

## Usage
Simply open `index.html` in your favorite modern web browser, or visit the live link above.
