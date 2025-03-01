**YOLOv8 Object Detection with SE & ResCBAM**

This repository contains Jupyter Notebooks (.ipynb) for object detection using YOLOv8 models:

1) YOLOv8n: Baseline model.

2) YOLOv8n + SE Blocks: Enhances channel-wise feature recalibration.

3) YOLOv8n + ResCBAM: Improves feature representation with channel & spatial attention.

**Architecture**:

1) Backbone: Extracts multi-scale features.

2) Neck: Performs feature fusion.

3) Head: Generates predictions.

4) SE Blocks: Enhance channel-wise features.

5) ResCBAM: Refines channel & spatial attention.

**Installation**:

a) pip install <related tensorflow and pytorch libraries>
b) git clone <repo_link>
c) cd <repo_name>
d) jupyter notebook
e) Run .ipynb files in notebooks/.

**Results**:

Enhanced models aim for better accuracy. Metrics are in results/.

**Contributions**
Feel free to reach out on below email id in case of any discrepancy : yadav.49@iitj.ac.in, pmi2017003@iitj.ac.in
PRs & issues are welcome.


**PAPER-LINK**
https://ieeexplore.ieee.org/document/10900641
