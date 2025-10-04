## Caddy Builder

Automatically builds the [Caddy](https://github.com/caddyserver/caddy) Docker image daily, adding several modules, including the [cloudflare](github.com/caddy-dns/cloudflare) module. See the [Dockerfile](https://github.com/SIXiaolong1117/caddy-builder/blob/main/Dockerfile) for details.

Get the built image:

```bash
docker pull ghcr.io/sixiaolong1117/my-caddy:latest
```

You can also fork this project; the built image will be automatically pushed to `ghcr.io/${{ github.repository_owner }}/my-caddy:latest`.

> [!CAUTION]
> `github.repository_owner` must be lowercase, so if you use an uppercase username like me, you will have to manually modify [`build,yml`](https://github.com/SIXiaolong1117/caddy-builder/blob/0d8bb1e3e8d3fb0ed2c994188283e8f88c7d743c/.github/workflows/build.yml#L40).

## Caddy Builder

每日自动构建 [Caddy](https://github.com/caddyserver/caddy) Docker 镜像，添加包括 [cloudflare](github.com/caddy-dns/cloudflare) 模块在内的几个模块，详见 [Dockerfile](https://github.com/SIXiaolong1117/caddy-builder/blob/main/Dockerfile)。

获取构建好的镜像：

```bash
docker pull ghcr.io/sixiaolong1117/my-caddy:latest
```

你也可以 Fork 本项目，镜像构建后会自动推送至 `ghcr.io/${{ github.repository_owner }}/my-caddy:latest`。

> [!CAUTION]
> `github.repository_owner` 必须为小写，所以如果你和我一样使用大写用户名，那你就必须手动修改 [`build,yml`](https://github.com/SIXiaolong1117/caddy-builder/blob/0d8bb1e3e8d3fb0ed2c994188283e8f88c7d743c/.github/workflows/build.yml#L40)。