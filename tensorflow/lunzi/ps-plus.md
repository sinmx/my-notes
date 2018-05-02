阿里的同学又一个 pr.


PS-Plus 相对于传统的 ParameterServer 有如下特点：
1. 高性能
2. 高灵活度
3. 完备的在线学习


### 高性能：
PS-Plus 通过智能参数分配，零拷贝，seastar 等多项技术，进一步提升了单台 server 的服务能力和系统整体的水平扩展能力。

在实测中，在 64core 的机器上单个 server 能轻松用满 55 + 的核心，在 dense 场景下 io 能打满双 25G 网卡，系统整体在 1~4000 worker 的范围内都具有近似线性的水平扩展能力

### 高度灵活：

PS-Plus 拥有完善的 UDF 接口，用户可使用 SDK 开发定制化的 UDF 插件，并且可以通过简单的 C++ 以及 Python 接口进行调用。

### 完备的在线学习支持：

PS-Plus 支持非 ID 化特征训练，特征动态增删，以及模型增量实时导出等支撑在线学习的重要特性。
