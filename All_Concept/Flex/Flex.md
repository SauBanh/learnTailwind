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
-   [Columns](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Columns/Columns.md)
-   <a style="color: red; text-decoration: underline">Flex</a>
-   [Grid](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Grid/Grid.md)
-   [Transform Transition](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Transform_Transition/Transform_Transition.md)
-   [Animation](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Animation/Animation.md)
-   [Customization](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Customization/Customization.md)

---

## Flex

### Flex and alignment

```c
<div
    class="flex flex-wrap h-72 w-100 bg-gray-100 justify-around items-center"
>
    <div class="p-10 border border-blue-600 bg-blue-100">01</div>
    <div class="p-10 border border-blue-600 bg-blue-100">02</div>
    <div class="self-start p-10 border border-blue-600 bg-blue-100">03</div>
    <div class="self-end p-10 border border-blue-600 bg-blue-100">04</div>
</div>
```

### Flex Column, Gap and Order

```c
<div
    class="flex flex-col gap-4 w-100 bg-gray-200 justify-around items-center"
>
    <div class="order-4 p-10 border border-blue-600 bg-blue-100">01</div>
    <div class="order-1 p-10 border border-blue-600 bg-blue-100">02</div>
    <div class="p-10 border border-blue-600 bg-blue-100">03</div>
    <div class="p-10 border border-blue-600 bg-blue-100">04</div>
</div>
```

### Grow and shrink

```c
<div class="flex w-100 bg-gray-300">
    <!-- flex-none: Prevent item from growing or shrinking -->
    <div class="w-64 flex-none p-10 border border-blue-600 bg-blue-100">
    01
    </div>
    <!-- flex-initial:  Allow item to shrink but not grow, taking into account its initial size  -->
    <div class="w-64 flex-initial p-10 border border-blue-600 bg-blue-100">
    02
    </div>
    <!-- flex-auto: Allow item to grow and shrink, taking into account its initial size -->
    <div class="w-64 flex-auto p-10 border border-blue-600 bg-blue-100">
    03
    </div>
    <!-- flex-1: Allow item to grow and shrink as needed, ignoring its initial size -->
    <div class="w-64 flex-1 p-10 border border-blue-600 bg-blue-100">04</div>
    <div class="p-10 border border-blue-600 bg-blue-100">05</div>
    <div class="p-10 border border-blue-600 bg-blue-100">06</div>
    <div class="p-10 border border-blue-600 bg-blue-100">07</div>
</div>
```

### Justify Content

| Tailwind        | css                             |
| --------------- | ------------------------------- |
| justify-start   | justify-content: flex-start;    |
| justify-end     | justify-content: flex-end;      |
| justify-center  | justify-content: center;        |
| justify-between | justify-content: space-between; |
| justify-around  | justify-content: space-around;  |
| justify-evenly  | justify-content: space-evenly;  |
| items-start     | align-items: flex-start;        |
| items-end       | align-items: flex-end;          |
| items-center    | align-items: center;            |
| items-baseline  | align-items: baseline;          |
| items-stretch   | align-items: stretch;           |

### Flex Direction

| Tailwind          | css                             |
| ----------------- | ------------------------------- |
| flex-row          | flex-direction: row;            |
| flex-row-reverse  | flex-direction: row-reverse;    |
| flex-col          | flex-direction: column;         |
| flex-col-reverse  | flex-direction: column-reverse; |
| flex-wrap         | flex-wrap: wrap;                |
| flex-wrap-reverse | flex-wrap: wrap-reverse;        |
| flex-nowrap       | flex-wrap: nowrap;              |

### Flex Properties

| Tailwind     | css             | description                                                             |
| ------------ | --------------- | ----------------------------------------------------------------------- |
| flex-none    | flex: none;     | Prevent item from growing or shrinking                                  |
| flex-initial | flex: 0 1 auto; | Allow item to shrink but not grow, taking into account its initial size |
| flex-auto    | flex: 1 1 auto; | Allow item to grow and shrink, taking into account its initial size     |
| flex-1       | flex: 1 1 0%;   | Allow item to grow and shrink as needed, ignoring its initial size      |
