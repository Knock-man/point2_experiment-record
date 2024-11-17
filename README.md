# point2_experiment-record
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

## 实验： baseline_BILSTM-CNN-attention_MVSA-single  
实验参数：  
<img src="https://github.com/user-attachments/assets/a1bf705f-4869-4a37-8c3c-f50ce7af4b33" alt="description" style="width: 30%; height: auto;">

| Accuracy | F1(weighted) | Precision(weighted) | R(weighted) | F1(macro) | Precision | R | loss
| --- | --- | --- | --- | --- | --- |  --- |   --- | 
| 0.697778 | 0.702889 | 0.709073 | 0.697778 | 0.592002 | 0.587000 | 0.599027 | 0.007094 | 
<img src="https://github.com/user-attachments/assets/34ddbcd8-7d93-456c-9db8-5718a88ddb49" alt="description" style="width: 50%; height: auto;">

## 实验： baseline_BILSTM-attention_MVSA-single  
实验参数： 
<img src="https://github.com/user-attachments/assets/8f0d11ce-8535-4aac-8f67-af76887016f5" alt="description" style="width: 30%; height: auto;">

| Accuracy | F1(weighted) | Precision(weighted) | R(weighted) | F1(macro) | Precision | R | loss
| --- | --- | --- | --- | --- | --- |  --- |   --- | 
| 0.697778 | 0.696265 | 0.695608 | 0.697778 | 0.583504 | 0.585869 | 0.582707 | 0.005372 | 
<img src="https://github.com/user-attachments/assets/9bcb60a5-24e4-48ea-b3aa-f985615e17bb" alt="description" style="width: 50%; height: auto;">

## 实验： baseline_BILSTM-CNN-attention_MVSA-multiple   
实验参数：  
<img src="https://github.com/user-attachments/assets/a1bf705f-4869-4a37-8c3c-f50ce7af4b33" alt="description" style="width: 30%; height: auto;">

| Accuracy | F1(weighted) | Precision(weighted) | R(weighted) | F1(macro) | Precision | R | loss
| --- | --- | --- | --- | --- | --- |  --- |   --- | 
| 0.687059 | 0.673633 | 0.666722 | 0.687059 | 0.545090 | 0.554448 | 0.542327 | 0.003695 | 
<img src="https://github.com/user-attachments/assets/e93c42c9-d066-4aee-8ec7-64b8e3eefa54" alt="description" style="width: 50%; height: auto;">

