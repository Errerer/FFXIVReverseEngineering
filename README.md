# FFXIVReverseEngineering
### 纯记录逆向的结果   要用自己转sig格式  太底裤的没有.jpg 

## 传送主要逻辑
40 ?? 53 56 57 41 ?? 41 ?? 41 ?? 41 ?? 48 ?? ?? ?? ?? 48 ?? ?? ?? ?? ?? ?? 48 ?? ?? ?? ?? ?? ?? 48 ?? ?? 48 89 45 ?? 8B ?? ?? ?? ?? ?? 45 ?? ??


## 传送按钮
e8 ?? ?? ?? ?? ba ?? ?? ?? ?? 0f ?? ?? ?? 33 ??

## 传送读条
48 89 5c 24 ?? 57 48 ?? ?? ?? 48 ?? ?? 48 ?? ?? 48 ?? ?? ?? 48 ?? ?? 74 ?? 85 ?? 78 ?? 48 ?? ?? ??


## 上坐骑不读条 （潜水情况崩溃）
48 89 5c 24 ? 57 48 ? ? ? 48 ? ? 48 ? ? ? ? ? ? e8 ? ? ? ? 48 ? ? ? ? ? ? 48 ? ? ff 50 ? 

## 坐骑上移速
40 ? 48 ? ? ? 48 ? ? e8 ? ? ? ? 48 ? ? ? ? ? ? 48 ? ? 33 ? 89 43 ? 88 43 ? 48 89 43 ? 

## 坐骑加载和移除（Client__Game__Character）
44 89 4c 24 ?? 44 89 44 24 ?? 53 57


## 修理主逻辑
40 ? 41 ? 41 ? 48 ? ? ? 8b ? 45 ? ? ? 48 ? ? ? ? ? ? 45 ? ? ? 

## 全部修理? 还是发包把
48 89 5c 24 ? 48 89 6c 24 ? 48 89 74 24 ? 48 89 7c 24 ? 41 ? 48 ? ? ? 41 ? ? ? 8b ? b3 ? 
