# javascript series


## javascript-design-patterns

> 18 Apr 2012

https://app.pluralsight.com/library/courses/javascript-design-patterns/table-of-contents


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

let b = new Book;
b.name = `xgqfrms`;


```


