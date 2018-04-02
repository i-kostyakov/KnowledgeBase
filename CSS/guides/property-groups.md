# Группировка и Порядок описания свойств в классах

    .declaration-order {
      /* Positioning */
      position: absolute;
      top: 0;
      right: 0;
      bottom: 0;
      left: 0;
      margin: 16px;
      z-index: 1;
      float: right;

      /* Display Model */
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      overflow: hidden;
      box-sizing: border-box;

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
      border: 10px solid hsla(0, 0%, 50%, 1);
      border-radius: 4px;

      /* Text */
      font: normal 13px/1.5 "Arial", sans-serif;
      font-style: normal;
      font-size: 13px;
      line-height: 1.5;
      font-family: "Arial", sans-serif;
      text-align: center;

      /* Оформление */
      color: hsla(0, 0%, 0%, 1);
      background: url('/some-url.jpg') center;
      background-color: hsla(0, 100%, 100%, 1);
      outline: 1px solid hsla(0, 50%, 100%, .6);
      opacity: 1;

      /* Анимация */
      transition: color 1s;
      animation: ...;

      /* Other */
      content: '';
      will-change: auto;
    }

**Значение для всех цветовых свойств должно задаваться в формате hsla**
