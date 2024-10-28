# How to use?

- **Scss-koden ligger redan i projektet. Enbart boilerplate koden behöver hämtas härifrån!**
- I HTML-filerna finns boilerplate kod att hämta för både sektioner och enskilda komponenter.
- Behöver någon komponent specialstyling inne på en _View_ implementeras detta under _layout/views/{viewName}_. I scss struktur under ex.
  ```
  .cart-view {
  // manage styling linked to to xxx-section
  }
  ```
- INGEN styling ändras därmed direkt i komponenternas filer.
