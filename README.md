# sail-skeleton

A starter kit for html/css people to get into urbit ux/ui building

## Init

given you have the [urbit binary]() installed into a directory `~/urbit/` and have created a fake ship called `zod`.

(todo maybe: section "i don't know what that means with starting from scratch?)

```
       ~ $ cd zod
   ~/zod $ git clone https://github.com/afknapping/sail-skeleton.git

         # or, if you have ssh set up:
         # git clone git@github.com:afknapping/sail-skeleton.git

   ~/zod $ cd ..
       ~ $ ./urbit zod
~zod:dojo> |merge %sail-skeleton our %webterm
~zod:dojo> |exit
         $ rm -rf zod/sail-skeleton
```

## Work

```
         $ ./urbit zod
~zod:dojo> |mount %sail-skeleton
```

- Ppen <http://localhost:80/app/sail-skeleton/> in browser
- Open `~/urbit/zod/` in a Finder window (or any other file explorer)
- There should be a folder `sail-skeleton/` and a file `sail-skeleton/app/index.hoon` – **edit away and take a look at [the Sail guide](https://developers.urbit.org/guides/additional/sail)**
  - **⚠️ `README.md` and `app/mine.hoon` are missing⚠️**
- `|commit` changes
- reload browser

### Gossary

- [Commit](https://developers.urbit.org/reference/glossary/commit)
- [Desk](https://developers.urbit.org/reference/glossary/desk)

### Further Reading

- [Introduction to Hoon](https://developers.urbit.org/guides/core/hoon-school/A-intro)

---

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

