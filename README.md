# C++基础

## 开发环境
- 操作系统: Ubuntu 20.04
- C++编译工具: 
    - gcc/g++ 9.4.0
    - CMake 3.23+

## 基本要求

### 1. 熟悉git命令的使用

- [ ] 项目的拉取及提交
- [ ] 提交内容的书写规范

提交规范可参考[Angular.js develope document](https://github.com/angular/angular.js/blob/master/DEVELOPERS.md#commits)中的 `Git Commit Guidelines` 章节。

### 2. 熟悉基础的C++代码规范

可参考[Google C++ Guide](https://google.github.io/styleguide/cppguide.html)官方文档。

### 3. 熟悉cmake的使用

- [ ] 构筑一个简单的工程，完成 `example/task1` 目录中缺失的部分。

- [ ] 动/静态库的生成，完成 `example/task2` 目录中缺失的部分。
    - [ ] 动态库编译生成的命名为 `foo.so` 。
    - [ ] 静态库编译生成的命名为 `foo.a` 。
    - [ ] 简单总结动/静态库的作用。

- [ ] 构筑一个使用第三方库的工程，完成 `example/task3` 目录中缺失的部分。
    - [ ] 第三方库自行选择，存放路径为 `third_party` 目录。
    - [ ] 使用 `find_package` 加载第三方库。

- [ ] 构筑一个使用到多个子项目的工程，完成 `example/task4` 目录中缺失的部分。
    - [ ] 在 `main.cpp` 调用 `foo` 和 `bar` 项目中的函数或类，执行并输出结果。

可参考[CMake Reference Documentation](https://cmake.org/cmake/help/latest/)官方文档。

### 4. 熟悉googletest的使用

- [ ] 编写 `test/test_case_1.cpp` 中 `add` 函数的测试用例。
- [ ] 编写 `test/test_case_2.cpp` 中的测试用例，测试函数或类自拟。
    - [ ] 编写2个测试用例，要用到 `::testing::Test` 中的 `SetUp` 成员函数。

可参考[GoogleTest User`s Guide](https://google.github.io/googletest/)官方文档。

**请根据提供的示例自行编写CMakeLists.txt文件，所有编译请在build目录中完成。**

[![Security Status](https://s.murphysec.com/badge/hankknight/cxx_primary.svg)](https://www.murphysec.com/p/hankknight/cxx_primary)
