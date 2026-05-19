# 投放数据处理面板

本地网页工具：上传订单分析 CSV，生成三表结构 XLSX。

## 启动

Mac:

```bash
python3 web_app.py
```

Windows:

```bat
python web_app.py
```

打开：

```text
http://127.0.0.1:8765
```

## 依赖

```bash
pip install -r requirements.txt
```

## 输出

- `直播投放数据源`：CSV 源数据
- `数据情况横向`：分类汇总，除零结果显示为 0
- `结算整理表`：结算字段，不包含重复的 `* 2` 字段
