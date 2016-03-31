# githooks
Want to make sure everyone in your project is using a githook?

## install
- Copy the `bin/git/hooks-wrapper` and `bin/git/init-hooks` scripts to your project
- If you change the location of these scripts in your project you will need to edit the paths in the scripts slightly

## usage
- Create a folder `bin/git/hooks/` and add/commit your hooks there (eg. pre-commit-my-custom-hook1)
- Add `bin/git/init-hooks` to your init/build/make/configure process so that it gets run as part of the project init process

## license
MIT
