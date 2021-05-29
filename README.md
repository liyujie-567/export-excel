# 导出excel

## Project setup
```
npm install xlsx -S
```

```
import excel from 'excel.js'

// 导出配置 当key和data为空数组时，即下载模板功能
const params = {
  key: ['name', 'value', 'unit'] || [],
  title: ['名称', '目标值', '单位'],
  data: arr || [],
  autoWidth: true,
  filename: '导出excel'
}
// 调用导出函数
excel.export_array_to_excel(params)
```