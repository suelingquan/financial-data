# financial-data

金融行业相关数据仓库，包含动量策略分析报告所使用的全部数据。

---

## 📁 目录结构

```
financial-data/
└── Data-Repository/
    ├── README.md
    │
    ├── 00_原始数据/
    │   ├── 01_个股周度交易数据/
    │   │   ├── stock_2018.csv
    │   │   ├── stock_2019.csv
    │   │   ├── stock_20200101_20201101.csv
    │   │   ├── stock_20201201_20211001.csv
    │   │   ├── stock_20211001_20220801.csv
    │   │   ├── stock_20220801_20230501.csv
    │   │   ├── stock_20230501_20240201.csv
    │   │   ├── stock_20240201_20241001.csv
    │   │   ├── stock_20241001_20250701.csv
    │   │   ├── stock_20250701_20260301.csv
    │   │   ├── stock_20260301_20260529.csv
    │   │   └── README.md
    │   │
    │   ├── 02_股本与市值数据/
    │   │   ├── marketcap_2018.csv
    │   │   ├── marketcap_2019.csv
    │   │   ├── marketcap_20200101_20201201.csv
    │   │   ├── marketcap_20201201_20211001.csv
    │   │   ├── marketcap_20211001_20220801.csv
    │   │   ├── marketcap_20220801_20230501.csv
    │   │   ├── marketcap_20230501_20240201.csv
    │   │   ├── marketcap_20240201_20241101.csv
    │   │   ├── marketcap_20241101_20250701.csv
    │   │   ├── marketcap_20250701_20260301.csv
    │   │   ├── marketcap_20260301_20260529.csv
    │   │   └── README.md
    │   │
    │   ├── 03_股票估值数据/
    │   │   ├── valuation.zip
    │   │
    │   └─
    │       ├── THRFACDAT_WEEKLY.csv      # Fama-French周三因子
    │       ├── RESSET_BDSHIBOR.csv       # 隔夜Shibor
    │       ├── 000300.SH.csv             # 沪深300指数
    │       └── README.md
    │
    ├── _处理后数据/
    │   ├── processed_data.zip            # 完整数据（分卷压缩）
    │   ├── processed_data.z01
    │   ├── processed_data.z02
    │   └── README.md
    │
    └── 
        ├── WML策略周度收益率序列/
        │   ├── wml_4w.csv
        │   ├── wml_8w.csv
        │   ├── wml_12w.csv
        │   ├── wml_24w.csv
        │   ├── wml_48w.csv
        │   └── README.md
        ├── 彩票因子分析结果/
        │   ├── lottery_factors_full.csv
        │   ├── lottery_double_sort_results.csv
        │   ├── table6_1_lottery_results.csv
        │   └── README.md
        └── 因子动量分析结果/
            ├── factor_momentum_regression.csv
            └── README.md
```

---

## 📊 数据来源

| 数据类别 | 来源 | 时间范围 | 文件数 |
|:---|:---|:---|:---|
| 个股周度交易数据 | CCER | 2018-01-05 ~ 2026-05-29 | 11个CSV |
| 股本与市值数据 | CCER | 2018-01-05 ~ 2026-05-29 | 11个CSV |
| 股票估值数据 | CCER | 2018-01-05 ~ 2026-05-29 | 11个CSV |
| Fama-French三因子 | RESSET | 2018-01-05 ~ 2026-03-31 | 1个CSV |
| 隔夜Shibor | RESSET | 2018-01-02 ~ 2026-05-06 | 1个CSV |
| 沪深300指数 | Wind | 2018-01-05 ~ 2026-05-29 | 1个CSV |

---

## 📈 核心数据文件

| 文件 | 说明 | 大小 |
|:---|:---|:---|
| `processed_data.zip` | 清洗后完整数据（133万行） | 约3.8GB（分卷压缩） |
| `lottery_factors_full.csv` | 彩票因子完整数据 | 约3.8GB |
| `wml_24w.csv` | 24周WML策略收益序列 | 约1MB |

---

## 📝 字段说明

详见各子文件夹下的 `README.md`。

- [个股周度交易数据说明](./00_原始数据/01_个股周度交易数据/README.md)
- [股本与市值数据说明](./00_原始数据/02_股本与市值数据/README.md)
- [股票估值数据说明](./00_原始数据/03_股票估值数据/README.md)
- [处理后数据说明](./01_处理后数据/README.md)

---

## 🔗 相关仓库

- 代码与论文仓库：[Python-Finance-Course-Practice]
