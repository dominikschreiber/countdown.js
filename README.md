countdown.js
============

`countdown.js` is a super-simple command line egg-timer.

Install it with

```bash
npm install -g countdown.js
```

Use it with

```bash
countdown.js 15m
```

**Available time strings to count down:** `args[0]` is parsed by [timestring](https://www.npmjs.org/package/timestring), so anything like `1h 15m`, `2 days 4 hours 3 minutes`, `22s` will work (see timestring package for detailed information).

License
-------
Published under a MIT license. See [LICENSE](./LICENSE).
