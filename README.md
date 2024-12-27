# morpho_prod_pilot
This pilot study explores the usage trends of 27 commonly used monosyllabic words proposed in 佛教與漢語詞彙. Derived from two corpora—Humanistic Buddhism Corpus (HBC) and Chinese Historical Corpus (CHC)—the study investigates their roles as prefixes and suffixes across different dynasties, calculates their morphological productivity (Baayen, 2009), and, using the word "定" as an example, analyzes its semantic similarity as a prefix and suffix across various historical periods.


Repository Structure
```
MORPH/
├── data/
│   ├── fonts/
│   │   └── TaipeiSansTCBeta-Regular.ttf 
│   ├── processed/
│   │   ├── prefix_suffix/ 
│   │   ├── HBC_combined.json  
│   │   ├── HBC_contexts.json  
│   │   └── hist_corp_contexts.json  
│   ├── raw/
│   │   ├── dev.json  
│   │   ├── test.json  
│   │   ├── train.json  
│   │   ├── hist_corp_full.csv  
│   │   └── dingfubao.csv  
├── notebooks/
│   ├── 定.ipynb  
│   ├── dingfubao_analysis.ipynb  
│   └── prod_analysis.ipynb  
├── ...
```