# jwtools
集微工具箱，包括各种常用操作，后续不断完善

### 使用
from jwtools.func import *

mm5 = get_text_md5("dddd")
print(mm5)

# write_text_to_file
result = write_text_to_file("D:/test/test123.txt", mm5)
print(result)

# read_text_from_file
cc = read_text_from_file("D:/test/test123.txt")
print(cc)