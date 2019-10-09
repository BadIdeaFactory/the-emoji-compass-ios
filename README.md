# The Emoji Compass (iOS)

This application is built using the [BIFFUD iOS Virus](https://github.com/BadIdeaFactory/biffud-ios-virus).  It contains the contents of [The Emoji Compass](https://github.com/BadIdeaFactory/the-emoji-compass)

## Setting up

After cloning this repository:

> $ > git submodule update --init --recursive

## Building the static site

This application hosts a local / static version of The Emoji Compass.  In order to build it you will need to follow these instructions to clone that static version to the right location:

> $ > cd the-emoji-compass

Follow [the build instructions](https://github.com/BadIdeaFactory/the-emoji-compass#build-instructions)

After build completes go back to the project root and copy the compiled compass files:

> $ > cp the-emoji-compass/build/* iOSVirus/Website