# OodDINO

[state-of-the-art on RoadAnomaly Benchmark](https://paperswithcode.com/sota/anomaly-detection-on-road-anomaly)

[state-of-the-art on SegmentMeIfYouCan Benchmark](https://segmentmeifyoucan.com/leaderboard)

## Datasets Preparation

Download validation set [data set ](https://drive.google.com/file/d/1IbD_zl5MecMCEj6ozGh40FE5u-MaxPLh/view?usp=sharing) It should look like this: 
```

${PROJECT_ROOT}
 -- val       
     -- road_anomaly
         ...
     -- segment_me
         ...
```
Download [train set](https://drive.google.com/file/d/1k25FpVP4pG3ER3eXsR-go_iprZMEdEae/view?usp=sharing).It should look like this: 
```
 -- train_dataset
     -- offline_dataset
         ...
     -- offline_dataset_score
         ...
     -- offline_dataset_score_view
         ...
     -- ood.json
```


