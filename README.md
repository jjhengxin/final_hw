# final_hw
YOLOv8-pose在羽毛球运动中的应用（）

## 应用一 姿势识别
auto_cut_video.ipynb中第一个代码段实现

## 应用二 自动剪辑动作集锦
代码：auto_cut_video.ipynb
结果：output_clips/

## 应用三 战术分析
自制的数据集：badminton_pose-1/test/
                             /train/
                             /valid/
训练模型代码：badminton_pose-1/runs_in_colab/train_new_model.ipynb（在colab上运行的）
epoch分别取10和100进行了训练
训练结果：badminton_pose-1/runs_in_colab/runs/pose/predict*
