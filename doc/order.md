# 语音操作指令

####  操作例句
#####  打开空调
| 字段| 值|
| :-------- |:--------|
| order|TurnOn|
| deviceName|空调|
#####  关闭客厅空调
| 字段| 值|
| :-------- |:--------|
| order|TurnOff|
| place|客厅|
| deviceName|空调|
#####  打开美的空调摆风
| 字段| 值|
| :-------- |:--------|
| order|OpenSwing|
| deviceName|美的空调|
#####  客厅空调温度设置为25度
| 字段| 值|
| :-------- |:--------|
| order|SetTemperature|
| deviceName|空调|
| place|客厅|
| value|25|
#####  客厅空调设置为除湿模式
| 字段| 值|
| :-------- |:--------|
| order|SetMode|
| place|客厅|
| deviceName|空调|
| value|dehumidification|
#####  打开三楼所有空调
| 字段| 值|
| :-------- |:--------|
| order|TurnOn|
| place|三楼|
| deviceName|空调|
#### 参数说明：

| 指令| 解释说明【加 V的表示需要value】|
| :-------- | :--------:|
| TurnOn| 打开 |
| TurnOff| 关闭 |
| AdjustUpVolume| 声音调大 |
| AdjustDownVolume| 声音调小 |
| SetVolume| 设置音量  V|
| SetMute| 设置静音 |
| CancelMute| 取消静音 |
| Play| 播放 |
| Pause| 暂停 |
| Continue| 继续 |
| SelectChannel| 设置频道  V|
| AdjustUpChannel| 频道增加，下一首，下一台 |
| AdjustDownChannel| 频道减少，上一首，上一台 |
| ReturnTVChannel| 返回上一台 |
| SetBrightness| 设置亮度  V|
| AdjustUpBrightness| 调大亮度|
| AdjustDownBrightness| 调小亮度|
| SetTemperature| 设置温度 V|
| SetMode| 设置模式 V|
| AdjustUpTemperature| 调高温度 |
| AdjustDownTemperature| 调低温度 |
| SetWindSpeed| 设置风速  V|
| SetWindDirection | 设置风向 V|
| AdjustUpWindSpeed| 调大风速 |
| AdjustDownWindSpeed| 调小风速 |
| SetColor| 设置颜色  V|
| OpenFunction| 打开功能 |
| CloseFunction| 关闭功能 |
| Cancel| 取消 |
| CancelMode| 取消模式  V|
| OpenSwing| 打开摆风 |
| CloseSwing| 关闭摆风 |
| OpenHorizontalSwing| 打开左右摆风 |
| CloseHorizontalSwing| 关闭左右摆风 |
| OpenVerticalSwing| 打开上下摆风 |
| CloseVerticalSwing| 关闭上下摆风 |
| TimingTurnOn| 定时打开  V|
| TimingTurnOff| 定时关闭  V|
| OpenTiming| 打开定时|
| CloseTiming| 关闭定时|
| SetTiming| 设置定时  V|
| OpenNegativeIons| 打开负离子|
| CloseNegativeIons| 关闭负离子|
| OpenMenu| 打开菜单|
| CloseMenu| 关闭菜单|
| Speed| 快进|
| Setreat| 后退|
| SetSignal| 设置信号源 V|
| OpenDiscBin | 打开碟仓|
| CloseDiscBin| 关闭碟仓|
| OpenChildLock | 打开童锁|
| CloseChildLock| 关闭童锁|
| Amplify | 放大|
| Reduce| 缩小|
| OpenMediumTemp| 打开保温|
| CloseMediumTemp| 关闭保温|

#### 空调模式说明：

| 空调模式列表| 模式说明|
| :-------- | :--------:|
| airsupply| 送风模式|
| dehumidification | 除湿模式|
| cold| 制冷模式|
| heat | 制热模式|
| auto| 自动模式|

#### 空调风速说明：

| 空调风速列表| 模式说明|
| :-------- | :--------:|
| low| 1档【最低】|
| medium | 2档【中档】|
| high| 3档【最高】|
