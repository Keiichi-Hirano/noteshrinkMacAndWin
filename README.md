noteshrinkMacAndWin
# Additional
1. Supports PDF file generation under Windows environment

# Example comments on additional features
  The logic is sandwiched between start and END.
## Append
  Start Comments → # Windows Append Start
  End Comments   → # Windows Append End

## Modify
  Start Comments → # Windows Modify Start
  End Comments   → # Windows Modify End

## Usage
```
./noteshrinkMacAndWin.py IMAGE1 [IMAGE2 ...]
```

# 手順
本パッケージをダウンロード、Install_Command_List.txtの記載に従い、必要なPythonライブラリをインストールを実施
各インストールが完了したら、コマンドラインよりUsage記載の通り、コマンドラインにて実行を行う。

# Original
noteshrink

Convert scans of handwritten notes to beautiful, compact PDFs -- see full writeup at <https://mzucker.github.io/2016/09/20/noteshrink.html>

## Requirements

 - Python 2 or 3
 - NumPy 1.10 or later
 - SciPy
 - ImageMagick
 - Image module from PIL or Pillow

## Usage

```
./noteshrink.py IMAGE1 [IMAGE2 ...]
```

Building the examples (already in `example_output`):

```
make
```

## Packages
Packages are available for:
 - [Arch Linux (AUR)](https://aur.archlinux.org/packages/noteshrink/)
 
## Derived works

*Note:* Projects listed here aren't necessarily tested or endorsed by me -- use with care!

  - [Web-based (Django) front-end](https://github.com/delneg/noteshrinker-django)
