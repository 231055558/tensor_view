# 一个用来可视化 h * w 的tensor的python第三方库
## 安装方法
```markdown
在/tensor_view-0.0.2目录下启动cmd，激活python环境
```
```bash
conda activate your_python_envs
```

## 激活成功后输入安装代码完成安装

```bash
python setup.py install
```

## 使用方法
在python编辑器下输入调用代码
```python
# 如果使用热力图
from tensor_view.heat_view import heat
# 如果使用灰度图
from tensor_view.gray_view import gray
```

## 而后通过函数方法传入二维tensor即可实现热力图可视化
```python
import torch

# 创建一个示例tensor
example_tensor = torch.tensor([[1.0, 2.0], [3.0, 4.0]])

# 调用heat_view函数
heat_view(example_tensor)
```


