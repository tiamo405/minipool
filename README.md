# Minipool.io
# Bản test github
Clone from https://minipool.io/
Using chrome extension [Resources Saver](https://github.com/up209d/ResourcesSaverExt)

[Demo](https://tiamo405.github.io/minipool/)

For education only

## Hack

```javascript
  let key = 'minibillar-data-key-1';
  let data = JSON.parse(localStorage.getItem(key));
  for(let c of data.statistics.rewards.cards) {
  	c.cardPoints = c.cardName.startsWith('table') ? 200:100;
  }
  localStorage.setItem(key, JSON.stringify(data));
```
