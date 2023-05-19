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
-   [Flex](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Flex/Flex.md)
-   <a style="color: red; text-decoration: underline">Grid</a>
-   [Transform Transition](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Transform_Transition/Transform_Transition.md)
-   [Animation](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Animation/Animation.md)
-   [Customization](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Customization/Customization.md)

---

## Grid

### Grid cols and rows

```c
<div class="grid grid-cols-3 grid-rows-4 gap-4 w-100 bg-gray-100">
    <div class="p-10 border border-blue-600 bg-blue-100">01</div>
    <div class="p-10 border border-blue-600 bg-blue-100">02</div>
    <div class="p-10 border border-blue-600 bg-blue-100">03</div>
    <div class="p-10 border border-blue-600 bg-blue-100">04</div>
    <div class="p-10 border border-blue-600 bg-blue-100">05</div>
    <div class="p-10 border border-blue-600 bg-blue-100">06</div>
    <div class="p-10 border border-blue-600 bg-blue-100">07</div>
    <div class="p-10 border border-blue-600 bg-blue-100">08</div>
    <div class="p-10 border border-blue-600 bg-blue-100">09</div>
</div>
```

### Col and row span

```c
<div class="grid grid-cols-3 gap-4 w-100 bg-gray-100">
    <div
    class="col-span-2 row-span-2 p-10 border border-blue-600 bg-blue-100"
    >
    01
    </div>
    <div class="p-10 border border-blue-600 bg-blue-100">02</div>
    <div class="p-10 border border-blue-600 bg-blue-100">03</div>
    <div class="p-10 border border-blue-600 bg-blue-100">04</div>
    <div class="p-10 border border-blue-600 bg-blue-100">05</div>
    <div class="p-10 border border-blue-600 bg-blue-100">06</div>
    <div class="col-span-3 p-10 border border-blue-600 bg-blue-100">07</div>
    <div class="p-10 border border-blue-600 bg-blue-100">08</div>
    <div class="col-span-2 p-10 border border-blue-600 bg-blue-100">09</div>
</div>
```

### Grid Template Columns

| Tailwind       | css                                                |
| -------------- | -------------------------------------------------- |
| grid-cols-1    | grid-template-columns: repeat(1, minmax(0, 1fr));  |
| grid-cols-2    | grid-template-columns: repeat(2, minmax(0, 1fr));  |
| grid-cols-3    | grid-template-columns: repeat(3, minmax(0, 1fr));  |
| grid-cols-4    | grid-template-columns: repeat(4, minmax(0, 1fr));  |
| grid-cols-5    | grid-template-columns: repeat(5, minmax(0, 1fr));  |
| grid-cols-6    | grid-template-columns: repeat(6, minmax(0, 1fr));  |
| grid-cols-7    | grid-template-columns: repeat(7, minmax(0, 1fr));  |
| grid-cols-8    | grid-template-columns: repeat(8, minmax(0, 1fr));  |
| grid-cols-9    | grid-template-columns: repeat(9, minmax(0, 1fr));  |
| grid-cols-10   | grid-template-columns: repeat(10, minmax(0, 1fr)); |
| grid-cols-11   | grid-template-columns: repeat(11, minmax(0, 1fr)); |
| grid-cols-12   | grid-template-columns: repeat(12, minmax(0, 1fr)); |
| grid-cols-none | grid-template-columns: none;                       |

### Grid Template Rows

| Tailwind       | css                                            |
| -------------- | ---------------------------------------------- |
| grid-rows-1    | grid-template-rows: repeat(1, minmax(0, 1fr)); |
| grid-rows-2    | grid-template-rows: repeat(2, minmax(0, 1fr)); |
| grid-rows-3    | grid-template-rows: repeat(3, minmax(0, 1fr)); |
| grid-rows-4    | grid-template-rows: repeat(4, minmax(0, 1fr)); |
| grid-rows-5    | grid-template-rows: repeat(5, minmax(0, 1fr)); |
| grid-rows-6    | grid-template-rows: repeat(6, minmax(0, 1fr)); |
| grid-rows-none | grid-template-rows: none;                      |
