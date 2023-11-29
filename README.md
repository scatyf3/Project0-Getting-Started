Project 0 Getting Started
====================

**University of Pennsylvania, CIS 565: GPU Programming and Architecture, Project 0**

* @scatyf3
  * 只是为了好玩，不保证任何进度和信度
* Tested on:  Windows 10, i5-13400 @2.50GHz 32GB, RTX 4070 12GB 
# readme

## 配置cmake

和他的方法不太一样，这是我之前问ai告诉我的一个土办法，但是既然可以构建了，大约成功了（？）

```powershell
PS C:\Users\scat\Documents\GitHub\Project0-Getting-Started\build> cmake C:\Users\scat\Documents\GitHub\Project0-Getting-Started\cuda-getting-started
CMake Deprecation Warning at CMakeLists.txt:1 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.


-- Selecting Windows SDK version 10.0.22621.0 to target Windows 10.0.19045.
CMake Warning (dev) at CMakeLists.txt:25 (find_package):
  Policy CMP0146 is not set: The FindCUDA module is removed.  Run "cmake
  --help-policy CMP0146" for policy details.  Use the cmake_policy command to
  set the policy and suppress this warning.

This warning is for project developers.  Use -Wno-dev to suppress it.

-- C:/Users/scat/Documents/GitHub/Project0-Getting-Started/cuda-getting-started/cmake/cuda_compute_capability.cpp
-- CUDA Compute Detection Output: 89
-- CUDA Compute Detection Return: 0
-- CUDA Compute Detection Worked
-- Number of Computes Detected = 1
-- Configuring done (1.7s)
-- Generating done (0.1s)
-- Build files have been written to: C:/Users/scat/Documents/GitHub/Project0-Getting-Started/buildPS C:\Users\scat\Documents\GitHub\Project0-Getting-Started\build> cmake C:\Users\scat\Documents\GitHub\Project0-Getting-Started\cuda-getting-started
CMake Deprecation Warning at CMakeLists.txt:1 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.


-- Selecting Windows SDK version 10.0.22621.0 to target Windows 10.0.19045.
CMake Warning (dev) at CMakeLists.txt:25 (find_package):
  Policy CMP0146 is not set: The FindCUDA module is removed.  Run "cmake
  --help-policy CMP0146" for policy details.  Use the cmake_policy command to
  set the policy and suppress this warning.

This warning is for project developers.  Use -Wno-dev to suppress it.

-- C:/Users/scat/Documents/GitHub/Project0-Getting-Started/cuda-getting-started/cmake/cuda_compute_capability.cpp
-- CUDA Compute Detection Output: 89
-- CUDA Compute Detection Return: 0
-- CUDA Compute Detection Worked
-- Number of Computes Detected = 1
-- Configuring done (1.7s)
-- Generating done (0.1s)
-- Build files have been written to: C:/Users/scat/Documents/GitHub/Project0-Getting-Started/build

```

## 修改姓名

```cpp
int main(int argc, char* argv[]) {
    // TODO: Change this line to use your name!
    m_yourName = "@scatyf3";

    if (init(argc, argv)) {
        mainLoop();
    }

    return 0;
}
```

## Nsight

完成，见image文件夹里的两个图片

