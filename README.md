# 开发小技巧
## 1.禁止手机睡眠 
'[UIApplication sharedApplication].idleTimerDisabled = YES;'

## 2.跳进APP权限
'''
//跳进APP权限
    if (UIApplicationOpenSettingsURLString != NULL) {
         NSURL *url = [NSURL URLWithString:UIApplicationOpenSettingsURLString];
         [[UIApplication sharedApplication] openURL:url];
     }
'''
