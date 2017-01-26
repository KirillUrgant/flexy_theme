#Тема для элементов форм для flexy framework

![screen](https://s29.postimg.org/q77iynflj/screen.png)

##Разметка элементов
```html
<form action="">
    <a class="b-button" href="#">link</a>
    <input class="b-button" type="submit" value="submit">
    <button class="b-button">button</button>
    <hr>
    <div class="b-input">
        <label class="b-input__label" for="name">You name</label>
        <input class="b-input__input" type="text" id="name" name="name" placeholder="name">
    </div>
    <hr>
    <div class="b-select">
        <select class="b-select__select">
            <option value="1" selected="">option 1</option>
            <option value="2">option 2</option>
            <option value="3">option 3</option>
        </select>
    </div>
    <hr>
    <div class="b-checkbox">
        <input class="b-checkbox__checkbox" type="checkbox" id="check1" name="check1">
        <label class="b-checkbox__label" for="check1">Checkbox 1</label>
    </div>
    <div class="b-checkbox">
        <input class="b-checkbox__checkbox" type="checkbox" id="check2" name="check2">
        <label class="b-checkbox__label" for="check2">Checkbox 2</label>
    </div>
    <hr>
    <div class="b-radio">
        <input class="b-radio__radio" type="radio" id="r1" name="r1">
        <label class="b-radio__label" for="r1">Radio 1</label>
    </div>
    <div class="b-radio">
        <input class="b-radio__radio" type="radio" id="r2" name="r1">
        <label class="b-radio__label" for="r2">Radio 2</label>
    </div>
</form>
```
