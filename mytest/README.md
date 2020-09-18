
## 学习参考
- [ZMQ中文指南](https://github.com/anjuke/zguide-cn)
- [ZMQ通信模式:REQ-REP模式](https://www.jianshu.com/p/50bb18c1ab4f)

## ZMQ 安装
- 生成配置文件
  ```shell
    ./autogen.sh
  ```
- 进行配置
  ```shell
    ./configure --prefix=/usr/local/zmq
  ```
- 编译安装
  ```shell
    make
    make install
  ```

## ZMQ 通信模式
- [REQ-REP模式](REQ-REP模式.md)

## ZMQ 使用事项(关于 C++)
- [ZMQ使用事项](ZMQ使用事项.md)

## 测试语言
- C++

## 测试目录说明
- 1-first: REQ-REP 模式
- 2-second: 进阶
- 3-third: 高级请求-应答模式
- 4-forth: 可靠的请求-应答模式
- 5-fifth: 高级发布-订阅模式



