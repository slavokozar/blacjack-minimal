# BlackJack PHP deck

This project is simple implementation of deck of 52 french cards. 

There are 4 color of cards: **heart, spade, club, diamond,**
13 values:
**2, 3, 4, 5, 6, 7, 8, 9, 10, J, Q, K, A**

Each card is interpreted by class **Card** stored in card.php.
 
Class **Card** has attributes ``suit, value`` and method ``toString`` which returns element implementing single card in deck. 

```html
<div class="card" data-suit="spade" data-value="A">
</div>
```

The ``data`` attribute of every tag can be easily read by jQuery. 
 In order to read attribute ``data-my_value`` there is ``$(selector).data('my_value')`` function.
 
 In order to read value and suite of our card:

```javascript
var value = $('.card').data('value');
var suite = $('.card').data('suite');
```

To read all values and suites sue **.each()** function:

```javascript
$('.card').each(function(){
   var value = $('.card').data('value');
   var suite = $('.card').data('suite'); 
});
```


##How to play BlackJack?
https://www.youtube.com/watch?v=idB-7FUaC-g&t=248s
