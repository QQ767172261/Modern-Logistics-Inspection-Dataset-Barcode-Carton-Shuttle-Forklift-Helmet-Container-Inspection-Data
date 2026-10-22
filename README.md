1现代物流数据集![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/84c60b37b2de4643973afa1ef09b8178.png)
# Logistics物流目标检测数据集（）信息总结
## 一、数据集规模
1. 图像总量：**99238张**，面向物流场景目标检测任务
2. 标注方式：部分数据通过Autodistill DETIC自动标注后人工复核，配套预训练模型mAP达76%
3. 场景覆盖：仓储、道路运输、厂区物流等综合物流场景（含限速道路标识样本）

![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/b2faa64f0c66407986ee078a0a6a9db9.png)
## 二、全部20类目标清单
1. barcode（条形码）
2. qr code（二维码）
3. cardboard box（纸箱）
4. wood pallet（木托盘）
5. freight container（货运集装箱）
6. forklift（叉车）
7. gloves（劳保手套）
8. helmet（安全帽）
9. safety vest（安全反光背心）
10. ladder（梯子）
11. license plate（车牌）
12. person（人员）
13. car（轿车）
14. truck（卡车）
15. van（厢式货车）
16. fire（明火）
17. smoke（烟雾）
18. road sign（道路标识）
19. traffic cone（交通锥）
20. traffic light（交通信号灯）
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/54a3fd60cf1a491199b8a6e582a9704c.png)

## 三、标注与导出格式
1. 原生平台支持导出主流目标检测格式，适配YOLOv8/n等模型训练：
   - YOLO TXT格式：单图对应同名txt标注文件，归一化边界框坐标，配套`data.yaml`类别配置文件
   - 同时支持COCO JSON、Pascal VOC XML等标准格式导出
2. 标注类型：2D矩形边界框目标检测标注
3. 数据集目录标准划分：自动分为train/valid/test三子集，每子集独立存放images图像文件夹、labels标注文件夹![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/bc3598ced2714620be04b9a77a40bc38.png)

1
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/e0bc424b977c451a9e827d069aceafd5.png)


