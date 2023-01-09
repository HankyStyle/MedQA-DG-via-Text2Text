# MedQA-DG-via-Text2Text
使用 Text2Text 生成 MedQA 的 Distractors

### 資料架構
```
.
├── README.md
├── data // MedQA 資料集支援 TW Mainland US 版本的問題與參考書  
|   ├── questions
│   │   ├── Mainland
│   │   ├── Taiwan
│   │   └── US
|   └── textbooks
│       ├── en
│       ├── zh_paragraph
│       └── zh_sentence
└── modeling // Model 訓練與存放路徑
    ├── bart-base
    └── biobart-base
        ├── train // Model Train Script
        |   └── model // Save Model in this Folder
        └── eval  // Model Evaluation Script

```
