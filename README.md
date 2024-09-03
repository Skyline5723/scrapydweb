修改增强：
   - 使用[Waitress](https://github.com/Pylons/waitress)增强ScrapydWeb的部署性能，支持Windows、Linux和MacOS
   - 匹配不同的日志格式：INFO | 2024-01-01 00:00:00 | module: msg
   - 删除任务列表某些列，增加错误和警告数显示（仅限Database模式）

先卸载（如已安装）
```bash
pip uninstall scrapydweb
```
使用git安装:
```bash
pip install --upgrade git+https://github.com/Skyline5723/scrapydweb
```
