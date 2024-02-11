# 你好，请看这里 👋
## 自我介绍
你可以叫我xingchen8800。我爱玩《我的世界》。我 __比较__ 擅长使用C++进行编程。
> 非淡泊无以明志，非宁静无以致远。----诸葛亮《诫子书》

> 学而不思则罔，思而不学则殆。----《论语》

### 我的代码风格

```cpp
#include <iostream> 
using namespace std;

namespace name{
    class Hello;
}

int main() {
    Hello h;
    h();
    return 0;
}

namespace name {
    class Hello {
    public:
        Hello();
        ~Hello();

        void operator()() {
            cout << "Hello, World!\n";
        }
    };
}
```
