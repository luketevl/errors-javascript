# errors-javascript
List erros in javascript and who solutions

# Error

## TypeError: Cannot set property 'key' of undefined
- With error
```javascript
let variable = [];
variable.position['key'] = 9; // TypeError: Cannot set property 'key' of undefined
```
- **Solution**
```javascript
let variable = {
  position: []
};
variable.position['key'] = 9; 
```
