Finetuned ColBert's variants

* ColBert-pwc: Finetunning with Pairwise Cross-Entropy Loss. (aka. Original ColBert)
    - ColBertV2: Download the finetunned checkpoints from ColBertV2.0
    ```
    mkdir checkpoints
    wget https://downloads.cs.stanford.edu/nlp/data/colbert/colbertv2/colbertv2.0.tar.gz
    tar -xvzf colbertv2.0.tar.gz
    rm colbertv2.0.tar.gz
    ```
* ColBert-ibn: Finetunning with In-batch Negative Loss
* ColBert-tct: Finetunning with In-batch Negative Loss and KL divergence and Knowledge distilation (aka TctColBert)
