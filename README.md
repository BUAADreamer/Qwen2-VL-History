# Qwen2-VL-History

## 例子

<details><summary>博物馆 Qwen2-VL</summary>

![讲解博物馆](pics/1_origin.png)

</details>

<details><summary>博物馆 Qwen2-VL-History</summary>

![讲解博物馆](pics/1.png)

</details>

<details><summary>博物馆 Qwen2-VL</summary>

![讲解博物馆](pics/2_origin.png)

</details>

<details><summary>博物馆 Qwen2-VL-History</summary>

![讲解博物馆](pics/2.png)

</details>

<details><summary>博物馆 Qwen2-VL</summary>

![讲解博物馆](pics/3_origin.png)

</details>

<details><summary>博物馆 Qwen2-VL-History</summary>

![讲解博物馆](pics/3.png)

</details>


## 微调
```shell
FORCE_TORCHRUN=1 CUDA_VISIBLE_DEVICES=0,1,2,3,4,5,6,7 llamafactory-cli train configs/qwen2_vl_full_sft.yaml
```

## 推理

```shell
CUDA_VISIBLE_DEVICES=0 llamafactory-cli webchat configs/qwen2_vl_infer.yaml
```

## 