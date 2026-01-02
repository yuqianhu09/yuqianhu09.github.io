# 本地预览指南

## 在Windows上运行Jekyll本地服务器

### 步骤1: 安装Ruby

1. 下载并安装 RubyInstaller for Windows:
   - 访问: https://rubyinstaller.org/downloads/
   - 下载 Ruby+Devkit 版本（推荐 3.1.x 或 3.2.x）
   - 运行安装程序，勾选 "Add Ruby executables to your PATH"

2. 安装完成后，重新打开命令行窗口

3. 验证安装:
   ```cmd
   ruby --version
   ```

### 步骤2: 安装Jekyll依赖

在项目目录下运行:

```cmd
cd C:\Users\yingj\Documents\personal_webpage\yuqianhu09.github.io
bundle install
```

如果遇到错误，可以尝试:
```cmd
bundle clean
bundle install
```

### 步骤3: 启动本地服务器

运行以下命令启动Jekyll服务器:

```cmd
bundle exec jekyll serve
```

或者:

```cmd
jekyll serve
```

### 步骤4: 查看网站

服务器启动后，你会看到类似这样的输出:
```
Server address: http://127.0.0.1:4000/
Server running... press ctrl-c to stop.
```

在浏览器中打开: **http://localhost:4000** 或 **http://127.0.0.1:4000**

### 常用命令

- **启动服务器**: `bundle exec jekyll serve`
- **实时重载**: `bundle exec jekyll serve --livereload` (自动刷新浏览器)
- **指定端口**: `bundle exec jekyll serve --port 4001`
- **停止服务器**: 按 `Ctrl+C`

### 故障排除

1. **如果 `bundle` 命令不存在**:
   ```cmd
   gem install bundler
   ```

2. **如果遇到权限错误**:
   - 确保以管理员身份运行命令行

3. **如果端口被占用**:
   ```cmd
   bundle exec jekyll serve --port 4001
   ```

4. **清理并重新安装**:
   ```cmd
   bundle clean
   bundle install
   bundle exec jekyll serve
   ```

### 提示

- 修改文件后，Jekyll会自动重新生成网站
- 使用 `--livereload` 选项可以自动刷新浏览器
- 按 `Ctrl+C` 可以停止服务器

