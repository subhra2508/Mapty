# map app

### project planning

### Geolocation api
```js
navigator.geolocation.getCurrentPosition(function(){
    console.log('this will be the success function')
},function(){
   console.log('this will be the error function');
});
```
- In an regular function call the this keyword is set to undefined
- 