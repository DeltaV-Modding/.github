# Contributing to DeltaV Modding

Thanks for helping. A few rules keep the projects healthy.

## Before you start

- For anything bigger than a small fix, open an issue or ask on [Discord](https://discord.com/invite/5Tjw429zwN) first, so two
  people do not build the same thing.
- One pull request per change. Keep it small enough to review.

## Stormworks projects (DeltaLoader and its mods)

- **Only your own work.** Never paste decompiled game code, game files or code of other mod loaders into a pull request. Numbers you
  found yourself (addresses, offsets, sizes) are fine; say how you found them.
- A change that talks to the game must **fail closed**: when the game build does not match, it does nothing and says why.
- Every new header says in its first lines what is proven and what is not.
- Build and run the tests before you send it (`build_mod.ps1`, `ctest`).

## Minecraft projects

Follow the build and style notes in the project's own README.

## Commits and pull requests

- Write commit messages and code comments in English.
- Describe what changed and how you tested it. Screenshots help for anything visible.
- By sending a pull request you agree that your change is published under the licence of that repository.
