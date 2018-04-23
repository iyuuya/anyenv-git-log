# anyenv-git-log
[anyenv](https://github.com/riywo/anyenv) plugin that provides `anyenv git-log` command to display git log

## Instlattion


Simply clone the repository into the plugins directory:

```shell
mkdir -p $(anyenv root)/plugins
git clone https://github.com/iyuuya/anyenv-git-log.git $(anyenv root)/plugins/anyenv-git-log
```

## Usage
```shell
## **env
anyenv git-log rbenv

## **env/plugins
anyenv git-log rbenv ruby-build
anyenv git-log rbenv/ruby-build
anyenv git-log rbenv/plugins/ruby-build
```

## License
(The MIT License)
