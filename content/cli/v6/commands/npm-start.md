---
title: npm-start
section: 1
description: Start a package
github_repo: npm/cli
github_branch: v6-docs
github_path: docs/content/commands/npm-start.md
---

### Synopsis

```bash
npm start [-- <args>]
```

### Description

This runs an arbitrary command specified in the package's `"start"` property of
its `"scripts"` object. If no `"start"` property is specified on the
`"scripts"` object, it will run `node server.js`.

As of [`npm@2.0.0`](https://blog.npmjs.org/post/98131109725/npm-2-0-0), you can
use custom arguments when executing scripts. Refer to [`npm run-script`](/cli/v6/commands/npm-run-script) for more details.

### See Also

* [npm run-script](/cli/v6/commands/npm-run-script)
* [npm scripts](/cli/v6/using-npm/scripts)
* [npm test](/cli/v6/commands/npm-test)
* [npm restart](/cli/v6/commands/npm-restart)
* [npm stop](/cli/v6/commands/npm-stop)
