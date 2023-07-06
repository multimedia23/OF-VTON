# OF-VTON
The code of Recurrent Appearance Flow for Occlusion-Free Virtual Try-On will be released soon.

## Experiments

### The visual comparison of different models on the virtual try-on task
![The visual comparison of deformation results](asserts/results.png)

### Quantitative results of different models on the virtual try-on task

|Method | FID | SSIM | LPIPS|
|-------|-------|-------|-------|
|CP-VTON|  20.25|0.730|0.3134|
|CP-VTON+| 15.92|0.845|0.1891|
|ACGPN|  13.88| 0.859| 0.2045|
|PF-AFN| 11.12| 0.897| 0.1545
|Flow-Style|9.93| 0.901 |0.1428|
|OccluMix|9.64|0.893| 0.1589|
|DAFlow| 11.43|0.843|0.1585|
|Our Method|**9.32**|**0.908**|**0.1379**|




