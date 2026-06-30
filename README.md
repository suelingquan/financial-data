# financial-data
金融行业相关数据
📁 Data-Repository/
│
├── README.md                              # 仓库总说明
│
├── 📁 00_原始数据/
│   │
│   ├── 📁 01_个股周度交易数据/
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
│   │   └── README.md                     # 字段说明
│   │
│   ├── 📁 02_股本与市值数据/
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
│   ├── 📁 03_股票估值数据/
│   │   ├── valuation_2018.csv
│   │   ├── valuation_2019.csv
│   │   ├── valuation_20200101_20201201.csv
│   │   ├── valuation_20201201_20211001.csv
│   │   ├── valuation_20211001_20220801.csv
│   │   ├── valuation_20220801_20230501.csv
│   │   ├── valuation_20230501_20240201.csv
│   │   ├── valuation_20240201_20241101.csv
│   │   ├── valuation_20241101_20250701.csv
│   │   ├── valuation_20250701_20260301.csv
│   │   ├── valuation_20260301_20260529.csv
│   │   └── README.md
│   │
│   ├── 📁 04_辅助数据/
│   │   ├── THRFACDAT_WEEKLY.csv          # Fama-French三因子
│   │   ├── RESSET_BDSHIBOR.csv           # 隔夜Shibor
│   │   ├── 000300.SH.csv                 # 沪深300指数
│   │   └── README.md
│   │
│   └── README.md                          # 原始数据总说明
│
├── 📁 01_处理后数据/
│   ├── processed_data.zip               # 完整数据（分卷压缩）
│   ├── processed_data.z01
│   ├── processed_data.z02
│   └── README.md                         # 处理后数据说明
│
└── 📁 02_实证结果/
    ├── 📁 WML策略周度收益序列/
    │   ├── wml_4w.csv
    │   ├── wml_8w.csv
    │   ├── wml_12w.csv
    │   ├── wml_24w.csv
    │   ├── wml_48w.csv
    │   └── README.md
    ├── 📁 彩票因子分析结果/
    │   ├── lottery_factors_full.csv
    │   ├── lottery_double_sort_results.csv
    │   ├── table6_1_lottery_results.csv
    │   └── README.md
    └── 📁 因子动量分析结果/
        ├── factor_momentum_regression.csv
        └── README.md
