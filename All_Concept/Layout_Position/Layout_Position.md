# learnTailwind

> How to use Tailwind

---

## Content

-   [Utility First](https://github.com/SauBanh/learnTailwind)
-   [Color](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Color/Color.md)
-   [Container Spacing](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Container_Spacing/Container_Spacing.md)
-   [Typography](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Typography/Typography.md)
-   [Sizing](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Sizing/Sizing.md)
-   <a style="color: red; text-decoration: underline">Layout Position</a>
-   [Backgrounds Shadows](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Background_Shadows/Backgrounds_Shadows.md)
-   [Borders](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Borders/Borders.md)
-   [Filters](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Filters/Filters.md)
-   [Interactivity](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Interactivity/Interactivity.md)
-   [Breakpoints](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Breakpoints/Breakpoints.md)
-   [Columns](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Columns/Columns.md)
-   [Flex](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Flex/Flex.md)
-   [Grid](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Grid/Grid.md)
-   [Transform Transition](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Transform_Transition/Transform_Transition.md)
-   [Animation](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Animation/Animation.md)
-   [Customization](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Customization/Customization.md)

---

## Layout Position

### Positioning

```c
<div class="relative w-1/2 h-12 bg-red-200">
    <p>Relative parent</p>
    <div class="absolute bottom-0 right-0 bg-red-500">
    <p>Absolute child</p>
    </div>
</div>
```

### Top left corner

```c
<div class="relative h-32 w-32 bg-yellow-100">
    <div class="absolute left-0 top-0 h-16 w-16 bg-yellow-300">01</div>
</div>
```

### Top right corner

```c
<div class="relative h-32 w-32 bg-yellow-100">
    <div class="absolute top-0 right-0 h-16 w-16 bg-yellow-300">03</div>
</div>
```

### Bottom left corner

```c
<div class="relative h-32 w-32 bg-yellow-100">
    <div class="absolute bottom-0 left-0 h-16 w-16 bg-yellow-300">07</div>
</div>
```

### Bottom right corner

```c
<div class="relative h-32 w-32 bg-yellow-100">
    <div class="absolute bottom-0 right-0 h-16 w-16 bg-yellow-300">09</div>
</div>
```

### Span top edge

```c
<!-- Span top edge -->
<div class="relative h-32 w-32 bg-yellow-100">
    <div class="absolute inset-x-0 top-0 h-16 bg-yellow-300">02</div>
</div>
```

### Span left edge

```c
<div class="relative h-32 w-32 bg-yellow-100">
    <div class="absolute inset-y-0 left-0 w-16 bg-yellow-300">04</div>
</div>
```

### Span right edge

```c
<div class="relative h-32 w-32 bg-yellow-100">
    <div class="absolute inset-y-0 right-0 w-16 bg-yellow-300">06</div>
</div>
```

### Span bottom edge

```c
<div class="relative h-32 w-32 bg-yellow-100">
    <div class="absolute inset-x-0 bottom-0 h-16 bg-yellow-300">08</div>
</div>
```

### Display Classes

```c
<div>
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus
    <span class="inline">This is display inline and will wrap normally</span
    >sapiente ut rerum esse ullam provident, fugit
    <span class="inline-block"
    >This is display inline-block and will not extend beyond it's
    parent</span
    >eos quam
    <span class="block"
    >This is display block and will move to it's own line</span
    >
    reprehenderit est hic aut unde sequi, officia, ipsa amet doloribus
    ratione<span class="hidden"
    >This is display none and will not display at all</span
    >
    ad.
</div>
```

### Z-Index

```c
<div class="relative h-36">
    <div class="absolute left-10 w-24 h-24 bg-blue-200 z-40">1</div>
    <div class="absolute left-20 w-24 h-24 bg-blue-300">2</div>
    <div class="absolute left-40 w-24 h-24 bg-blue-400 z-10">3</div>
    <div class="absolute left-60 w-24 h-24 bg-blue-500 z-20">4</div>
    <div class="absolute left-80 w-24 h-24 bg-blue-600">5</div>
</div>
```

### Floats

```c
<div class="w-1/2">
    <img class="h-48 w-48 float-right" src="/assets/img/img1.jpg" />
    <p>
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Facere numquam
    voluptatem accusantium atque cupiditate nulla ratione saepe veniam, ex
    iure nisi mollitia sed rerum veritatis temporibus iusto! Molestiae,
    ratione doloribus?
    </p>
</div>
```

### Position Classes

| Tailwind | css                 |
| -------- | ------------------- |
| static   | position: static;   |
| fixed    | position: fixed;    |
| absolute | position: absolute; |
| relative | position: relative; |
| sticky   | position: sticky;   |

### Display Classes

| Tailwind     | css                    |
| ------------ | ---------------------- |
| block        | display: block;        |
| inline-block | display: inline-block; |
| inline       | display: inline;       |
| flex         | display: flex;         |
| inline-flex  | display: inline-flex;  |
| table        | display: table;        |
| grid         | display: grid;         |
| inline-grid  | display: inline-grid;  |
| contents     | display: contents;     |
| list-item    | display: list-item;    |
| hidden       | display: none;         |

### Z-Index

| Tailwind | css            |
| -------- | -------------- |
| z-0      | z-index: 0;    |
| z-10     | z-index: 10;   |
| z-20     | z-index: 20;   |
| z-30     | z-index: 30;   |
| z-40     | z-index: 40;   |
| z-50     | z-index: 50;   |
| z-auto   | z-index: auto; |

### Float

| Tailwind    | css           |
| ----------- | ------------- |
| float-right | float: right; |
| float-left  | float: left;  |
| float-none  | float: none;  |
