# APTOS 2025 Big Data Competition - Phase Recognition of Surgical Videos Using ML
[Tianchi](https://tianchi.aliyun.com/competition/entrance/532335?spm=a2c22.29524702.0.0.7e92539d9cM33o) | [HuggingFace](https://huggingface.co/datasets/xioamiyh/APTOS2025_OphNet-Cat) | [OneDrive](https://asiateleophth-my.sharepoint.com/:f:/g/personal/secretariat_asiateleophth_org/EosodiUKJjJDgVnDlbKlu2UB0Lkh1gMOkQPeulvF7DlOxA?e=AILLxk) 

## Introduction
In the APTOS2025 phase recognition competition, your goal is to develop a machine learning model capable of automatically identifying and analyzing different surgical phases in ophthalmic surgery videos. You will use the cataract surgery subset of the OphNet dataset, which contains 496 cataract surgery videos with detailed annotations for 35 surgical phases. The model needs to accurately recognize various phases of the surgical workflow, providing an effective tool for surgical workflow analysis, surgical skill assessment, and surgical training. 

## Download
*  **OneDrive** [Link](https://asiateleophth-my.sharepoint.com/:f:/g/personal/secretariat_asiateleophth_org/EosodiUKJjJDgVnDlbKlu2UB0Lkh1gMOkQPeulvF7DlOxA?e=AILLxk) 

*  **HuggingFace** 
    ```python
    export HF_ENDPOINT=https://hf-mirror.com  (optional, if you are in mainland China)
    ```
    ```python
    huggingface-cli download --repo-type dataset --resume-download xioamiyh/OphNet2024 --revision main --local-dir ./
    ```

*  **Merge and Extract the Archive**:
    ```python
    cat aptos_ophnet.tar.gz.* | tar xzvf -
    ```

## Baseline
coming soon...


## Citation
```python
@article{hu2024ophnet,
  title={OphNet: A Large-Scale Video Benchmark for Ophthalmic Surgical Workflow Understanding},
  author={Hu, Ming and Xia, Peng and Wang, Lin and Yan, Siyuan and Tang, Feilong and Xu, Zhongxing and Luo, Yimin and Song, Kaimin and Leitner, Jurgen and Cheng, Xuelian and others},
  journal={arXiv preprint arXiv:2406.07471},
  year={2024}
}
```
