# sort文件内容排序去重

> 在文本处理中比较常见的一个场景便是排序去重文件内容，使用sort+uniq便是较为常见的排序去重方法，但是这个组合使用不当的话会直接把文件内容清空，以下为去重方法的使用演示。



```bash
sort $file -u -o $file
```