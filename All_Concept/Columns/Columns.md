# learnTailwind

> How to use Tailwind

---

## Content

-   [Utility First](https://github.com/SauBanh/learnTailwind)
-   [Color](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Color/Color.md)
-   [Container Spacing](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Container_Spacing/Container_Spacing.md)
-   [Typography](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Typography/Typography.md)
-   [Sizing](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Sizing/Sizing.md)
-   [Layout Position](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Layout_Position/Layout_Position.md)
-   [Backgrounds Shadows](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Background_Shadows/Backgrounds_Shadows.md)
-   [Borders](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Borders/Borders.md)
-   [Filters](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Filters/Filters.md)
-   [Interactivity](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Interactivity/Interactivity.md)
-   [Breakpoints](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Breakpoints/Breakpoints.md)
-   <a style="color: red; text-decoration: underline">Columns</a>
-   [Flex](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Flex/Flex.md)
-   [Grid](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Grid/Grid.md)
-   [Transform Transition](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Transform_Transition/Transform_Transition.md)
-   [Animation](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Animation/Animation.md)
-   [Customization](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Customization/Customization.md)

---

## Columns

### HTML

```c
<div class="columns-2 gap-8">
    <img class="w-full" src="/assets/img/img1.jpg" />
    <img class="w-full" src="/assets/img/img2.jpg" />
    <img class="w-full break-after-column" src="/assets/img/img3.jpg" />
    <img class="w-full" src="/assets/img/img4.jpg" />
</div>
<div class="columns-3 gap-24">
    <img class="w-full" src="/assets/img/img3.jpg" />
    <img class="w-full break-before-column" src="/assets/img/img4.jpg" />
    <img class="w-full" src="/assets/img/img5.jpg" />
    <img class="w-full" src="/assets/img/img6.jpg" />
    <img class="w-full" src="/assets/img/img7.jpg" />
</div>
<div class="columns-3xs">
    <!-- Video Aspect Ratio -->
    <img class="w-full aspect-video" src="/assets/img/img8.jpg" />
    <!-- Square Aspect Ratio -->
    <img class="w-full aspect-square" src="/assets/img/img9.jpg" />
    <img class="w-full break" src="/assets/img/img1.jpg" />
    <img class="w-full" src="/assets/img/img2.jpg" />
</div>
```

### Column Classes

| Tailwind              | css                             |
| --------------------- | ------------------------------- |
| columns-1 columns: 1; |
| columns-2             | columns: 2;                     |
| columns-3             | columns: 3;                     |
| columns-4             | columns: 4;                     |
| columns-5             | columns: 5;                     |
| columns-6             | columns: 6;                     |
| columns-7             | columns: 7;                     |
| columns-8             | columns: 8;                     |
| columns-9             | columns: 9;                     |
| columns-10            | columns: 10;                    |
| columns-11            | columns: 11;                    |
| columns-12            | columns: 12;                    |
| columns-auto          | columns: auto;                  |
| columns-3xs           | columns: 16rem; /\* 256px \*/   |
| columns-2xs           | columns: 18rem; /\* 288px \*/   |
| columns-xs            | columns: 20rem; /\* 320px \*/   |
| columns-sm            | columns: 24rem; /\* 384px \*/   |
| columns-md            | columns: 28rem; /\* 448px \*/   |
| columns-lg            | columns: 32rem; /\* 512px \*/   |
| columns-xl            | columns: 36rem; /\* 576px \*/   |
| columns-2xl           | columns: 42rem; /\* 672px \*/   |
| columns-3xl           | columns: 48rem; /\* 768px \*/   |
| columns-4xl           | columns: 56rem; /\* 896px \*/   |
| columns-5xl           | columns: 64rem; /\* 1024px \* / |
| columns-6xl           | columns: 72rem; /\* 1152px \* / |
| columns-7xl           | columns: 80rem; /\* 1280px \* / |

### Break After

| Tailwind               | css                      |
| ---------------------- | ------------------------ |
| break-after-auto       | break-after: auto;       |
| break-after-avoid      | break-after: avoid;      |
| break-after-all        | break-after: all;        |
| break-after-avoid-page | break-after: avoid-page; |
| break-after-page       | break-after: page;       |
| break-after-left       | break-after: left;       |
| break-after-right      | break-after: right;      |
| break-after-column     | break-after: column;     |

### Break Before

| Tailwind                | css                       |
| ----------------------- | ------------------------- |
| reak-before-auto        | break-before: auto;       |
| break-before-avoid      | break-before: avoid;      |
| break-before-all        | break-before: all;        |
| break-before-avoid-page | break-before: avoid-page; |
| break-before-page       | break-before: page;       |
| break-before-left       | break-before: left;       |
| break-before-right      | break-before: right;      |
| break-before-column     | break-before: column;     |
