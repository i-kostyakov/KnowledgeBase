# Группировка и Порядок описания свойств в классах

    .declaration-order {
      /* Positioning */
      position: absolute;
      top: 0;
      right: 0;
      bottom: 0;
      left: 0;
      z-index: 1;
      margin: 16px;
      margin-top: 16px;
      margin-right: 16px;
      margin-bottom: 16px;
      margin-left: 16px;
      float: right;
      clear: both;
      place-self: center;
      align-self: center;
      justify-self: center;
      grid-area: none;
      grid-column: none;
      grid-column-start: none;
      grid-column-end: none;
      grid-row: none;
      grid-row-start: none;
      grid-row-end: none;
      order: 2;

      /* Display Model */
      display: flex;
      flex-direction: column;
      flex-flow: initial;
      flex-wrap: initial;
      place-items: center;
      justify-content: center;
      align-items: center;
      place-content: center;
      justify-content: center;
      align-content: center;
      overflow: hidden;
      overflow-x: hidden;
      overflow-y: hidden;
      box-sizing: border-box;
      grid: initial;
      grid-auto-flow: initial;
      grid-auto-columns: initial;
      grid-auto-rows: initial;
      grid-gap: initial;
      grid-column-gap: initial;
      grid-row-gap: initial;
      grid-template: initial;
      grid-template-areas: initial;
      grid-template-columns: initial;
      grid-template-rows: initial;
      gap: initial;

      /* Box Model */
      flex: 1 1 auto;
      flex-grow: 1;
      flex-shrink: 1;
      flex-basis: auto;
      width: 100px;
      max-width: 100px;
      min-width: 100px;
      height: 100px;
      max-height: 100px;
      min-height: 100px;
      padding: 8px;
      padding-top: 8px;
      padding-right: 8px;
      padding-bottom: 8px;
      padding-left: 8px;
      border: 10px solid hsla(0, 0%, 50%, 1);
      border-radius: 4px;
      border-width: initial;
      border-top: initial;
      border-top-width: initial;
      border-right: initial;
      border-right-width: initial;
      border-bottom: initial;
      border-bottom-width: initial;
      border-left: initial;
      border-left-width: initial;
      border-top-left-radius: initial;
      border-top-right-radius: initial;
      border-bottom-right-radius: initial;
      border-bottom-left-radius: initial;
      border-collapse: initial;
      border-spacing: initial;
      border-style: initial;
      border-color: initial;
      border-top-style: initial;
      border-top-color: initial;
      border-right-style: initial;
      border-right-color: initial;
      border-bottom-style: initial;
      border-bottom-color: initial;
      border-left-style: initial;
      border-left-color: initial;
      border-image: initial;
      border-image-source: initial;
      border-image-slice: initial;
      border-image-width: initial;
      border-image-outset: initial;
      border-image-repeat: initial;

      /* Typography */
      font: normal 13px/1.5 "Arial", sans-serif;
      font-style: normal;
      font-size: 13px;
      line-height: 1.5;
      font-family: "Arial", sans-serif;
      text-align: center;

      /* Visual */
      color: hsla(0, 0%, 0%, 1);
      background: url('/some-url.jpg') center;
      background-color: hsla(0, 100%, 100%, 1);
      outline: 1px solid hsla(0, 50%, 100%, .6);
      opacity: 1;

      /* Animation */
      transition: color 1s;
      animation: ...;

      /* Misc */
      content: '';
      will-change: auto;
    }

**Значение для всех цветовых свойств должно задаваться в формате hsla**
