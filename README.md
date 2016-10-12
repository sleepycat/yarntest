## Yarn test

This is a repo that demonstrates a problem with running mocha via yarn.

```javascript
> git clone https://github.com/sleepycat/yarntest.git && cd yarntest
> yarn
> yarn test
yarn test v0.15.1
$ "mocha --compilers js:babel-core/register"
sh: mocha --compilers js:babel-core/register: No such file or directory
error Command failed with exit code 127.
info Visit http://yarnpkg.com/en/docs/cli/test for documentation about
this command.
mike@longshot ~/projects/yarntest⭐  mocha --compilers js:babel-core/register


  Arithmetic
      ✓ should calculate 1 + 1 correctly


        1 passing (128ms)

```

