- 1.0.4 (2025年12月03日)
    - 路径支持 {compress} 占位符替换为 .min 压缩字段在生产环境下，路径中的 {compress} 占位符将被替换为 ".min" 字符串，开发环境下则替换为空字符串。此功能用于自动处理

- 1.0.3 (2025年12月03日)
    - module 定义时，支持 version 直接定义版本
    - 优化遍历寻找版本时，第一匹配时，就跳过搜索
    - 在 dev 模式下，加入 log 日志

- 1.0.2 2025年12月03日
    -　修改支持 monorepo 架构
    - Vite 7.x 支持

- 1.0.1 (Apr 26, 2024)
    - Deprecate `autoComplete`, pass the package name directly in options.modules instead.

- 1.0.0 (Apr 25, 2024)
    - Update all dependencies
    - Vite 5.x support
    - Support development mode
    - Supports custom generation of script and css link tags
    - Add Vite2, Vite3, Vite4, Vite5 examples
    - `autoComplete` deletes some packages
