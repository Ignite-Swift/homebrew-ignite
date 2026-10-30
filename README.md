# homebrew-ignite

Homebrew tap for the [Ignite](https://github.com/Ignite-Swift/Ignite) static site generator.

```shell
brew tap ignite-swift/ignite
brew install ignite-swift
```

Or in one step:

```shell
brew install ignite-swift/ignite/ignite-swift
```

The formula is named `ignite-swift` because Homebrew core already has an unrelated `ignite` formula. The installed command is still `ignite`.

New versions are proposed automatically: the release workflow in the Ignite repository opens a pull request here for each version tag. Adding the `pr-pull` label to that pull request publishes the bottles and merges it.

The formula is based on the one [nyan-lin-tun](https://github.com/nyan-lin-tun) proposed in [Homebrew/homebrew-core#321008](https://github.com/Homebrew/homebrew-core/pull/321008).
