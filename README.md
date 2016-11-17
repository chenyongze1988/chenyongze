# Emoji Commit Messages

My personal variant of the ever-popular emoji commit message practice.

## Motivation

Emoji help make it more clear what a given commit is trying to accomplish,
make your commit history easier to search though, and encourage you
to keep each of your changes contained to a single type of action.
This makes it easier to reason about the history of your code.

For example, instead of having one massive commit that adds a feature,
refactors an old related feature, fixes a typo, and fixes a bug,
you could split that change into four commits that each accomplish
one specific action. Not only does this make things cleaner and clearer,
but it also helps when using tools like `git bisect` to track down bugs.

## The List

| Emoji | When to use it |
|:-----:|:-------------- |
| 🎉 | initial commit |
| 🎨 | when improving UI |
| 📦 | when refactoring / improving code |
| 🐎 | when improving performance |
| ☁ | when tweaking an API |
| 📝 | when writing docs |
| 🐛 | when fixing a bug |
| 💥 | when fixing a crash |
| 🚱 | when plugging memory leaks |
| 🔥 | when removing code or files |
| ✅ | when adding tests |
| 💚 | when fixing the CI build |
| ⬆ | when upgrading dependencies |
| ⬇ | when downgrading dependencies |
| 👕 | when removing linter warnings |
| ✨ | when adding a new user-facing feature |
| ♿ | when improving accessibility |
| ⚡ | when making a backwards-incompatible change |
| 🐧 | when fixing something specific to Linux |
| 🍎 | when fixing something specific to iOS |
| 🤖 | when fixing something specific to Android |
| 🏁 | when fixing something specific to Windows |
| ❄ | when updating configs |
| 🔒 | when dealing with security |
| 🚧 | when the change is a "work in progress" (do not merge) |
| 📡 | when adding instrumentation / metrics |
| 🔊 | when adding logging |
| 🔇 | when removing logging |
| 🚀 | when doing stuff related to dev tools |
| 💎 | when bumping version for a new release |

## Credits

Developed along with my wonderful co-workers at [Cribspot](https://www.cribspot.com/).

Inspired in part by style guides from [slashsBin](https://github.com/slashsBin/styleguide-git-commit-message#suggested-emojis) and [atom](https://github.com/atom/atom/blob/master/CONTRIBUTING.md#git-commit-messages).
