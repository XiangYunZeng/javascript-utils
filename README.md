<!--
 * @Author: Zengxiangyun
 * @Date: 2023-02-21 14:39:39
 * @LastEditTime: 2023-02-21 15:20:57
 * @Description: 
-->
> 常用工具函数

## 安装

```bash
$ yarn add @zxy-space/javascript-utils
```

## 使用

```js
import { debounce } from '@zxy-space/javascript-utils'

// 全量引用
// import * as utils from '@zxy-space/javascript-utils'
```

### 已有方法

|         工具名          |              描述              | Nodejs 可用 |
|:--------------------:|:----------------------------:|:---------:|
|       realType       |           获取数据真实类型           |     ✔     |
|       isObject       |            是否为对象             |     ✔     |
|       isRegexp       |           是否为正则表达式           |     ✔     |
|      isFunction      |            是否为函数             |     ✔     |
|      isImageUrl      |        判断 url 是否为图片路径        |     ✔     |
|       isNumber       |            是否为纯数字            |     ✔     |
|       isEmpty        |             是否为空             |     ✔     |
|      isBoolean       |            是否为布尔值            |     ✔     |
|      toBoolean       |        转换 string 布尔值         |     ✔     |
|   toLowerCamelCase   |           下划线转小驼峰            |     ✔     |
|     toUnderline      |          小驼峰转下划线分割           |     ✔     |
|     toPascalCase     |           中横线转大驼峰            |     ✔     |
|   formatThousandth   |            数字千分位             |     ✔     |
|      countDown       |             倒计时              |     ✖     |
|       debounce       |              防抖              |     ✔     |
|       deepCopy       |             深拷贝              |     ✔     |
|     searchParams     |        获取 URL 单个查询参数         |     ✔     |
|  formatQueryParams   |        获取 URL 全部查询参数         |     ✔     |
|    createRandomID    |           生成随机 ID            |     ✔     |
| objectKeyToCamelCase |      Object key 转换为小驼峰       |     ✔     |
|          ua          | 对 `navigator.userAgent` 进行解析 |     ✖     |
|       dCookie        |         `cookie` 操作          |     ✖     |
|     generateTree     |          一维数组转树形数据           |     ✔     |
|      throwError      |          统一报错信息处理           |     ✔     |
|      debugWarn       |          警告信息统一处理           |     ✔     |

### ua 示例

```js
import { ua } from '@zxy-space/javascript-utils'

console.log(ua())

```