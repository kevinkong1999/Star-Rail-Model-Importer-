#     <center><h1 style="font-size: 38px;"><a href="https://github.com/SilentNightSound/SR-Model-Importer/tree/main">运搬原作点击这里</a>
</h1></center> 

#      星穹mod注入工具（SRMI）

将自定义模型导入Honkai Star Rail的工具和说明。
#### 免责声明：我强烈建议只使用私人服务器进行修改。在官方星际铁路服务器上使用这些工具具有被禁止的高风险。我不容忍在官方服务器上使用这些工具和程序，如果您这样做，则对由此产生的任何后果不承担任何责任。

SRMI是3DMigoto/GIMI的一个版本，我已经修改了它以与Star Rail兼容。请注意，这里的许多文件都是从 GIMI 移植过来的，我正在为 Star Rail 修复它们 - 其中许多可能存在兼容性问题，并且可能有一些参考仍然指向 genshin 资源。

您可以根据需要随意使用此存储库中的任何脚本，但如果在项目中使用这些程序，请注明。我将继续使用新功能和修复程序更新此页面，因此请经常回来查看。

故障排除指南：[故障排除](Guides/Troubleshooting.md)

星穹铁道改装仍然是最近的，所以指南仍在进行中。许多技术与 GIMI 类似，但如需更多帮助修改，请访问  [AGMG Discord](https://discord.gg/agmg)

导入程序的模型文件位于[SR-Model-Importer-Assets](https://github.com/SilentNightSound/SR-Model-Importer-Assets)

## 安装说明（3DMigoto）
1. 下载 3dmigoto.zip并解压缩它。我提供了1个版本（要开发版的去原作那里下）：
   - “3dmigoto-SRMI-for-playing-mods.zip”是用于放mods的程序版本，它关闭了开发功能（没有绿色文本），但速度更快
2. 要加载 3dmigoto，请以管理员身份运行。请注意，exe 是从 python 编译的，因此 Windows Defender 可能会标记它 - 如果您在运行 exe 时遇到问题，因为它被阻止，我还提供了具有相同代码的代码（您需要安装 psutil 和 pyinjector 依赖项才能运行它）
  
  <kbd style="background-color: #f2f2f2; color: #333;">3DMigotoLoader.exe</kbd> <kbd style="background-color: #f2f2f2; color: #333;">3DMigotoLoader.py</kbd>
  
3. 如果到目前为止一切正确，则应将3DMigoto注入到游戏中，并且您应该会看到绿色文本叠加层（仅当使用“用于开发”版本时，“用于播放”版本不显示绿色文本）：
4. 安装完成！您现在应该能够加载自定义资源并使用 3DMigoto 覆盖纹理和着色器。要添加模组，请将它们放在 Mods 文件夹中（每个角色一次一个模组），然后按 F10 将它们加载到游戏中



