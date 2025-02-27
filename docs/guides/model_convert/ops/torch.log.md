## torch.log
### [torch.log](https://pytorch.org/docs/stable/generated/torch.log.html?highlight=log#torch.log)

```python
torch.log(input,
          *,
          out=None)
```

### [paddle.log](https://www.paddlepaddle.org.cn/documentation/docs/zh/api/paddle/log_cn.html#log)

```python
paddle.log(x,
           name=None)
```

其中 Pytorch 相比 Paddle 支持更多其他参数，具体如下：
### 参数差异
| PyTorch       | PaddlePaddle | 备注                                                   |
| ------------- | ------------ | ------------------------------------------------------ |
| input         | x            | 输入的 Tensor。                                      |
| out           | -            | 表示输出的 Tensor，PaddlePaddle 无此参数。               |

### 转写示例
#### out：指定输出
```python
# Pytorch 写法
torch.log([3, 5], out=y)

# Paddle 写法
y = paddle.log([3, 5])
```
