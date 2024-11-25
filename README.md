![image](https://github.com/user-attachments/assets/b5bc90bd-665e-4624-a033-03efca2b3b08)# point2_experiment-record
实验环境：  
<img src="https://github.com/user-attachments/assets/1ed4d349-a205-45a0-aeea-d0bc94919496" alt="description" style="width: 50%; height: auto;">  
实验参数：  
  *lr=2e-5*  
  *fuse_lr=2e-5*  
  *image_output_type=all*  
  *optim=adamw*  
  *data_type=MVSA-single*  
  *train_fuse_model_epoch=20*  
  *epoch=30*  
  *warmup_step_epoch=2*  
  *text_model=bert-base*  
  *fuse_type=att*  
  *batch_size=12*  
  *acc_grad=1*  
  *tran_num_layers=3*  
  *image_num_layers=2*  
## 实验： baseline_MVSA-single
| Accuracy | F1(weighted) | Precision(weighted) | R(weighted) | F1(macro) | Precision | R | loss
| --- | --- | --- | --- | --- | --- |  --- |   --- | 
| 0.671111 | 0.672179 | 0.677555 | 0.671111 | 0.573175 | 0.573550 | 0.577306 | 0.009768 | 

<img src="https://github.com/user-attachments/assets/5e634768-5045-415c-8ac1-a715c282a4c9" alt="description" style="width: 50%; height: auto;">

## 实验：baseline_MVSA-multiple  
| Accuracy | F1(weighted) | Precision(weighted) | R(weighted) | F1(macro) | Precision | R | loss
| --- | --- | --- | --- | --- | --- |  --- |   --- | 
| 0.674118 | 0.655297 | 0.646247 | 0.674118 | 0.511616 | 0.543621 | 0.495049 | 0.008646 | 
<img src="https://github.com/user-attachments/assets/7825323e-5bc4-4b5a-ab7f-602272faba81" alt="description" style="width: 50%; height: auto;">

## 实验：baseline_BILSTM_MVSA-single  
<img src="https://github.com/user-attachments/assets/3a906beb-1ecb-4106-b945-e86638844d3a" alt="description" style="width: 50%; height: auto;">  

| Accuracy | F1(weighted) | Precision(weighted) | R(weighted) | F1(macro) | Precision | R | loss
| --- | --- | --- | --- | --- | --- |  --- |   --- | 
| 0.706667 | 0.701544 | 0.699640 | 0.706667 | 0.582701 | 0.543621 | 0.579661 | 0.0052116 | 

<img src="https://github.com/user-attachments/assets/c6a7e330-d5e6-4026-8f0f-9df5fb750475" alt="description" style="width: 50%; height: auto;">

## 实验： baseline_BILSTM(hidden_size=128)-attention_MVSA-single  
实验参数:
<img src="https://github.com/user-attachments/assets/8f0d11ce-8535-4aac-8f67-af76887016f5](https://github.com/user-attachments/assets/4f605640-5201-4bbf-b287-1c14a97b469a" alt="description" style="width: 50%; height: auto;">

| Accuracy | F1(weighted) | Precision(weighted) | R(weighted) | F1(macro) | Precision | R | loss
| --- | --- | --- | --- | --- | --- |  --- |   --- | 
| 0.697778 | 0.696265 | 0.695608 | 0.697778 | 0.583504 | 0.585869 | 0.582707 | 0.005372 | 
<img src="https://github.com/user-attachments/assets/9bcb60a5-24e4-48ea-b3aa-f985615e17bb" alt="description" style="width: 50%; height: auto;">

## 实验： baseline_BILSTM(hidden_size=256)-attention_MVSA-single  
实验参数:  
<img src="https://github.com/user-attachments/assets/4a207979-f73d-4daf-a88b-77ffa6099faf" alt="description" style="width: 50%; height: auto;">

| Accuracy | F1(weighted) | Precision(weighted) | R(weighted) | F1(macro) | Precision | R | loss
| --- | --- | --- | --- | --- | --- |  --- |   --- | 
| 0.706667 | 0.707631 | 0.708773 | 0.706667 | 0.620471 | 0.618341 | 0.622773 | 0.004950 | 
<img src="https://github.com/user-attachments/assets/34782309-cecb-415f-82de-d4d04cdb7267" alt="description" style="width: 50%; height: auto;">

## 实验： baseline_BILSTM(128)-CNN-attention_MVSA-single  
实验参数:
<img src="https://github.com/user-attachments/assets/a1bf705f-4869-4a37-8c3c-f50ce7af4b33" alt="description" style="width: 50%; height: auto;">

| Accuracy | F1(weighted) | Precision(weighted) | R(weighted) | F1(macro) | Precision | R | loss
| --- | --- | --- | --- | --- | --- |  --- |   --- | 
| 0.697778 | 0.702889 | 0.709073 | 0.697778 | 0.592002 | 0.587000 | 0.599027 | 0.007094 | 
<img src="https://github.com/user-attachments/assets/34ddbcd8-7d93-456c-9db8-5718a88ddb49" alt="description" style="width: 50%; height: auto;">

## 实验： baseline_BILSTM(256)-CNN-attention_MVSA-single  
实验参数：  
<img src="https://github.com/user-attachments/assets/ef795694-2586-4a2d-906f-7a3d1b69a3ca" alt="description" style="width: 50%; height: auto;">

| Accuracy | F1(weighted) | Precision(weighted) | R(weighted) | F1(macro) | Precision | R | loss
| --- | --- | --- | --- | --- | --- |  --- |   --- | 
| 671111 | 0.665007 | 0.661719 | 0.671111 | 0.552110 | 0.567145 | R: 0.545057 | 0.005250 | 

<img src="https://github.com/user-attachments/assets/1b6fbbdc-19f8-4168-a537-0c6d6b19f4d8" alt="description" style="width: 50%; height: auto;">

## 实验： baseline_BILSTM(256)-CNN-attention_MVSA-single  （创新点一架构）
实验参数： 
<img src="https://github.com/user-attachments/assets/82475d00-9de7-4177-9101-33c63ef14d9d" alt="description" style="width: 50%; height: auto;">

| Accuracy | F1(weighted) | Precision(weighted) | R(weighted) | F1(macro) | Precision | R | loss
| --- | --- | --- | --- | --- | --- |  --- |   --- | 
| 0.715556 | 0.726688 | 0.728780 | 0.737778 | 0.620189 | 0.67750 | R: 0.601697 | 0.004801 | 

## 实验： baseline_BILSTM(256)-capsule-attention_MVSA-single  （创新点一架构）
实验参数： 
<img src="https://github.com/user-attachments/assets/1375938a-e4c6-4885-a7b8-d7656f076681" alt="description" style="width: 50%; height: auto;">

| Accuracy | F1(weighted) | Precision(weighted) | R(weighted) | F1(macro) | Precision | R | loss
| --- | --- | --- | --- | --- | --- |  --- |   --- | 
| 0.688889 | 0.694417 | 0.701416 | 0.688889 | 0.592007 | 0.586963 | R: 0.600847 | 0.009700 | 

<img src="https://github.com/user-attachments/assets/c2055cd4-c52e-4c55-9ddd-dfa9b0a9f442" alt="description" style="width: 50%; height: auto;">

## 实验： Robert_（BILSTM(256)-multi_Att)+capsule0.4_MVSA-single  （创新点一架构）
实验参数：
<img src="https://github.com/user-attachments/assets/bea4be04-ba40-4783-b8e0-d9c3667979e4" alt="description" style="width: 50%; height: auto;">

| Accuracy | F1(weighted) | Precision(weighted) | R(weighted) | F1(macro) | Precision | R | loss
| --- | --- | --- | --- | --- | --- |  --- |   --- | 
| 0.711111 | 0.708502 | 0.711800 | 0.711111 | 0.595357 | 0.605117 | 0.591785 | 0.004960 | 

<img src="https://github.com/user-attachments/assets/ba76fa37-fe7f-400d-ad99-f0aa0a0ca5eb" alt="description" style="width: 50%; height: auto;">

## 实验： baseline_BILSTM(128)-CNN-attention_MVSA-multiple
实验参数： 
<img src="https://github.com/user-attachments/assets/a1bf705f-4869-4a37-8c3c-f50ce7af4b33" alt="description" style="width: 50%; height: auto;">

| Accuracy | F1(weighted) | Precision(weighted) | R(weighted) | F1(macro) | Precision | R | loss
| --- | --- | --- | --- | --- | --- |  --- |   --- | 
| 0.687059 | 0.673633 | 0.666722 | 0.687059 | 0.545090 | 0.554448 | 0.542327 | 0.003695 | 
<img src="https://github.com/user-attachments/assets/e93c42c9-d066-4aee-8ec7-64b8e3eefa54" alt="description" style="width: 50%; height: auto;">
