# Micro-PubSub
Micro-PubSub is a modified version of David Walsh's [pubsub](http://davidwalsh.name/pubsub-javascript).

## Usage

``` javascript
var pubsub = require('micro-pubsub');
pubsub.subscribe('some-key', function (info) {
    console.log(info);
});

pubsub.publish('some-key, {price: 23});
```

## License

[MIT](http://opensource.org/licenses/MIT)