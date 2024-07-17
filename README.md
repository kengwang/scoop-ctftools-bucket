# Scoop ctftools Docker

Easily install ctftools tools with Scoop.

[![Tests](https://github.com/kengwang/scoop-ctftools-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/kengwang/scoop-ctftools-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/kengwang/scoop-ctftools-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/kengwang/scoop-ctftools-bucket/actions/workflows/excavator.yml)


## Install

```powershell
scoop bucket add ctftools https://github.com/kengwang/scoop-ctftools-bucket.git
```

## Note

### 寄生包

有些软件自己包含在了特定包管理器中 (特别是 `pip`), 在考虑之下, 本 Bucket 准备采用寄生包的思想, 在安装的时候调用相关包管理器进行升级. 但是最终仍然由原包管理器进行管理.

## Supported Softwares

See [bucket](https://github.com/kengwang/scoop-ctftools-bucket/tree/main/bucket) directory for the list of supported softwares.
