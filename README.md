# Camera Distortion-aware 3D Human Pose Estimation in Video with Optimization-based Meta-Learning

**This is the official repository of "Camera Distortion-aware 3D Human Pose Estimation in Video with Optimization-based Meta-Learning", ICCV 2021.**

This is the implementation of the approach described in the paper:
> Hanbyel Cho, Yooshin Cho, Jaemyung Yu, and Junmo Kim. [Camera Distortion-aware 3D Human Pose Estimation in Video with Optimization-based Meta-Learning](https://arxiv.org/abs/2111.15056?context=cs). IEEE International Conference on Computer Vision (ICCV), 2021.

### Dependencies
Make sure you have the following dependencies installed before proceeding:
- Python 3+ distribution
- PyTorch >= 0.4.0

Optional:
- Matplotlib, if you want to visualize predictions. Additionally, you need *ffmpeg* to export MP4 videos, and *imagemagick* to export GIFs.
- MATLAB, if you want to experiment with HumanEva-I (you need this to convert the dataset).

## License
This work is licensed under CC BY-NC. See LICENSE for details. Third-party datasets are subject to their respective licenses.
If you use our code/models in your research, please cite our paper:
```
@InProceedings{Cho_2021_ICCV,
    author    = {Cho, Hanbyel and Cho, Yooshin and Yu, Jaemyung and Kim, Junmo},
    title     = {Camera Distortion-Aware 3D Human Pose Estimation in Video With Optimization-Based Meta-Learning},
    booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
    month     = {October},
    year      = {2021},
    pages     = {11169-11178}
}
```
