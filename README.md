# OptcncRTControllerRelease

本目录用于存放 [`OptimalCNC/MasterSlave`]([https://your-repo-url](https://github.com/OptimalCNC/MasterSlave)) 项目中 **最新版本** 的 `MotionControlServices.h` 文件。

## 📌 文件用途

该头文件定义了上位机与TwinCAT之间通过 **ADS 通信** 所需的所有数据结构与类型。  
上位机必须依赖此文件，才能正确读取&传输数据。

## ⚠️ 使用说明

- 每当 `OptimalCNC/MasterSlave` 项目中更新此文件后，workflow会**及时更新**本仓库中的Release文件。
- **禁止在本目录中修改Release**。如需更改，请前往源项目中修改并重新同步。
