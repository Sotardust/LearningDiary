### Android 5.0
1. 运行机制，采用ART 安装时转换为机器语言，成为真正的本地应用
2. 新推出Material Design，用户切换Activity时候无缝过渡位移动画
3. 通知详情可以用户自己设计
### Android 6.0
1. 运行时权限
2. 使用Builder模式来构造通知
3. 取消了Apache HTTP 客户端
4. 低耗电模式，设备处于空闲状态，推迟CPU和网络活动
5. 秘钥库变更，不在支持DSA，单依旧 支持ECDSA
6. 相机Camera变更为Camera2 ，之前是先到先得，现在是按照优先使用级别使用
### Android 7.0
1. 多窗口支持
2. 增强 通知功能，如直接回复
3. JIT/AOT编译（Just In Time，Ahead Of Time）
4. 随时随地的低耗电，关闭屏幕一段时间就会限制CPU的网络活动
5. 快速设置
6. 号码屏蔽
7. 来电过滤

### Android 8.0
1. 后台执行限制，减少电量使用，提高电池寿命
2. 后台位置限制，减少位置更新频率
3. 隐私性
4. 权限

### 着重记录理解

1. 5.0 推出的ART虚拟机，在5.0之前都是Dalvik，他们的区别是：
    Dalvik每次运行，字节码都需要通过即时编译转换成机器码（JIT）
    ART第一次安装应用的时候，字节码就会预先编译成机器码（AOT）
2. 6.0 运行时权限申请
3. 7.0 多窗口支持，V2签名   

