# tensor_view
我制作了一个用来可视化 h * w 的tensor的python第三方库

# 安装方法
在/tensor_view-0.0.1目录下启动cmd，激活python环境
/code conda activate your_python_envs
激活成功后输入安装代码完成安装
/code python setup.py install

# 使用方法
在python编辑器下输入调用代码
/code from tensor_view.tensor_view import heat_view
而后通过函数方法传入二维tensor即可实现热力图可视化
/code heat_view(torch.tensor)

# 备注
目前只有heat_view函数，只能实现热力图可视化，灰度图可视化作者懒得加入
