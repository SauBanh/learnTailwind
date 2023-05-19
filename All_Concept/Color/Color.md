# learnTailwind

> How to use Tailwind

---

## Content

-   [Utility First](https://github.com/SauBanh/learnTailwind)
-   <a style="color: red; text-decoration: underline">Color</a>
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
-   [Grid](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Grid/Grid.md)
-   [Transform Transition](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Transform_Transition/Transform_Transition.md)
-   [Animation](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Animation/Animation.md)
-   [Customization](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Customization/Customization.md)

---

## Color

### Text Colors

```c
<p class="text-black">Tailwind is awesome</p>
<p class="text-red-50">Tailwind is awesome</p>
<p class="text-red-100">Tailwind is awesome</p>
<p class="text-red-200">Tailwind is awesome</p>
<p class="text-red-300">Tailwind is awesome</p>
<p class="text-red-400">Tailwind is awesome</p>
<p class="text-red-500">Tailwind is awesome</p>
<p class="text-red-600">Tailwind is awesome</p>
<p class="text-red-700">Tailwind is awesome</p>
<p class="text-red-800">Tailwind is awesome</p>
<p class="text-red-900">Tailwind is awesome</p>
```

### Background Colors

```c
<div class="bg-slate-600">
    <p class="text-white">Tailwind is awesome</p>
</div>
<div class="bg-zinc-400">
    <p class="text-white">Tailwind is awesome</p>
</div>
<div class="bg-emerald-600">
    <p class="text-white">Tailwind is awesome</p>
</div>
```

### Text Underline

```c
<p class="underline text-red-700 decoration-red-700">Tailwind is awesome</p>
<p class="underline text-blue-700 decoration-blue-700">Tailwind is awesome<p>
```

### Border Colors

```c
<input class="border-2 border-rose-500" />
<input class="border-2 border-blue-300" />
<input class="border-2 border-purple-900" />
<input class="border-2 border-yellow-500" />
```

### Divide Colors

```c
<div class="divide-y divide-blue-200">
    <div>Item 1</div>
    <div>Item 2</div>
    <div>Item 4</div>
    <div>Item 5</div>
    <div>Item 6</div>
</div>
```

### Outline Colors

```c
<button class="outline outline-blue-500">Subscribe</button>
<button class="outline outline-purple-300">Subscribe</button>
<button class="outline outline-gray-500">Subscribe</button>
```

### Box Shadow Colors (Opacity defaults to 100, but you cans set it)

```c
<button class="bg-cyan-500 shadow-lg shadow-cyan-500">Subscribe</button>
<button class="bg-blue-500 shadow-lg shadow-blue-500/50">Subscribe</button>
<button class="bg-indigo-500 shadow-lg shadow-indigo-500/50">
    Subscribe
</button>
```

### Accent Colors

```c
<input type="checkbox" class="accent-purple-500" checked /> Option 1
<input type="checkbox" class="accent-pink-500" checked /> Option 2
<input type="checkbox" class="accent-red-300" checked /> Option 3
```

### Arbitrary Colors

```c
<div class="bg-[#427fab] h-10">Hello</div>
<div class="text-[#427fab] h-10">Hello</div>
<div class="border border-[#427fab] h-10">Hello</div>
```
