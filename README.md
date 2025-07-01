# openpose


ref: https://github.com/CMU-Perceptual-Computing-Lab/openpose

### example

### 原图+姿态
```
./OpenPose-x86_64.AppImage \
  --model_folder  ./models  \
  --image_dir ./src_img \
  --write_images ./output_images/ \
  --write_json ./output_json/ \
  --display 0 \
  --net_resolution "656x368"
```
  
  
### 纯姿态图 --render_pose 1 
  ```
  ./OpenPose-x86_64.AppImage \
  --model_folder  ./models  \
  --image_dir ./src_img \
  --write_images ./output_images/ \
  --write_json ./output_json/ \
  --display 0 \
  --render_pose 1 \
  --disable_blending

```
