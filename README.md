# Jable TVBox 數據源

## TVBox 配置

### 方法一：使用配置文件

下載 `tvbox_config.json` 並導入 TVBox

### 方法二：手動添加

```json
{
  "sites": [
    {
      "key": "jable",
      "name": "Jable",
      "type": 1,
      "api": "https://raw.githubusercontent.com/andyau98/Jab/main/tvbox_jable.json",
      "searchable": 1,
      "quickSearch": 0,
      "filterable": 0
    }
  ]
}
```

## 文件說明

- `tvbox_jable.json` - TVBox 主數據源
- `api.json` - 完整 API 格式
- `tvbox_config.json` - TVBox 配置文件
- `jable_playlist.m3u` - M3U 播放列表

## 更新時間
Fri Apr  3 20:47:39 HKT 2026
