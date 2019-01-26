# trimpayForSSRPanel
您可在此获取 SSRPanel 的手动对接文件


SQL语句：
```
INSERT INTO config values ('201', 'is_trimepay', 0);
INSERT INTO config VALUES ('202', 'trimepay_appid', '');
INSERT INTO config VALUES ('203', 'trimepay_appsecret', '');
ALTER TABLE `payment` CHANGE `qr_local_url` `qr_local_url` TEXT CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci NULL DEFAULT NULL COMMENT '支付二维码的本地存储URL';
```
