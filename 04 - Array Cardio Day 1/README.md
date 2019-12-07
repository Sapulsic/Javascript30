# JavaScript30 - Day 4

### **Summary**
Exercises dealing with Arrays.

### **Learned**


* Using `console.table()` to show the Array in a Table Layout.
* Using a more efficient version of `"name" + " " + "name"` using the syntax below.

```javascript
 `${name} ${name}`
```

* Shortening an If statement by using a ternary operator.

```javascript
    const ordered = inventors.sort((a, b) => a.year > b.year ? 1 : -1);
```


* Since `.querySelector` returns a NodeList, you have to convert the NodeList into an Array to use `.map`. Using `Array.from()` will convert the .querySelector into an array.

```javascript
    const name = Array.from(category.querySelectorAll('class'));
```