# wexin-miniProgram
微信小程序注册-部署流程

## 准备邮箱
   注册微信小程序需要邮箱，任何邮箱都可以，邮箱密码强度要高一些。
   >此邮箱将作为[微信公众平台](https://mp.weixin.qq.com)的登录帐号，请填写未被微信公众平台注册，未被微信开放平台注册，未被个人微信号绑定的邮箱。

## 申请账号
  进入[小程序注册页](https://mp.weixin.qq.com/wxopen/waregister?action=step1)，开始一步一步完成账号注册。
  ##### step1:填写邮箱和密码
  ![注册step1](https://github.com/weixiaopa/wexin-miniProgram/blob/master/imagees/mini01.png)
  >此处的密码是微信小程序的密码，请牢记。在[微信开放平台](https://open.weixin.qq.com)进行微信小程序绑定时需要此密码进行绑定。
  
  ##### step2:激活邮箱
    登录邮箱，查收激活邮件，点击激活链接。
  ##### step3: 填写主体信息
   点击激活链接后，继续下一步的注册流程。请选择主体类型选择，完善主体信息和管理员信息。
   >此处选择注册类型为“个人”，需要输入个人的身份证号码，姓名，手机号等信息。
   ![首页面](https://github.com/weixiaopa/wexin-miniProgram/blob/master/imagees/mini02.png)
   确认信息完成注册。
   
  ## 小程序相关设置
  1. 完成注册后，进入[微信公众平台](https://mp.weixin.qq.com)首页面，如下图所示：
  ![首页面](https://github.com/weixiaopa/wexin-miniProgram/blob/master/imagees/mini03.png)
  2. 点击右侧的“填写”按钮进行信息的填写，如下图所示：
  ![信息填报](https://github.com/weixiaopa/wexin-miniProgram/blob/master/imagees/mini04.png)
  > * 此页面需要上传小程序启动logo图片，图片有一定要求，具体看上图。一年之内只有5次修改的机会，因此在注册前应该准备好logo图片。
  > * 提交后，小程序进入“审核”状态，大概审核时间为几分钟，几分钟过后，重新刷新
  3. 配置服务器域名。选择左侧列表中的“</>开发”，选择此模块中的“开发设置”，在页面中的“服务器域名”模块进行配置。
  
  #### 成员管理
  在成员管理模块，添加小程序的“项目成员”和“体验成员”。对于个人版的小程序“项目成员”和“体验成员”均可以添加15个。
  
  #### 成员管理
  添加完开发者后，可以上传代码到微信平台。在小程序开发者工具中点击上侧工具栏的“上传”按钮，将代码部署到微信公众平台。
  
  
  
