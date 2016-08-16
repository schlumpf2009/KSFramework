
配置表的热重载比较简单，只需执行菜单项就可以了。


执行菜单KEngine->Setting-> **Reload All Settings** 中的功能项，实现重载配置表。

执行后，所有配置表就会被重载。

值得注意的是，它有两种模式：

- 运行模式，它只会将已经加载过的表进行重载，保证惰式加载的正常运作；
- 编辑器非运行状态，它会将所有的表全部进行重载，以方便策划进行检查有无填表异常；


## 代码重载

您也可以通过以下代码手工实现配置表重载。

```csharp
// 重载所有表
SettingsManager.AllSettingsReload();
```