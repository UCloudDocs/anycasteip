

# 查看详情
已绑定的资源，可在控制台查看当前资源的健康检查状态，后端会自动屏蔽检查失败的节点，将访问流量送至健康的资源节点。云主机，默认检查运行状态，“运行”即视为健康，否则为不健康；负载均衡ULB，全部VServer健康检查均失败，则该节点为不健康，否则均视为健康。

## 操作步骤
1，进入**基础网络 UNet**，**AnycastEIP**标签页，选定需要查看节点健康状况的AnycastEIP实例，进入**详情-资源管理**。

2，每一个绑定的资源，右侧均显示当前的健康检查状态。

![](/images/healthcheck.png)

