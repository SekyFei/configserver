```java
package com.seky.controller;

import org.springframework.beans.factory.annotation.Value;
import org.springframework.web.bind.annotation.RequestMapping;
import org.springframework.web.bind.annotation.RestController;

@RestController
public class ConfigClinetController {
	@Value("${name}")
	private String name;
	@Value("${password}")
	private String password;
	@Value("${countTime}")
	private String countTime;
	
	@RequestMapping("/profile")
	public String getProfile(){
		System.out.println("name:" + name);
		System.out.println("password:" + password);
		System.out.println(this.countTime);
		return "name:" + name + " password:" + password;
	}
}
```

<font face="黑体">我是黑体字</font>
<font face="微软雅黑">我是微软雅黑</font>
<font face="STCAIYUN">我是华文彩云</font>
<font color=#0099ff size=12 face="黑体">黑体</font>
<font color=#00ffff size=3>null</font>
<font color=red size=5>graysss
地方vsdjfsdfjsdo;看看书的山东播剧so网卡进入个人沃尔夫我也色粉色来看看按时发放时发送栏开发我看反馈了违法
</font>


| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |