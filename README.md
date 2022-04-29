# PicGo-Images
PicGo 图床上传

token：
  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
  
  
插件：
  name: picgo-plugin-rename-file
  curl: https://github.com/liuwave/picgo-plugin-rename-file
  setting: {localFolder:1}/{origin}
  命名规则：
       - {y} 年，4位
       - {m} 月，2位
       - {d} 日期，2位
       - {h} 小时，2位
       - {i} 分钟，2位
       - {s} 秒，2位
       - {ms} 毫秒，3位(v1.0.4)
       - {timestamp} 时间戳(秒)，10位(v1.0.4)
       - {hash}，文件的md5值，32位
       - {origin}，文件原名（会去掉后缀）
       - {rand:<count>}, 随机数，<count>表示个数，默认为6个，示例：{rand：32}、{rand}
       - {localFolder:<count>}, <count>表示层级 ，默认为1，示例：{localFolder:6}、{localFolder}
