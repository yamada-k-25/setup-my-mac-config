# setup-my-mac-config

### Install CLT(Command Line Tool)
各種コマンドラインを使うために最初にインストールする必要がある。(git, makeなど)
```
$ xcode-select --install
```

### homebrew
パッケージ管理システム。インストールするパッケージは最小限に抑える。
基本はDockerを使って、パッケージを管理していく。Dockerには含めないようなパッケージだけをhomebrewを使って管理する。
```sh
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
