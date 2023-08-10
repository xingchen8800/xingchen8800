# 你好，请看这里 👋
## 自我介绍
你可以叫我xingchen8800，我是学生。我的哔哩哔哩用户名是xing_chen_(在上面发一些视频)。我爱玩《我的世界》。我 __比较__ 擅长使用C++进行编程。
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
## 我的项目
| 项目名 | 简介 | 状态 | 开源 | github仓库 | README |
|-|-|-|-|-|-|
|xcUI| 一个 __任何设备(需要提供输入和输出的函数)__ 都可以使用的GUI库。 | 正在编写 |✅| xingchen8800/UI.git | Yes |
|iScreen| 一个是用于 __esp32__ 的Screen项目 | 正在编写 |❌| - | No |
