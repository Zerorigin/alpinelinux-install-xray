# alpinelinux-install-xray

A fork of [alpinelinux-install-v2ray](https://github.com/v2fly/alpinelinux-install-v2ray).

This is a Xray install script for Alpine Linux.

## 依賴軟體

### 安裝 cURL

```
# apk add curl
```

## 下載

```
$ curl -O https://raw.githubusercontent.com/Zerorigin/alpinelinux-install-xray/master/install-release.sh
```

## 使用

```
# ash install-release.sh
```

## 管理指令

### 啟用

```
# rc-update add xray
```

### 禁用

```
# rc-update del xray
```

### 啟動

```
# rc-service xray start
```

### 關閉

```
# rc-service xray stop
```

### 重啟

```
# rc-service xray restart
```
