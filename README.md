# directions
> Constants for ordinal directions

```javascript
const {
	TOP_LEFT, TOP, TOP_RIGHT,
	LEFT, RIGHT,
	BOTTOM_LEFT, BOTTOM, BOTTOM_RIGHT } = require('directions')

const cardinals = [LEFT, TOP, RIGHT, BOTTOM]

for (var direction of cardinals) {
	var [dx, dy] = direction
	// ...
}
```

## Installation
```sh
npm install --save semibran/directions
```

## License
MIT
