# python-test
# 1、变量和简单数据类型
## 1.1 修改字符串的方法：
- `title()`:首字母大写
- `upper()`,`lower()`
- `\t`: 制表符, `\n`:换行符
- `rstrip()`:去除末尾空格
- `lstrip()`:去除开头空格
- `strip()`:去除两端空格
 
## 1.2 列表
 
- `append()`:末尾添加元素
- `pop()`：弹出末尾元素，括号内可加序号
- `del list[0]`删除元素
- `remove()`:根据值删除元素
- `sort()`: 永久排序；`sorted()`: 临时排序
- `reverse()`: 反转列表
- `list(range(4))`:转换成列表
- 列表解析
- `a=b[:]`: 复制一个列表；`a=b`: 将a关联到b上
- 检查是否在列表中：`if user not in banned_users: `
 
## 1.3 字典
 
- 键-值对可动态添加
 
- `del dict[key]`:删除元素
 
- 多行定义字典：
 
- ```
  favorite_languages = {
      'jen': 'python',
      'sarah': 'c',
      'edward': 'ruby',
      'phil': 'python',
      }
  ```
 
- 遍历字典元素：`for key, value in user_0.items(): `