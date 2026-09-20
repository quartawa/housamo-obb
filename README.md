# housamo-obb

`jp.co.lifewonders.housamo` 的商店额外资源包，用于避免分发的apk包无法进入游戏的问题。

**只安装 APK 不代表资源已经齐全。** Google Play 安装的 APK 与手动安装的原 APK 完全一致，但商店还下载了独立 OBB。

~~你游不愧是老古董了，这个资源架构至少是10s的了~~

## 安装步骤

### 1. 从正常运行的商店版备份

1. 从 Google Play 安装游戏，确认能够正常启动。
2. 保存账号引继信息及需要保留的游戏数据。OBB 是公共游戏资源，不能替代账号或存档备份。
3. 提取用于修补的原 APK，并备份游戏的整个 OBB 目录：

   ```text
   /sdcard/Android/obb/jp.co.lifewonders.housamo/
   ```

4. 确认电脑端备份完整后，再卸载原版。卸载可能同时删除游戏数据和 OBB。

如果已有本目录的 OBB，且 APK 与上表配套，可以使用这份资源，无需重复从商店下载。

### 2. 安装 APK

安装apk

### 3. 恢复 OBB，再打开游戏

将 OBB 原样复制到下面的完整路径，保留文件名，**不要解压**：

```text
/sdcard/Android/obb/jp.co.lifewonders.housamo/main.1377.jp.co.lifewonders.housamo.obb
```

不要放到 `Android/data`、下载目录或 HET 的私有目录。
