java8 新增，
处理空指针异常（NPE）

一般来说，不宜返回null，应返回空数组`new T[0]`或者空字符串 `""`

如果一定要使用空来进行判断，使用 `return Optional.empty()`
调用方使用Optional.isPersent()判断

