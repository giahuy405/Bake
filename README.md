# Bake

Grid-template-area
CSS
```javascript
 .grid-container {
      display: grid;
      grid-template-areas:
        "grid-container__item1 grid-container__item1 grid-container__item1"
        "grid-container__item2 grid-container__item3 grid-container__item4";
      grid-template-rows: 200px 1fr 200px;
      grid-template-columns: 18% 1fr 13%;
      height: 100vh;
      width: 100vw;
    }
    .grid-container__item1 {
      background-color: red;
      grid-area: grid-container__item1;
    }

    .grid-container__item2 {
      background-color: blue;

      grid-area: grid-container__item2;
    }
    .grid-container__item3 {
      background-color: yellow;

      grid-area: grid-container__item3;
    }
```
HTML
```javascript
 <div class="grid-container">
      <div class="grid-container__item1">1</div>
      <div class="grid-container__item2">2</div>
      <div class="grid-container__item3">3</div>
      <div class="grid-container__item4">4</div>
      <div class="grid-container__item5">5</div>
      <div class="grid-container__item6">6</div>
    </div>
```
