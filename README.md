# form

---

// 通用表单样式

---

## 演示

<link type="text/css" rel="stylesheet" media="screen" href="src/form.css">
<link type="text/css" rel="stylesheet" media="screen" href="src/grid.css">
<link type="text/css" rel="stylesheet" media="screen" href="src/responsive.css">
<link type="text/css" rel="stylesheet" media="screen" href="src/ex.css">

__注意：__示例中以.ex开头的class在实际使用场景中是不必要的，此类class只为可视化文档的展示做辅助作用。

### 默认

````html
<form class="ui-form">
    <fieldset>
        <div class="ui-form-item">
            <label for="input_test">Label name</label>
            <input id="input_test" type="text" name="" placeholder="Placeholder">
            <select>
                <option value="">Please Select One</option>
                <option value="">A</option>
                <option value="">B</option>
                <option value="">C</option>
            </select>
            <label>
                <input type="checkbox" name="" value=""> Check me out
            </label>
            <label>
                <input type="radio" name="" value=""> Check me out
            </label>
        </div>
        <div class="ui-form-item">
            <input id="checkbox_test" type="checkbox" name="" value="">
            <label for="checkbox_test">
                 Check me out
            </label>
            <input id="radio_test" type="radio" name="" value=""> 
            <label for="radio_test">
                Check me out
            </label>
            <textarea name=""></textarea>
        </div>
    </fieldset>
</form>
````

### 示例一

````html
<form class="ui-form">
    <fieldset>
        <div class="ui-form-item ui-grid-row-fluid">
            <div class="ui-grid-span2">
                <label class="ui-form-item-label-right">Label name</label>
            </div>
            <div class="ui-grid-span8">
                <input class="ui-form-item-control" type="text" name="" value="">
            </div>
        </div>
        <div class="ui-form-item">
            <label class="ui-form-item-label">Label name</label>
            <input class="ui-form-item-control" type="text" name="" value="">
        </div>
    </fieldset>
</form>
````
