### ClothingMigration-NCNN
##### 工作内容
将CVPR2021的服装迁移模型[CT-Net](https://github.com/yf1019/CT-Net)搬运至[NCNN](https://github.com/Tencent/ncnn)框架上
##### CT-Net依赖
1. 依赖[OpenPose](https://github.com/Hzzone/pytorch-openpose)的人体姿势——pytorch实现
2. 依赖[LIP_JPPNet](https://github.com/Engineering-Course/LIP_JPPNet)的的人体解析分割图——Tensorflow实现
3. 依赖[Densepose](https://github.com/facebookresearch/detectron2/tree/main/projects/DensePose)的人体IUV图——[Detectron2](https://github.com/facebookresearch/detectron2)实现
##### 待完成工作
- [ ] OpenPose的ncnn&c++实现
- [ ] LIP_JPPNet的ncnn&c++实现
- [ ] Densepose的ncnn&c++实现
- [ ] CT-Net的ncnn&c++实现
- [ ] 组合四个模型的ncnn&c++实现
- [ ] QT GUI实现
- [ ] 撰写知乎文章
- [ ] 额外预处理—[人像抠图](https://github.com/FeiGeChuanShu/ncnn_Android_RobustVideoMatting)
- [ ] 额外后处理—[超分辨率](https://github.com/yhjo09/SR-LUT)