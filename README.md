# think-wxpayapi

weixinpay for tp5 or tp6
## 安装

### 执行命令安装
```
composer require qingsong/think-wxpayapi
```

## 调用方法
```
        $tools = new \qingsong\wxpayapi\JsApiPay();

	$input = new \qingsong\wxpayapi\data\WxPayUnifiedOrder(); 

	$order = \qingsong\wxpayapi\WxPayApi::unifiedOrder($input);

	$notify = new \qingsong\wxpayapi\PayNotifyCallBack();
```

## 删除包
```
composer remove qingsong/think-wxpayapi
```

