# javascript series


## javascript-design-patterns

> 18 Apr 2012

https://app.pluralsight.com/library/courses/javascript-design-patterns/table-of-contents

### bug ???

```js
    
function Book () {
    var name = '';
    Object.defineProperty(this, 'name', {
        get: function () {
            return name;
        },
        set: function (val) {
            console.log(val);
            name = val;
        }
    });
}

let b = new Book();
b.name = `xgqfrms`;


```

![image](https://user-images.githubusercontent.com/18028768/32324362-18e98e24-c006-11e7-8b38-e19a8d03e679.png)

