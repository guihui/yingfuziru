# yingfuziru

## 微信支付
weixin://wap/pay?appid%3Dwx2421b1c4370ec43b%26noncestr%3D3e84679af4efab5f32ee9ea01b2ec290%26package%3DWAP%26prepayid%3Dwx20160504154919fdacd7bc0d0127918780%26timestamp%3D1462348159%26sign%3DC40DC4BB970049D6830BA567189B463B

url解码后

weixin://wap/pay?**appid**=wx2421b1c4370ec43b&**noncestr**=3e84679af4efab5f32ee9ea01b2ec290&**package**=WAP&**prepayid**=wx20160504154919fdacd7bc0d0127918780&**timestamp**=1462348159&**sign**=C40DC4BB970049D6830BA567189B463B
```
IWXAPI api;
PayReq request = new PayReq();
request.appId = "wxd930ea5d5a258f4f";
request.partnerId = "1900000109";
request.prepayId= "1101000000140415649af9fc314aa427",;
request.packageValue = "Sign=WXPay";
request.nonceStr= "1101000000140429eb40476f8896f4c9";
request.timeStamp= "1398746574";
request.sign= "7FFECB600D7157C5AA49810D2D8F28BC2811827B";
api.sendReq(req);
```
