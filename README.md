# gh-contributions-notifier

Skip leg day, not commit day ᕦ(ò_óˇ)

## Instructions
> Prerequisites: You will need `npm` (or `yarn`) and Node.js installed
1) `git clone` this repo
2) `cd` into it and run `npm install`
3) Fill in the `.env` file
4) Keep it running in the background with `pm2` or `forever` _(you will need to have these installed)_ or by adding it as a systemd service
```bash
pm2 start index.js
```
_(or alternatively, dockerize it and open a PR :) )_

&nbsp;

---

### Cron syntax
Find an explanation [here](https://www.npmjs.com/package/node-cron)
```bash
0 19 * * *
# ^ run everyday at 19:00
30 14 * * *
# ^ run everyday at 14:30
```