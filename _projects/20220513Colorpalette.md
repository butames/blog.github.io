---
title: 'Palettes and Tables'
subtitle: 'My favorite color palette and learning to style a table'
date: 2022-05-13 00:06:55
featured_image: '/images/blog_images/2022-05-13-suncolors.gif'
---

## Styling a table in markdown

I love the tableau color blind palette^[1]. This particular palette is a series of blues, oranges, and greys that are easy on the eyes and help make viewing figures, tables, charts, and sundry visualizations quite pleasing. I have decided to capture those colors here, should I need to reference them for various projects. Additionally, I get to learn how to create stylized tables in Markdown. 

<style>
    .heatMap {
        width: 100%;
        font: 100%/30px 'Roboto', sans-serif;
        text-align: left;
    }
    .heatMap th {
        background: #ffffff;
        word-wrap: break-word;
        text-align: left;
    }
    .heatMap tr:nth-child(1) { background: #1170aa; }
    .heatMap tr:nth-child(2) { background: #5fa2ce; }
    .heatMap tr:nth-child(3) { background: #a2cce8; }
    .heatMap tr:nth-child(4) { background: #c85200; }
    .heatMap tr:nth-child(5) { background: #fc7d0b; }
    .heatMap tr:nth-child(6) { background: #ffbc79; }
    .heatMap tr:nth-child(7) { background: #57606c; }
    .heatMap tr:nth-child(8) { background: #7b848f; }
    .heatMap tr:nth-child(9) { background: #a3acb9; }
</style>

<div class="heatMap">

| Description   | HEX     | RGB             | CMYK               | 
|---------------|---------|-----------------| -------------------|
| Dark Blue     | #1170aa | 17, 112, 170    | 90%, 34%, 0%, 33%  |
| Medium Blue   | #5fa2ce | 95, 162, 206    | 54%, 21%, 0%, 19%  |
| Light Blue    | #a2cce8 | 163, 204, 233   |30%, 12%, 0%, 9%    |
| Dark Orange   | #c85200 | 200, 82, 0      | 0%, 59%, 100%, 22% |
| Medium Orange | #fc7f0a | 252, 125, 11    | 0%, 50%, 96%, 1%   |
| Light Orange  | #ffbc79 | 255, 188, 121   | 0%, 26%, 53%, 0%   |
| Dark Grey     | #57606c | 87, 96, 108     | 19%, 11%, 0%, 58%  |
| Medium Grey   | #7b848f | 123, 132, 143   | 14%, 8%, 0%, 44%   |
| Light Grey    | #a3acb9 | 164, 173, 186   | 12%, 7%, 0%, 27%   |

</div>

[^1]:[Tableau Color Palettes (discrete) - By Jeffrey B. Arnold](https://jrnold.github.io/ggthemes/reference/tableau_color_pal.html)
---
Banner Theme: Our star seen at different wavelengths by NASA Solar Dynamics Observatory (SDO) (Credit : NASA Goddard Visualization Studio / Tom Bridgman.)
