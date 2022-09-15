# cisco 命令

## モード移動
- enable	特権EXECへ移動
- exit	ひとつ前へ移動
- end	コンフィギュレーションから特権EXECへ
- configure terminal	グローバルコンフィギュレーションモードへ
- interface	インターフェースコンフィギュレーションモードへ
- line	ラインコンフィギュレーションモードへ

## 参考URL
https://beginners-network.com/cisco-catalyst-command/

## 特権モード
```
enable
```
## 特権EXECモード
```
configure terminal
```

## 設定保存
```
copy running-config startup-config
```

## show
```
show ?
show version
show running-config
```
### Interface接続確認
```
show ip interface brief
```

### PPPoE確認
```
show pppoe session all
```

### Route情報確認
```
show ip route
```
