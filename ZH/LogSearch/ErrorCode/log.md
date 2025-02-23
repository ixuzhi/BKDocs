## 权限中心

| 错误码 | 模块 | 注释 |
| :--- | :---: | ---: |
| 3699001 | 权限中心 | 动作 ID 不存在 |
| 3699002 | 权限中心 | 资源 ID 不存在 |
| 3699003 | 权限中心 | 获取系统信息错误 |
| 3699403 | 权限中心 | 权限校验不通过 |

## 数据源接入

| 错误码 | 模块 | 注释 |
| :--- | :---: | ---: |
| 3621601 | ES 源接入 | 暂不支持的场景 |
| 3621602 | ES 源接入 | 探测 ES 连通性失败 |
| 3621603 | ES 源接入 | EsClient 连接失败 |
| 3621604 | ES 源接入 | EsClient 查询 index 失败 |
| 3623301 | 索引集接入 | 索引集不存在 |
| 3623302 | 索引集接入 | 结果数据表在计算平台中不存在 |
| 3623305 | 索引集接入 |  索引集名称重复|
| 3623306 | 索引集接入 | 索引在 ES 中不存在 |
| 3623307 | 索引集接入 |  接入索引在索引集已存在|
| 3623308 | 索引集接入 |  索引字段不一致，无法添加索引到同一个索引集中|
| 3623310 | 索引集接入 | 索引集不支持跨业务 |

## 日志采集

| 错误码 | 模块 | 注释 |
| :--- | :---: | ---: |
| 3631001 | 日志采集 | 采集配置不存在 |
| 3631101 | 日志采集 | 参数校验异常：采集项 ID 不存在 |
| 3631102 | 日志采集 | 参数校验异常：采集任务 ID 不存在 |
| 3631103 | 日志采集 | 参数校验异常：采集实例 ID 不存在 |
| 3631104 | 日志采集 | 采集项名称已存在 |
| 3631105 | 日志采集 | 数据链路 ID 不存在 |
| 3631106 | 日志采集 | 无法查询到该订阅配置信息 |
| 3631107 | 日志采集 | 采集项在停止状态下不能编辑 |
| 3631201| 日志采集 | 集群不存在 |
| 3631202| 日志采集 | bk_biz_id 为必填字段，且为整数 |
| 3631204| 日志采集 | 集群连接异常 |
| 3631205| 日志采集 | 集群不存在 |
| 3631206| 日志采集 | 未知的 ES 服务端版本类型 |
| 3631207| 日志采集 | http 探测 ES 版本错误 |
| 3631301| 日志采集 | 暫不支持的清洗类型 |
| 3631302| 日志采集 | 分隔符配置解析异常 |
| 3631303| 日志采集 | 字段提取预览失败，请检查提取规则与数据是否匹配 |
| 3631304| 日志采集 | 解析数据时间字段异常 |
| 3631305| 日志采集 | 解析时间格式异常 |
| 3631306| 日志采集 | 字段名总长度超过 256，暂不支持 |
| 3631307| 日志采集 | 该业务已超出公共集群容量限制 |
| 3631401| 日志采集 | kafka 连接失败 |
| 3631402| 日志采集 | Partition 信息获取失败 |

## 日志检索

| 错误码 | 模块 | 注释 |
| :--- | :---: | ---: |
| 3624401 | 日志检索 | 检索的索引集不存在 |
| 3624402 | 日志检索 | 找不到索引集的时间字段信息，无法进行检索 |
| 3624403 | 日志检索 | 将时间字段转换异常|
| 3624418 | 日志检索 | 超出最大查询数量 |
| 3624422 | 日志检索 | 此索引没有找到时间字段类型 |
