# UnMozLz4
## ���
```
���ڽ�ѹ��������(Mozilla Firefox)����ǩ�ļ�(*.jsonlz4), Ϊ�˷������, �ҽ���ѹ������װΪ��.
```

## �÷�
```
from UnMozLz4 import UnMozLz4
mozLz4Bin = file('bookmarks-2018-03-25_7.jsonlz4', 'rb').read()
print UnMozLz4(mozLz4Bin).unc()
```
