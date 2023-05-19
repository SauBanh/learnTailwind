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
-   [Grid](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Grid/Grid.md)
-   [Transform Transition](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Transform_Transition/Transform_Transition.md)
-   [Animation](https://github.com/SauBanh/learnTailwind/blob/main/All_Concept/Animation/Animation.md)
-   <a style="color: red; text-decoration: underline">Customization</a>

---

## Customization

### Config

```c
tailwind.config = {
    theme: {
        screens: {
            sm: '550px',
            md: '800px',
            lg: '1200px',
            xl: '1440px',
        },
        fontFamily: {
            sans: ['Graphik', 'sans-serif'],
            serif: ['Merriweather', 'serif'],
        },
        extend: {
            colors: {
                primary: '#FF5733',
                secondary: '#FFFC33',
            },
            spacing: {
                5: '3.5rem',
            },
        },
    },
}
```

### Tailwind is mobile-first

```c
<body
    class="bg-black sm:bg-green-800 md:bg-primary lg:bg-yellow-800 xl:bg-purple-800 2xl:bg-orange-800"
  >
    <div class="bg-black p-5">
    <h1 class="text-white text-xl md:text-3xl md:text-secondary xl:text-5xl">
    Tailwind is awesome
    </h1>
    </div>

<script>
    function showBrowserWidth() {
    const width =
        window.innerWidth ||
        document.documentElement.clientWidth ||
        document.body.clientWidth

    document.querySelector('h1').innerHTML = `Width: ${width}`
    }
    window.onload = showBrowserWidth
    window.onresize = showBrowserWidth
</script>
</body>
```

### Breakpoint Classes

| Tailwind | Breakpoint | Css                                |
| -------- | ---------- | ---------------------------------- |
| sm       | 640px      | @media (min-width: 640px) { ... }  |
| md       | 768px      | @media (min-width: 768px) { ... }  |
| lg       | 1024px     | @media (min-width: 1024px) { ... } |
| xl       | 1280px     | @media (min-width: 1280px) { ... } |
| 2xl      | 1536px     | @media (min-width: 1536px) { ... } |
