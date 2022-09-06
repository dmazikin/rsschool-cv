# Dmitry Mazikin

---

## Junior Frontend/Wordpress Developer

---

### Contacts info:

**Phone-1:** _8 (953) 707 86 83;_

**Phone-2:** _8 (910) 659 65 19;_

**Email:** *mazikindima@mail.ru;*

**Telegram:** _@maz_web;_

[My website](https://fl-dm.ru/ "portfolio");

---

## About me

I can well compose a site of any size, and it will be displayed correctly in all current versions of browsers. I can plan and document my work, as well as estimate deadlines.

I understand the importance of maintaining code style. I understand why there are grid systems and css frameworks. I can take all the necessary information from layouts from the designer.

I can interact with a small team, create branches and pull requests. I use scss in my work, because it is easier to read, minimizing the appearance of errors. Also, I can use sass.

---

## Skills

1. HTML/CSS
2. Sass/Scss
3. WordPress
4. Native Js
5. Jquery/plugins
6. Bootstrap
7. Git, GitHub
8. Gulp/npm
9. VS Code , Linux, Setting hosting and domens, BEM

---

## Code example

Creating a tab switcher on a website:

```
 $("ul.catalog__tabs").on("click", "li:not(.catalog__tab_active)", function() {
        $(this)
            .addClass("catalog__tab_active")
            .siblings()
            .removeClass("catalog__tab_active")
            .closest("div.container")
            .find("div.catalog__content")
            .removeClass("catalog__content_active")
            .eq($(this).index())
            .addClass("catalog__content_active");
    });
```

---
