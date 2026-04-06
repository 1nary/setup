# Mac Setup

新しいMacをセットアップする時用のコマンド一覧。

## Homebrew

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## 基本ツール

```sh
brew install git
brew install gh
brew install vim
brew install tmux
brew install fish
brew install htop
brew install tree
brew install exa
```

## 言語・ランタイム

```sh
brew install anyenv
brew install python@3.12
brew install uv
brew install yarn
```

## モバイル開発（Flutter/iOS）

```sh
brew install cocoapods
brew install fastlane
brew install lefthook
brew install scrcpy
brew install --cask xcodes-app
brew install --cask android-platform-tools
```

## インフラ・バックエンド

```sh
brew install docker
brew install --cask docker-desktop
brew install supabase/tap/supabase
brew install stripe/stripe-cli/stripe
brew install --cask gcloud-cli
brew install mysql
brew install postgresql@14
```

## アプリ

```sh
brew install --cask ghostty
brew install --cask obsidian
brew install --cask deepl
brew install --cask font-hack-nerd-font
```

## Claude

```sh
brew install claude-squad
```

## iTerm2

プロファイルの復元：iTerm2 → Settings → Profiles → Other Actions... → Import JSON Profiles... → `iterm2-profile.json` を選択
