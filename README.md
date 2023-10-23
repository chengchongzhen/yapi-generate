## generate-api-code

[在线生成API代码](https://generate-api-code.onrender.com), 因为是免费的站点, 闲置时会释放服务, 所以首次访问会有点慢, 请耐心等待

自动生成api代码 示例

```js
/**
 * @description: 获取可以更改的派生指标状态列表
 * @return {*}
 */
export function getDq - updateStatusList(params, other = {}) {
  return request({
    url: '/api/checkbox/dq-updateStatusList',
    method: 'get',
    params,
    ...other
  })
}

/**
 * @description: 后端开发
 * @return {*}
 */
export function getLoad - backend - developer(params, other = {}) {
  return request({
    url: '/api/checkbox/load-backend-developer',
    method: 'get',
    params,
    ...other
  })
}
```
