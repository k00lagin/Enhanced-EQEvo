# Стили для более заметных/понятных кнопок назад/далее

1. Установить расширение браузера [Stylus](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne/)
2. Создать стиль для eq-MFC-terminalbb.mfc-74.ru
3. Скопировать код в поле редактирования скрипта в Stylus
```css
.left-left-content-button,
.right-right-content-button {
    width: unset;
    padding: 0 16px;
}
.ion-arrow-left-c::after {
    font: 400 36px/1.42 'Roboto', 'Helvetica Neue', Helvetica, Arial;
    content: "Назад";
    margin-left: 12px;
    margin-top: -8px;
}
.ion-arrow-right-c::before {
    font: 400 36px/1.42 'Roboto', 'Helvetica Neue', Helvetica, Arial;
    content: "Далее";
    margin-right: 12px;
    margin-top: -8px;
}
.ion-arrow-right-c::after {
    font-family: "Ionicons";
    content: "\f10b";
    font-style: normal;
}
.ion-arrow-left-c::before {
    font-family: "Ionicons";
    content: "\f108";
}
.ion-arrow-left-c,
.ion-arrow-right-c {
    display: flex;
    flex-flow: row nowrap;
    align-items: center;
}
```
4. Сохранить скрипт
