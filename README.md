# TLCFuse
We propose a novel approach for bird's eye view semantic grid segmentation, that leverages sequential sensor data to achieve robustness against occlusions. Our model extracts information from the sensor readings using attention operations and aggregates this information into a lower-dimensional latent representation, enabling thus the processing of multi-step inputs at each prediction step. Moreover, we show how it can also be directly applied to forecast the development of traffic scenes and be seamlessly integrated into a motion planner for trajectory planning. On the semantic segmentation tasks, we evaluate our model on the nuScenes dataset and show that it outperforms other baselines, with particularly large differences when evaluating on occluded and partially-occluded vehicles. Additionally, on motion planning task we are among the early teams to train and evaluate on nuPlan, a cutting-edge large-scale dataset for motion planning.

Architecture: 
![Architecture](imgs/TLCFuse_pipeline.png)

## Qualitative results:

### Predicting current time frame:
Sample A:
![Sample A](imgs/sample_a.png)

Sample B: 
![Sample B](imgs/sample_b.png)

sample C:
![Sample C](imgs/sample_c.png)

Sample D: 
![Sample D](imgs/sample_d.png)

Sample E:
![Sample E](imgs/sample_e.png)

### PLanning
[![Planning]](https://youtu.be/-tTrlZeFsvs)

### Predicting future frames:
![cams](imgs/cams_forecasting.gif) ![prediction](imgs/qualitative_forecasting.gif)

