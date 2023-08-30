
# colab_diffusers_with_civitai_checkpoint_model

GoogleColab上で[civitai](https://civitai.com/)のモデルを[Diffusers](https://huggingface.co/docs/diffusers/index)で読み込み、画像生成を行う事のできるノートブックです


## Colab

<a href="https://colab.research.google.com/github/HawkClaws/colab_diffusers_with_civitai_checkpoint_model/blob/main/colab_diffusers_with_civitai_checkpoint_model.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>


## 使い方
1. [civitai/model](https://civitai.com/models)にアクセスします
2. モデルにフィルターを掛けます<br>
使用できるモデルはCheckpointかつ、SDモデルのみ(SDXLは未対応)です
![image](./images/htu1.png)
3. モデルのダウンロードリンクをコピーします
![image](./images/htu2.png)
4. MODEL_URLにダウンロードリンクを貼り付けます
5. Setupのコードを実行します
6. 画像生成のパラメータ（プロンプト）を入力しGenerate Imageのコードを実行します