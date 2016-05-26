# any++

usage:
```cpp

std::string s1 = "foo";
Any a1 = s1;

Assert(a1.is<std::string>);

std::string s2 = a1;

auto s3 = a1.as<std::string>();

```
