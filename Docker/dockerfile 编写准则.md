# dockerfile 编写准则

------

# Dockerfile 编写 准则

> 主要介绍使用Dockerfile编写镜像的时候,需要注意的事项。

- **精简镜像用途**

尽量让每个镜像的用途比较集中，简单。避免构建多功能、复杂镜像。

- **选择合适的基础镜像**
- **提供足够清晰的命令注释和维护者信息** 方面维护
- 正确使用版本号
- 尽量减少镜像层数

使用的RUN 尽量合并。

- 及时删除临时文件及缓存文件。
- 提高生成效率
- 调整合理的指令顺序
- 减少外部源干扰