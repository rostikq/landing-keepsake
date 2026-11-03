# landing-keepsake

Адаптивний односторінковий лендінг дизайн-агенції Keepsake (Lab 7, Завдання 4).

**Demo:** https://<your-username>.github.io/landing-keepsake/

## Технології та рішення
- Семантичний HTML5 (`header`, `nav`, `main`, `section`, `article`, `footer`, `form`), один `h1`.
- CSS-змінні в `:root` (кольори, шрифти, відступи, розміри по брейкпоінтах).
- Mobile first: базові стилі для 375, `@media (min-width: 768px)` і `1280px`; max-width контейнера 1100px.
- Flexbox для розкладки; CSS Grid лише для сітки портфоліо (`aspect-ratio` для карток).
- Без JS: бургер-меню через `input:checkbox:checked ~ nav`, фільтр портфоліо через `input:radio:checked ~`, success форми через `:target`, error через `:user-invalid`.
- Ховер/focus карток (`:hover`, `:focus-within`), `:focus-visible` для кнопок.
- Шрифти Oswald, Open Sans, Dancing Script з Google Fonts (`display=swap`); іконки — inline SVG.
