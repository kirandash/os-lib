# Creating an OS project on Github

## 1 Setup

### 1.1 Accounts

- github
- https://codecov.io/
- https://www.travis-ci.com/

### 1.2 CoC and License, README file

- License: https://opensource.org/license/mit/ (mandatory)
- CODE_OF_CONDUCT.md https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md

### 1.3 npm configuration and npm init

- Docs: https://docs.npmjs.com/cli/v8/commands/npm-config
- to logout from existing npm session: `npm logout`
- `cat ~/.npmrc` to see content of npmrc
- `npm config set`
- setup npmrc:

```
npm config set init-author-name "Kiran Dash"
npm config set init-author-email "kiran@bgwebagency.in"
npm config set init-author-url "https://bgwebagency.in"
npm config set init-license "MIT"
npm config set save-exact "true"
npm config set username "kirandash"
npm config set email "some@gmail.com"
```

- `npm init`
- set entry point to src/index.js
