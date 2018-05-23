# Tianyancha
天眼查爬虫API，一行代码将目标企业的工商信息分门别类地保存为Excel文件。

## 运行环境
[Jupyter Notebook](http://jupyter.org/)，建议使用[Anaconda](https://www.anaconda.com/download/)下载安装运行环境。

## 使用方法
1. 下载仓库到本地
2. 打开`Tianyancha.ipynb`
3. 输入查询公司的名称并运行所有代码块
5. 程序开始运行，对分类信息开始依次爬取，输出结果范例为`中信.xlsx`

## 改进方向
1. 非阻塞方法：代理池，引用，Headers的设置
2. 性能提升
3. API化：类似`get_company_info(keyword)`
