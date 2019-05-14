# HeadDetect_MTCNN
CPU real-time head detection

# Test steps
## step1
Download opencv_dll and put it to current directory [BaiDu Cloud](https://pan.baidu.com/s/143Ia9lH9BXNiv-hSPSu4Bw)
## step2
Set parameters:
`HeadDetect.exe min_size test_type test_path`
```cpp
test_imgdir.cmd  (for imgdir)
test_usbcam.cmd  (for usbcam)
test_video.cmd  (for video)
```
# Algorithm efficiency
| Image Size | minsize | Speed | CPU |
|:------:|:------:|:------:|:------:|
| 1920x1080 | 50 | 48ms| i7-8750H @2.20GHz |
| 640x480 | 50 | 5ms| i7-8750H @2.20GHz |

# Deficiencies
1. Small dataset leads to missed detection.
2. Heads in hats can't be detected.
3. Welcome to provide good datasets to help improve the robustness of the algorithm.
4. Any questions can be contacted by the author.

# Reference
https://blog.csdn.net/samylee
