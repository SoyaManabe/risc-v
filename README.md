# risc-v
## Discription
このリポジトリではrisc-vの勉強に用いた題材のコードを残しております。

## Books
### Friends RISC-V
BOOTHにて購入。risc-v版のパタヘネ本に登場する単一サイクルのRISC-VサブセットをVerilogによって実装することを目的としている。
実際にIcarus Verilogシミュレータを用いて実装からテストまで体験することができる。また、フレンズの会話調で物語が進行していくので、フレンズのみんなならスッとRISC-Vの知識が脳に入り込んでくるだろう。
[Link](https://booth.pm/ja/items/1331900)

## Environment
* macOS Catalina
* Icarus Verilog(Verilogのシミュレータ)
* GTKWave(シミュレーション波形表示ソフト)

## Installation
```
# Install GTKWave
$ brew install caskroom/cask/gtkwave

# Install Icarus Verilog
$ sudo xcodebuild -license accept
$ brew install icarus-verilog

# Confirm installation
$ iverilog
iverilog: no source files.

Usage: iverilog [-ESvV] [-B base] [-c cmdfile|-f cmdfile]
                [-g1995|-g2001|-g2005|-g2005-sv|-g2009|-g2012] [-g<feature>]
                [-D macro[=defn]] [-I includedir]
                [-M [mode=]depfile] [-m module]
                [-N file] [-o filename] [-p flag=value]
                [-s topmodule] [-t target] [-T min|typ|max]
                [-W class] [-y dir] [-Y suf] source_file(s)

See the man page for details.
```

## Notification
けもフレはいいぞぉ
