## Breakpoints

### Tailwind is mobile-first

```c
<body
class="bg-black sm:bg-green-800 md:bg-blue-800 lg:bg-yellow-800 xl:bg-purple-800 2xl:bg-orange-800"
>
<h1 class="text-white text-xl md:text-3xl xl:text-5xl">
    Tailwind is awesome
</h1>

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
