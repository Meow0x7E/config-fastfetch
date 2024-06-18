# config-nvim

一个简单的 [fastfetch][1] 配置文件，可以让你的 [fastfetch][1] 更加花哨。

预览:
![Preview](doc/preview.png)

# 使用方式

- 手动下载 [config.jsonc](blob/main/config.jsonc)，并将其放到 `~/.config/fastfetch` 目录下。
- 复制并执行以下命令来自动处理这一切
```bash
git clone https://github.com/Meow0x7E/config-fastfetch ~/.config/fastfetch
rm -rf $(ls -A ~/.config/fastfetch | sed -e '/config.jsonc/d' -e 's/^/~\/\.config\/fastfetch\//')
```
[1]: https://github.com/fastfetch-cli/fastfetch
