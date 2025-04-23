# Menu Mobile

## Observations
- Open Menu function
- Close Menu function
- ESC Key close function
- Not scroll (_body and html_)

## Structure
```javascript
// VARS
var $MenuOpen = $('.js-menu-open');
var $MenuClose = $('.js-menu-close');

// Click Open [ + ]
$MenuOpen.click(function(event){
    alert('Click Open');
});

// Click Close [ X ]
$MenuClose.click(function(event){
    alert('Click close');
});
```

## Functions
```javascript
function Open(){
    //
}

function Close(){
    //
}
```

## Requirements
- https://gsap.com/docs/v3/
- https://releases.jquery.com/
