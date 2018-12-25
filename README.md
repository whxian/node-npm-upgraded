# MAC升级Nodejs和Npm到最新版

1. 查看本机node.js版本： 
   ```
   node -v
   ```

2. 清除node.js的cache：
   ```
   sudo npm cache clean -f
   ```

3. 安装 n 工具，这个工具是专门用来管理node.js版本的，别怀疑这个工具的名字，是他是他就是他，他的名字就是 "n"： 
   ```
   sudo npm install -g n
   ```

4. 安装最新版本的node.js：
   ```
   sudo n stable
   ```

5. 再次查看本机的node.js版本：
   ```
   node -v
   ```

6. 更新npm到最新版：
   ```
   sudo npm install npm@latest -g
   ```

7. 验证： 
   ```
   node -v
   npm -v
   ```
