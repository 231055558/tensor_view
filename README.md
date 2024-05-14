```markdown
# tensor_view

我制作了一个用来可视化 h * w 的tensor的python第三方库

## 安装方法

在/tensor_view-0.0.1目录下启动cmd，激活python环境

```bash
conda activate your_python_envs
```

激活成功后输入安装代码完成安装

```bash
python setup.py install
```

## 使用方法

在python编辑器下输入调用代码

```python
from tensor_view.tensor_view import heat_view
```

而后通过函数方法传入二维tensor即可实现热力图可视化

```python
import torch

# 创建一个示例tensor
example_tensor = torch.tensor([[1.0, 2.0], [3.0, 4.0]])

# 调用heat_view函数
heat_view(example_tensor)
```

## 备注

目前只有`heat_view`函数，只能实现热力图可视化，灰度图可视化作者懒得加入。
```

保存这个内容到你的README文件中即可。这样，用户在阅读你的README时，会看到清晰的代码块，方便他们按照步骤进行安装和使用。
