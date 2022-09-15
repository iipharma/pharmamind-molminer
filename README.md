# PharmaMind-MolMiner
PharmaMind®-MolMiner is a rule-free OCSR (Optical Chemical Structure Recognition) learning system. It aims to transform the vectorization problem into object detection tasks. That means it is able to extract chemical elements in an object detection manner by training well-labelled datasets with atom and bond annotations. It is implemented based on advanced deep learning technologies including [MobileNetv2](https://ieeexplore.ieee.org/document/8578572), [YOLOv5](https://github.com/ultralytics/yolov5), [EasyOCR](https://github.com/JaidedAI/EasyOCR). More details see [JCIM paper](https://doi.org/10.1021/acs.jcim.2c00733).

# Abstract
Molecular structures are commonly depicted in 2D printed forms in scientific documents such as journal papers and patents. However, these 2D depictions are not machine-readable. Due to a backlog of decades and an increasing amount of printed literatures, there is a high demand for translating printed depictions into machine-readable formats. Most OCSR systems developed over the last three decades use rule-based approach which vectorizing the depiction based on the interpretation of vectors and nodes as bonds and atoms. Here, we present a practical software called MolMiner, which is primarily built using deep neural networks originally developed for semantic segmentation and object detection to recognize atom and bond elements from documents. These recognized elements can be easily connected as a molecular graph with a distance-based construction algorithm. MolMiner gave state-of-the-art performance on four benchmark datasets and a self-collected external dataset from scientific papers. As MolMiner performed similarly well in real-world OCSR tasks with a user-friendly interface, it is an useful and valuable tool for daily applications. The free download links of Mac and Windows versions are available at: [Releases](https://github.com/iipharma/pharmamind-molminer/releases)

# User Manual

- [PharmaMind-MolMiner User Guide](./docs/en-US/PharmaMind%20User%20Guide.pdf) in English.

- [PharmaMind-MolMiner User Guide](./docs/zh-CN/PharmaMind%20User%20Guide.pdf) in Chinese.

# Release logs

- [PharmaMind-MolMiner Releases](https://github.com/iipharma/pharmamind-molminer/releases)
- [MAC CDN download](https://molminer-cdn.iipharma.cn/pharma-mind/artifact/latest/mac/PharmaMind-mac-latest-setup.dmg)
- [Win CDN download](https://molminer-cdn.iipharma.cn/pharma-mind/artifact/latest/win/PharmaMind-win-latest-setup.exe)
