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
地方vsdjfsdfjsdo;看看书的山东播剧so网卡进入个人沃尔夫<br/>我也色粉色来看看按时发放时发送栏开发我看反馈了违法
</font>


| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

浅红色文字：<font color="#dd0000">浅红色文字：</font><br /> 
深红色文字：<font color="#660000">深红色文字</font><br /> 
浅绿色文字：<font color="#00dd00">浅绿色文字</font><br /> 
深绿色文字：<font color="#006600">深绿色文字</font><br /> 
浅蓝色文字：<font color="#0000dd">浅蓝色文字</font><br /> 
深蓝色文字：<font color="#000066">深蓝色文字</font><br /> 
浅黄色文字：<font color="#dddd00">浅黄色文字</font><br /> 
深黄色文字：<font color="#666600">深黄色文字</font><br /> 
浅青色文字：<font color="#00dddd">浅青色文字</font><br /> 
深青色文字：<font color="#006666">深青色文字</font><br /> 
浅紫色文字：<font color="#dd00dd">浅紫色文字</font><br /> 
深紫色文字：<font color="#660066">深紫色文字</font><br /> 
