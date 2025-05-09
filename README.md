# clOS
## Linux for the layperson.

Forked from blendOS, immutable by design, engineered to be dumbass-proof.

### What is clOS? 

clOS is (a temporary name for) an Arch Linux-based OS that's meant to make Linux dead simple for the masses. 

There are a few simple goals defining this project:

- It should be dead-simple to install
- It should require the bare-minimum amount of config and tweaking, meaning that it is a very opinionated and batteries-included OS
- It should feel familiar to use when coming from other big name OSes (I'm taking a LOT of inspiration here from Apple's macOS)
- It should be robust and resillient, gracefully handling errors and shipping with a comprehensive snapshot/recovery system a la Timeshift and macOS Recovery
- Your grandparents should feel comfortable using it

### So like, what is this repo?

Because all of the components of clOS are in separate repositories, I've united them here in a monorepo of sorts simply for convenience. Someday I might also run CI/build scripts from here too.

### Package guide
#### archiso-container

These are simply the build files for an archiso docker container.

#### blend-inst

This is the OS installer framework/backend from [blendOS](https://blendos.co/). This part does the heavy lifting while our pretty installer gui keeps you wistfully distracted.

#### image-builder

todo...

#### jade-gui

todo...
