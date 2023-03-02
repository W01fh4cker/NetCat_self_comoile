# NetCat_self_comoile
# Compilation environment | 编译环境

`Microsoft Visual Studio 2019`

![image](https://user-images.githubusercontent.com/101872898/222322633-be2e6040-a6e7-4bb9-b789-fb1cf7e3e9ca.png)

# Need Attention | 需要注意的坑：

1. 这里需要加上这几行代码，并且选择`x86`：

![image](https://user-images.githubusercontent.com/101872898/222322828-d3b72106-34fe-4d8d-814e-4d7bd0671585.png)

2. 在项目——netcat 属性——C/C++——预处理器——预处理器定义这里修改成以下配置：

   ```text
   WIN32
   NDEBUG
   _CONSOLE
   _CRT_SECURE_NO_WARNINGS
   _CRT_NONSTDC_NO_DEPRECATE
   ```

![image](https://user-images.githubusercontent.com/101872898/222323181-4866472d-ef54-462b-85ab-d48a807c6c25.png)

![image](https://user-images.githubusercontent.com/101872898/222323434-0e17a354-3779-4650-b65c-49988c283db0.png)

# Q&A | 问题答复

直接在`issues`里面提出即可。
