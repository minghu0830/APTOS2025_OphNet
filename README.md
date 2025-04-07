# APTOS 2025 Big Data Competition - Phase Recognition of Surgical Videos Using ML

### Introduction
In the OphNet phase recognition task, your goal is to develop a machine learning model capable of automatically identifying and analyzing different surgical phases in ophthalmic surgery videos. You will use the cataract surgery subset of the OphNet dataset, which contains 496 cataract surgery videos with detailed annotations for 35 surgical phases. The model needs to accurately recognize various phases of the surgical workflow, providing an effective tool for surgical workflow analysis, surgical skill assessment, and surgical training. 

### Download
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

### Baseline
coming soon...
