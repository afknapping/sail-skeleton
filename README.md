# sail-skeleton

A starter kit for html/css people to get into urbit ux/ui building

## Init

given you have the [urbit binary]() installed and have created a fake ship called `zod`

```
~ $ cd zod
~/zod $ git clone git@github.com:afknapping/sail-skeleton.git 
~/zod $ ..
$ ./urbit zod
~zod:dojo> |merge %sail-skeleton our %webterm
~zod:dojo> |exit
$ rm zod/sail-skeleton
```

## Work

```
$ ./urbit zod
~zod:dojo> |mount %sail-skeleton
```
(tba: edit, commit, refresh browser)


## Minimum version

- [ ] hello world renders in the browser after cloning the repo and copypasting a few commands into terminal and dojo

### other ideas

- [ ] [autocommit](https://operators.urbit.org/manual/os/dojo-tools#autocommit) changes
- [ ] use [arthyn/gin-tonic](https://github.com/arthyn/gin-tonic): ship sync and sail hot reloading for urbit development
- [ ] example mock data in various types
- [ ] example ui components as single-file components
- [ ] scribble wireframe styles from [diskurs-prototype](https://github.com/afknapping/diskurs-prototype/blob/main/src/_sac1-tools.sass#L33-L56) / [Houdini Rough boxes](https://css-houdini.rocks/rough-boxes/)
- [ ] replit project
- [ ] replit template


## Thx

~tinnus-napbus, ~sogrum-savluc

