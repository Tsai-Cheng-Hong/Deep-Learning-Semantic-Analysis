# Deep-Learning 深度學習-繁體中文的語意分析(正面、負面分類)Semantic-Analysis

深度學習-自然語言處理-繁體中文的語意分析(正面、負面分類)

這篇文章為 使用Tensorflow的Keras進行文件分類

需要先用pip install or conda install 安裝環境套件

我的tensorflow是2.2.0版本
python是3.8 

然後下載dataset放到正確的路徑即可

這邊放上dataset的下載連結 https://drive.google.com/drive/folders/1mst-U0QtMidXaxWXZP82WMThtFFUV5ZR?usp=sharing

還有pre-trained model的下載連結 https://drive.google.com/drive/folders/1QEbdEn-DO-23hYCLgaB3f4vP8e8L8iIp?usp=sharing

環境安裝好後即可python semantic_analysis.py執行程式

訓練流程:

1.Dataset & Label : 網路下載

2.特徵萃取 : Word2Vec

3.特徵選擇 : LSTM

4.分類器 : 3-Layer Fully Connect


------------------------------------------------------------------------

可以試一試使用不同的語言模型進行訓練

不同的語言模型將會有不一樣的成效

各式語言模型:https://github.com/Tsai-Cheng-Hong/Deep-Learning-Word-Embedding
