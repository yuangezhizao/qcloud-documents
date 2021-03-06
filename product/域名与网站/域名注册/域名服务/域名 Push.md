域名 Push 为您提供将当前账号下的域名使用权转移至其他腾讯云用户的功能。本文档指导您通过域名 Push，将 A 账号下的域名转移至 B 账号 ID 名下。
>!
- 域名转移成功后，新的账号将拥有该域名的使用权限，包括但不限于信息修改、域名转移、解析管理等。
- 转移账号仅支持腾讯云中国主账号，不支持协作者、子用户及国际账号。

## 操作步骤
### 发起域名 Push 请求
1. 登录腾讯云 [域名注册控制台](https://console.cloud.tencent.com/domain/push)，进入 “域名 Push” 管理页面。
2. 在 “域名 Push” 管理页面中，单击【我要 Push】。如下图所示：
![](https://main.qcloudimg.com/raw/968ef56a5fc45b5ddadbf82c7362db0e.png)
3. 进入 “我要 Push” 管理页面，填写相关信息。如下图所示：
![](https://main.qcloudimg.com/raw/f3e152e6fd71101180fdf47fcd829bac.png)
 - **选择域名：**请输入需要 Push 的域名，每行一个，最多支持4000个。例如 dnspod.cn、tencent.com。
 - **Push 接收账号：**请输入转移接收方的账号 ID 并单击【确认】。
 >?您可以通过 **[账号信息](https://console.cloud.tencent.com/developer) > 基本资料 > 账号 ID** 获取账号 ID，该账号 ID 是用户在腾讯云的唯一账号标识。
 - **Push 类型：**若选择【免费转移】，Push 接收账号将免费接收转移域名。
>?暂不支持带价 Push。
>
 - **重置 DNS 解析：**重置 DNS 解析将会清除域名所有解析数据，该操作无法撤回，如域名已有线上业务，请勿选择该项。
 - **转移锁定：**如您需将域名转出腾讯云，请您在发起域名 Push 时，**请勿勾选**【开启 “60天内禁止转移注册商锁定”】，否则转入域名后60天内不能转出。
 >?根据国际互联网域名与地址管理机构（ICANN）的 转让政策规定，修改域名信息后60天内，禁止将域名从当前接入商转出。
 >
 - **附言：**接收方接收之前可看到的附言，输入内容在200字符内。
4. 单击【下一步】，在弹出的 “身份验证” 窗口中，获取并填写短信验证码，并单击【确定】。如下图所示：
![](https://main.qcloudimg.com/raw/baab6a00f06feaf18930d93f1ef29f4d.png)
5. 在 “转移信息确认” 窗口中，确认 Push 接收账号 ID 等信息，并单击【确认提交】，即可完成操作。如下图所示：
![](https://main.qcloudimg.com/raw/9cc55a3dcf75efe5b48b4ae0f35ecd1e.png)
6. 发起域名 Push 请求后，请等待 Push 接收账号确认，确认后将完成域名 Push。


### 接收域名 Push 请求
1. 登录腾讯云 [域名注册控制台](https://console.cloud.tencent.com/domain/push)，进入 “域名 Push” 管理页面。
2. 在 “域名 Push” 管理页面中，单击【收到的请求】页签。
3. 在【收到的请求】页签中，选择您需要接收的域名并单击【接收】。如下图所示：
![](https://main.qcloudimg.com/raw/c123fad6dcb73b8c39d767f176cfda90.png)
4. 在 “接收域名” 页，单击【支付并接收】，即可完成接收域名 Push 请求操作。如下图所示：
![](https://main.qcloudimg.com/raw/6e85ba844b2549094fa073e81ed599ae.png)
>?如您无已通过实名认证的信息模板，需重新创建信息模板。具体操作可参考 [信息模板管理](https://cloud.tencent.com/document/product/242/15435)。


