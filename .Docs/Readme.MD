# Content / 目次 / 目錄

Please select a language below.
次の言語に選んでください。
請於下方選擇所閱讀的語言。

* [Update for Installation Guide](#Update-for-Installation-Guide)
* [インストール説明の更新](#インストール説明の更新)
* [安裝手冊更新](#安裝手冊更新)

`=========================================================================`

# Update for Installation Guide

This document is update for the re-build the project and some code explanation for project "AI Kernel".

## Hardware Prepration

- [x] [Intel Core i7-9700K Processor 12M Cache, up to 4.90 GHz](https://ark.intel.com/content/www/us/en/ark/products/186604/intel-core-i7-9700k-processor-12m-cache-up-to-4-90-ghz.html)
- [x] [DDR4 2666 16GB SAMSUNG Original](https://www.amazon.com/dp/B07F6L771D/ref=cm_sw_r_tw_dp_U_x_HRJcDb50SGA5X) * 2
- [x] [SAMSUNG SSD 970 EVO M.2 SSD 500GB](https://www.samsung.com/us/computing/memory-storage/solid-state-drives/ssd-970-evo-nvme-m2-500gb-mz-v7e500bw/)
- [x] [Seagate BarraCuda Hard Drive 2TB ST2000LM015](https://www.seagate.com/internal-hard-drives/hdd/barracuda/#specs-2-5)
- [x] [GEFORCE RTX 2080 8 GB GDDR6](https://www.nvidia.com/en-us/geforce/graphics-cards/rtx-2080/#specs)

## OS, API & Specs

* Ubuntu 16.04 LTS x64
* NVidia CUDA Toolkit 10.1 Update 1 
* NVidia cuDNN v7.6.0 (May 20, 2019), for CUDA 10.1
* NVidia DIGITS v6.1.1 (From Github)
* DeepQA (GitHub - Conchylicultor/DeepQA)
* Facebook fastText
* Jieba zh-tw [*already Project build-in]
* Python Flask
* Python SpeechRecognition
* Other relative libraries 
* Unity version 5.6.2f1
* Xcode 8.0
* IOS 11

## Installation

* [Python Install](#)
* [GPU Driver Install](#)
* [CUDA Toolkit Install](#)
* [cuDNN Install](#)
* [OpenCV Install](#)
* [Caffe Install](#)
* [DIGITS Install](#)
* [DeepQA Install](#)
* [SpeechRecognition Install](#)

## Code description

* [Repo & Structure](RepoAndStructure.MD#repo--structure)
* [AWWW_chatbot_response.py](#)
* [AWWW_jiebaCut.py](#)
* [AWWW_pic_pred.py](#)
* [AWWW_wav_to_STT.py](#)
* [AWWW_wav_to_spectro.py](#)
* [AWWW_web.py](#)

## Execution

* [Start with System](StartWithSystem.MD#start-with-system)


`=========================================================================`

# インストール説明の更新

このマニュアルの作成は二度のこのAI Kernelのビルドアップとコードの説明の為にを更新する。

## ハードウェアの準備

- [x] [インテル Core i7-9700K プロセッサー 12M キャッシュ、最大 4.90 GHz](https://ark.intel.com/content/www/jp/ja/ark/products/186604/intel-core-i7-9700k-processor-12m-cache-up-to-4-90-ghz.html)
- [x] [DDR4 2666 16GB SAMSUNG Original](https://www.amazon.co.jp/dp/B07DNS22CR/ref=cm_sw_r_tw_dp_U_x_4NJcDb0SJ5BYC) * 2
- [x] [SAMSUNG SSD 970 EVO M.2 SSD 500GB](https://www.samsung.com/semiconductor/minisite/jp/ssd/consumer/970evo/#ge_semi_anchor_stand2)
- [x] [Seagate BarraCudaハードディスク・ドライブ2TB ST2000LM015](https://www.seagate.com/jp/ja/internal-hard-drives/hdd/barracuda/#specs-2-5)
- [x] [GEFORCE RTX 2080 8 GB GDDR6](https://www.nvidia.com/ja-jp/geforce/graphics-cards/rtx-2080/#specs)

## オペレーティングシステム、アプリケーションプログラミングインタフェースとスペック

* Ubuntu 16.04 LTS x64
* NVidia CUDA Toolkit 10.1 Update 1 
* NVidia cuDNN v7.6.0 (May 20, 2019), for CUDA 10.1
* NVidia DIGITS v6.1.1 (From Github)
* DeepQA (GitHub - Conchylicultor/DeepQA)
* Facebook fastText
* Jieba zh-tw [*already Project build-in]
* Python Flask
* Python SpeechRecognition
* 他の依存ライブラリ 
* Unity version 5.6.2f1
* Xcode 8.0
* IOS 11

## 導入方法

* [Pythonのインストール](#)
* [GPU Driverのインストール](#)
* [CUDA Toolkitのインストール](#)
* [cuDNNのインストール](#)
* [OpenCVのインストール](#)
* [Caffeのインストール](#)
* [DIGITSのインストール](#)
* [DeepQAのインストール](#)
* [SpeechRecognitionのインストール](#)

## コードの説明

* [リポジトリと構造](RepoAndStructure.MD#リポジトリと構造)
* [AWWW_chatbot_response.py](#)
* [AWWW_jiebaCut.py](#)
* [AWWW_pic_pred.py](#)
* [AWWW_wav_to_STT.py](#)
* [AWWW_wav_to_spectro.py](#)
* [AWWW_web.py](#)

## 実行

* [システムと一緒に実行](StartWithSystem.MD#システムと一緒に実行)


`=========================================================================`

# 安裝手冊更新

本文件為一份針對AI Kernel的專案進行重新安裝與程式碼註解的更新說明文件。

## 硬體配置

- [x] [Intel Core i7-9700K 處理器 12M 快取記憶體，最高 4.90 GHz](https://ark.intel.com/content/www/tw/zh/ark/products/186604/intel-core-i7-9700k-processor-12m-cache-up-to-4-90-ghz.html)
- [x] [DDR4 2666 16GB SAMSUNG Original](https://www.samsung.com/semiconductor/dram/module/M378A2K43CB1-CRC/) * 2
- [x] [SAMSUNG SSD 970 EVO M.2 SSD 500GB](https://www.samsung.com/tw/memory-storage/970-evo-nvme-m2-ssd/MZ-V7E500BW/)
- [x] [Seagate BarraCuda 硬碟機 2TB ST2000LM015](https://www.seagate.com/tw/zh/internal-hard-drives/hdd/barracuda/#specs-2-5)
- [x] [GEFORCE RTX 2080 8 GB GDDR6](https://www.nvidia.com/zh-tw/geforce/graphics-cards/rtx-2080/#specs)

## 作業系統，應用程式介面與規格

* Ubuntu 16.04 LTS x64
* NVidia CUDA Toolkit 10.1 Update 1 
* NVidia cuDNN v7.6.0 (May 20, 2019), for CUDA 10.1
* NVidia DIGITS v6.1.1 (From Github)
* DeepQA (GitHub - Conchylicultor/DeepQA)
* Facebook fastText
* Jieba zh-tw [*already Project build-in]
* Python Flask
* Python SpeechRecognition
* 其他相依套件
* Unity version 5.6.2f1
* Xcode 8.0
* IOS 11

## 安裝步驟

* [Python 安裝](#)
* [GPU Driver 安裝](#)
* [CUDA Toolkit 安裝](#)
* [cuDNN 安裝](#)
* [OpenCV 安裝](#)
* [Caffe 安裝](#)
* [DIGITS 安裝](#)
* [DeepQA 安裝](#)
* [SpeechRecognition 安裝](#)

## 程式碼說明

* [GitHub源與架構](RepoAndStructure.MD#github源與架構)
* [AWWW_chatbot_response.py](#)
* [AWWW_jiebaCut.py](#)
* [AWWW_pic_pred.py](#)
* [AWWW_wav_to_STT.py](#)
* [AWWW_wav_to_spectro.py](#)
* [AWWW_web.py](#)

## 使用

* [於系統開機時一起執行](StartWithSystem.MD#於系統開機時一起執行)
