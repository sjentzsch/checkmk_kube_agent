# Checkmk Repository

![Checkmk](https://checkmk.com/application/files/thumbnails/low_res/7015/9834/3137/checkmk_logo_main.png)

## Add the Checkmk Helm repository

```sh
helm repo add checkmk https://sjentzsch.github.io/checkmk_kube_agent

```

## Install checkmk

```sh
helm upgrade -i checkmk checkmk/checkmk
```

For more details on installing Checkmk please see the [chart's README](https://github.com/sjentzsch/checkmk_kube_agent/blob/main/deploy/charts/checkmk/README.md).

## License

[Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0)
