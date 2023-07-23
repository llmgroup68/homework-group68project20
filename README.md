# homework-group68project20
Project20: ECMH PoC


实现方式：Python

成员：李丽敏-202100460130（仅一人一组）


实验概述：


ECMH是一种基于椭圆曲线的哈希函数，它与传统的哈希函数不同，使用了椭圆曲线上的点来进行哈希计算。


ECMH 的计算过程如下：

1：将要哈希的消息转换为整数或字节数组。


2：对消息进行哈希运算，得到哈希值。


3：将哈希值转换为椭圆曲线上的点。


具体过程如下：

将消息进行哈希运算，得到哈希值h。可以使用常见的哈希算法，如SHA-256。

![image](https://github.com/llmgroup68/homework-group68project20/assets/138642474/1e2004a1-a53e-4156-a2d0-e596f8a6a184)


将哈希值h转换为一个整数或字节数组。

![image](https://github.com/llmgroup68/homework-group68project20/assets/138642474/99d889e2-cc06-4605-8a62-1c630d7b76dd)



使用椭圆曲线上的点生成算法，将哈希值转换为椭圆曲线上的点P。其中，点的生成算法可以使用随机数和某些特定的函数来计算。

![image](https://github.com/llmgroup68/homework-group68project20/assets/138642474/4e4ae7ef-e419-441a-934a-4292b52f7f58)

得到椭圆曲线上的点P，作为最终的哈希结果。

实验结果如下：
我选取了765和087进行Hash

![image](https://github.com/llmgroup68/homework-group68project20/assets/138642474/16687219-8f11-4547-811b-4cafc06da141)


ECMH 提供了一种基于椭圆曲线的哈希函数，具有较高的安全性和强大的抗碰撞能力。它在密码学和安全通信中得到广泛应用，例如在数字签名、密钥交换和身份认证等领域。
