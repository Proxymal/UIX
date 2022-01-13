## About

*UIX.css* is a modern responsive CSS framework for your websites that allows to create minimalistic-looking designs.

To use *UIX.css* you don't have to know CSS, just type classes and attributes in your HTML to apply styles.

## Theming

The main concept of the framework is theming. The page and every component individually can be themed.

Page or component can be themed via attributes:
- `dark`
- `light`
- `accent`

Example:
```html
<html>
    <!-- Child elements of page will have light theming-->
    <body light>
        <nav></nav>
        <main></main>
        <!-- Element will have dark theming instead of parent theming-->
        <footer dark></footer>
    </body>
</html>
```

## Classes

### **Text Font, Text Font Weight**
| class        | Description          |
|--------------|----------------------|
| font-title   | Font for titles      |
| font-text    | Font for texts       |
| font-sans    | Sans font            |
| font-serif   | Sans Serif font      |

| class              | Description             |
|--------------------|-------------------------|
| font-weight-normal | Normal text weight      |
| font-weight-bold   | Bold text weight        |

### **Text Size**
Text size classes allows to make responsive text sizes. Fixed sizes are recommended to use.
| class        | Size (px)            |
|--------------|----------------------|
| text-fixed-1 | 12px - 14px          |
| text-fixed-2 | 14px - 16px          |
| text-fixed-3 | 16px - 18px          |
| text-fixed-4 | 18px - 24px          |
| text-fixed-5 | 20px - 24px - 30px   |
| text-fixed-6 | 24px - 30px - 48px   |
| text-fixed-7 | 32px - 48px - 64px   |
| text-fixed-8 | 56px - 72px - 100px  |
| text-fixed-9 | 72px - 100px - 164px |

*ru* (Responsive unit): *viewportBasis* * 100vw
| class        | Size     |
|--------------|----------|
| text-fluid-1 | 14 / ru  |
| text-fluid-2 | 16 / ru  |
| text-fluid-3 | 18 / ru  |
| text-fluid-4 | 24 / ru  |
| text-fluid-5 | 30 / ru  |
| text-fluid-6 | 48 / ru  |
| text-fluid-7 | 64 / ru  |
| text-fluid-8 | 80 / ru  |
| text-fluid-9 | 100 / ru |

### **Text Color**
First colors are the brightest ones, the last colors are darkest.
| class    |
|----------|
| color-1  |
| color-2  |
| color-3  |
| color-4  |
| color-5  |
| color-6  |
| color-7  |
| color-8  |
| color-9  |

### **Background Color**
First colors are the brightest ones, the last colors are darkest.
| class    |
|----------|
| bg-1     |
| bg-2     |
| bg-3     |
| bg-4     |
| bg-5     |
| bg-6     |
| bg-7     |
| bg-8     |
| bg-9     |