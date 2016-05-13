# O-Tools for LiveScript
> build and watch scripts for LiveScript developers

This NPM module provides the `build` and `watch` scripts for compiling LiveScript code bases.


## Usage

* add `o-tools-livescript` to your codebase:

  ```
  $ npm install --save-dev o-tools-livescript
  ```

* add `./bin` to you `PATH` environment variable

* remove the files `bin/build` and `bin/watch` from your code base
  if you plan on using the versions provided by this library

Now you can run `build` to compile source code in `src` to `dist`,
and `watch` to do this continuously on every file change.



## Release a new version

```
$ publish <patch|minor|major>
```

The new version is pushed by the CI server, which can take a few minutes.