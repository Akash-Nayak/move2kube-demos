## Installation

### Move2Kube Command Line Tool:

**Github release**

The binary can be downloaded from the [GitHub releases page](https://github.com/konveyor/move2kube/releases) of Move2Kube.

**Linux / macOS / Windows WSL:**
```
$ curl -L https://raw.githubusercontent.com/konveyor/move2kube/master/scripts/install.sh | bash -
```

**Go**

Installing using `go get` pulls from the master branch of [Move2Kube](https://github.com/konveyor/move2kube) with the latest development changes.
```
$ go get –u github.com/konveyor/move2kube
```

### Move2Kube Web Interface:
```
$ git clone https://github.com/konveyor/move2kube-ui
```
```
$ docker-compose up
```
Move2Kube UI will now be accessible in http://localhost:8080.
