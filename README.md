### get-stream
---
https://github.com/sindresorhus/get-stream

```
npm fs = require(fs);
const getStream = require('get-stream');
(async () => {
  const stream = fs.createReadStream('unicorn.txt');
  console.log(await getStream(stream));
})();

(async() => {
  try {
    await getStream(streamThatErrorAtTheEnd('unicorn'));
  } catch(error){
    console.log(error.bufferedData);
  }
})()
```

```
```

```
```


