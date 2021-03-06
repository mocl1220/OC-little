# AOAC-PRW全局更名

## 描述

- 虽然采用了 `AOAC` 技术的机器和 `S3` 睡眠无关，但仍然需要 `0D6D` 补丁。否则，插拔电源、USB设备等会导致机器被唤醒，即使在盒盖情况下也会如此。有关 `0D6D` 补丁详见《060D补丁》。
- 因为 `AOAC` 机器的特殊性，采用 **PRW全局更名** 可实现 `0D6D` 补丁的相同效果，也不会影响其他部件。

## PRW全局更名

_PRW to XPRW：

```
Find        5F505257 
Replace     58505257 
```

## 注意事项

- 原理上讲， **PRW全局更名** 不会对其他系统造成影响。如有冲突请恢复使用《060D补丁》。

