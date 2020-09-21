---
title: npm-shrinkwrap
section: 1
description: Lock down dependency versions for publication
---

### Synopsis

```bash
npm shrinkwrap
```

### Description

This command repurposes `package-lock.json` into a publishable
`npm-shrinkwrap.json` or simply creates a new one. The file created and updated
by this command will then take precedence over any other existing or future
`package-lock.json` files. For a detailed explanation of the design and purpose
of package locks in npm, see [package-locks](/configuring-npm/package-locks).

### See Also

* [npm install](/cli-commands/install)
* [npm run-script](/cli-commands/run-script)
* [npm scripts](/using-npm/scripts)
* [package.js](/configuring-npm/package-json)
* [package-locks](/configuring-npm/package-locks)
* [package-lock.json](/configuring-npm/package-lock-json)
* [shrinkwrap.json](/configuring-npm/shrinkwrap-json)
* [npm ls](/cli-commands/ls)