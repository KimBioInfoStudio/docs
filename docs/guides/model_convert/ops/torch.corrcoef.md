## torch.corrcoef
### [torch.corrcoef](https://pytorch.org/docs/stable/generated/torch.corrcoef.html?highlight=corrcoef#torch.corrcoef)

```python
torch.corrcoef(input)
```

### [paddle.linalg.corrcoef](https://www.paddlepaddle.org.cn/documentation/docs/zh/api/paddle/linalg/corrcoef_cn.html#corrcoef)

```python
paddle.linalg.corrcoef(x,
                       rowvar=True,
                       name=None)
```

两者功能一致且参数用法一致，仅参数名不同，具体如下：
### 参数差异
| PyTorch       | PaddlePaddle | 备注                                                   |
| ------------- | ------------ | ------------------------------------------------------ |
| input         | x            | 一个 N(N<=2)维矩阵，包含多个变量。默认矩阵的每行是一个观测变量，由参数 rowvar 设置。    |
| -             | rowvar       | 以行或列作为一个观测变量。    |
