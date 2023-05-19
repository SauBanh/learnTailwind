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
-   <a style="color: red; text-decoration: underline">Filters</a>
-   [Interactivity](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Interactivity/Interactivity.md)
-   [Breakpoints](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Breakpoints/Breakpoints.md)
-   [Columns](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Columns/Columns.md)
-   [Flex](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Flex/Flex.md)
-   [Grid](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Grid/Grid.md)
-   [Transform Transition](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Transform_Transition/Transform_Transition.md)
-   [Animation](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Animation/Animation.md)
-   [Customization](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Customization/Customization.md)

---

## Filters

### Blur

```c
<div class="blur-none">
    Lorem ipsum dolor sit amet consectetur, adipisicing elit. Itaque deserunt
    animi quas aliquam consectetur ut obcaecati voluptas repudiandae odit
    harum?
</div>
<div class="blur-sm">
    Lorem ipsum dolor sit amet consectetur, adipisicing elit. Itaque deserunt
    animi quas aliquam consectetur ut obcaecati voluptas repudiandae odit
    harum?
</div>
<div class="blur-lg">
    <img class="w-48" src="/assets/img/img1.jpg" alt="" />
</div>
<div class="blur-2xl">
    <img class="w-48" src="/assets/img/img1.jpg" alt="" />
</div>
```

### Brightness

```c
<div class="brightness-50">
    <img class="w-48" src="/assets/img/img2.jpg" alt="" />
</div>
<div class="brightness-100">
    <img class="w-48" src="/assets/img/img2.jpg" alt="" />
</div>
<div class="brightness-150">
    <img class="w-48" src="/assets/img/img2.jpg" alt="" />
</div>
<div class="brightness-200">
    <img class="w-48" src="/assets/img/img2.jpg" alt="" />
</div>
```

### Contrast

```c
<div class="contrast-50">
    <img class="w-48" src="/assets/img/img2.jpg" alt="" />
</div>
<div class="contrast-100">
    <img class="w-48" src="/assets/img/img2.jpg" alt="" />
</div>
<div class="contrast-150">
    <img class="w-48" src="/assets/img/img2.jpg" alt="" />
</div>
<div class="contrast-200">
    <img class="w-48" src="/assets/img/img2.jpg" alt="" />
</div>
```

### Grayscale

```c
<div class="grayscale">
      <img class="w-48" src="/assets/img/img3.jpg" alt="" />
    </div>
```

### Invert

```c
<div class="invert">
    <img class="w-48" src="/assets/img/img3.jpg" alt="" />
</div>
```

### Sepia

```c
<div class="sepia">
    <img class="w-48" src="/assets/img/img3.jpg" alt="" />
</div>
```

### BlurHue Rotate

```c
<div class="hue-rotate-15">
    <img class="w-48" src="/assets/img/img3.jpg" alt="" />
</div>
<div class="hue-rotate-90">
    <img class="w-48" src="/assets/img/img3.jpg" alt="" />
</div>
<div class="hue-rotate-180">
    <img class="w-48" src="/assets/img/img3.jpg" alt="" />
</div>
<div class="hue-rotate-60">
    <img class="w-48" src="/assets/img/img3.jpg" alt="" />
</div>
```

### Saturate

```c
<div class="saturate-50">
    <img class="w-48" src="/assets/img/img4.jpg" alt="" />
</div>
<div class="saturate-100">
    <img class="w-48" src="/assets/img/img4.jpg" alt="" />
</div>
<div class="saturate-150">
    <img class="w-48" src="/assets/img/img4.jpg" alt="" />
</div>
<div class="saturate-200">
    <img class="w-48" src="/assets/img/img4.jpg" alt="" />
</div>
```

### Blur convert

| Tailwind  | css                 |
| --------- | ------------------- |
| blur-none | filter: blur(0);    |
| blur-sm   | filter: blur(4px);  |
| blur      | filter: blur(8px);  |
| blur-md   | filter: blur(12px); |
| blur-lg   | filter: blur(16px); |
| blur-xl   | filter: blur(24px); |
| blur-2xl  | filter: blur(40px); |
| blur-3xl  | filter: blur(64px); |

### Brightness

| Tailwind       | css                       |
| -------------- | ------------------------- |
| brightness-0   | filter: brightness(0);    |
| brightness-50  | filter: brightness(.5);   |
| brightness-75  | filter: brightness(.75);  |
| brightness-90  | filter: brightness(.9);   |
| brightness-95  | filter: brightness(.95);  |
| brightness-100 | filter: brightness(1);    |
| brightness-105 | filter: brightness(1.05); |
| brightness-110 | filter: brightness(1.1);  |
| brightness-125 | filter: brightness(1.25); |
| brightness-150 | filter: brightness(1.5);  |
| brightness-200 | filter: brightness(2);    |

### Contrast

| Tailwind     | css                     |
| ------------ | ----------------------- |
| contrast-0   | filter: contrast(0);    |
| contrast-50  | filter: contrast(.5);   |
| contrast-75  | filter: contrast(.75);  |
| contrast-100 | filter: contrast(1);    |
| contrast-125 | filter: contrast(1.25); |
| contrast-150 | filter: contrast(1.5);  |
| contrast-200 | filter: contrast(2);    |

### Hue Rotate

| Tailwind       | css                         |
| -------------- | --------------------------- |
| hue-rotate-0   | filter: hue-rotate(0deg);   |
| hue-rotate-15  | filter: hue-rotate(15deg);  |
| hue-rotate-30  | filter: hue-rotate(30deg);  |
| hue-rotate-60  | filter: hue-rotate(60deg);  |
| hue-rotate-90  | filter: hue-rotate(90deg);  |
| hue-rotate-180 | filter: hue-rotate(180deg); |
