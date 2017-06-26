# Solution to npm Error: Cannot find module 'internal/fs'

Based on the way you have updated your **npm** tool you may see the following error message when trying to install globally a module **Error Cannot find-module 'internal-fs'**

I solved it doing this:

```sh
curl -0 -sL https://npmjs.org/install.sh | sudo sh
```
