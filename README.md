# rssi2percent

Converts RSSI in dBm to quality percentage.


### `rssi2percent.rssiQuality(dBm)`

Converts RSSI dBm to WiFi signal strength percentage (quality).

### Parameters

| parameter | type    | description |
| --------- | ------- | ----------- |
| `dBm`     | Integer | RSSI dBm    |


### Example

```js
var quality = rssi2percent.rssiQuality(-75);

//=quality
```


**Returns** `Number`, WiFi signal quality

## Installation

Requires [nodejs](http://nodejs.org/).

```sh
$ npm i --save https://github.com/GrowNodes/rssi2percent.git
```

## Tests

```sh
$ npm test
```


