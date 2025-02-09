## [ 仅参数名不一致 ]torch.vsplit
api 存在重载情况，分别如下：

-------------------------------------------------------------------------------------------------
### [torch.vsplit](https://pytorch.org/docs/stable/generated/torch.vsplit.html#torch.vsplit)

```python
torch.vsplit(input,
        sections)
```

### [paddle.vsplit](https://www.paddlepaddle.org.cn/documentation/docs/zh/develop/api/paddle/vsplit_cn.html)

```python
paddle.vsplit(x,
        num_or_indices,
        name=None)
```

其中 Paddle 相比 PyTorch 仅参数名不一致，具体如下：

### 参数映射

| PyTorch       | PaddlePaddle | 备注                                                   |
| ------------- | ------------ | ------------------------------------------------------ |
| input          |  x           | 输入多维 Tensor ，仅参数名不一致。  |
| sections           | num_or_indices         | 表示分割的数量或索引，仅参数名不一致。                          |

-------------------------------------------------------------------------------------------------

### [torch.vsplit](https://pytorch.org/docs/stable/generated/torch.vsplit.html#torch.vsplit)

```python
torch.vsplit(input,
        indices)
```

### [paddle.vsplit](https://www.paddlepaddle.org.cn/documentation/docs/zh/develop/api/paddle/vsplit_cn.html)

```python
paddle.vsplit(x,
        num_or_indices,
        name=None)
```

其中 Paddle 相比 PyTorch 仅参数名不一致，具体如下：

### 参数映射

| PyTorch       | PaddlePaddle | 备注                                                   |
| ------------- | ------------ | ------------------------------------------------------ |
| input          |  x           | 输入多维 Tensor ，仅参数名不一致。  |
| indices           | num_or_indices         | 表示分割的数量或索引，仅参数名不一致。                          |
