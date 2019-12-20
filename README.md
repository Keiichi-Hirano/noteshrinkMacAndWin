noteshrinkMacAndWin
# Additional
1. Supports PDF file generation under Windows environment

# Example comments on additional features
  The logic is sandwiched between start and END.
## Append
Start Comments
```
 # For Windows Append Start
```
End Comments
```
# For Windows Append End
```

## Modify
Start Comments
```
# For Windows Modify Start
```
End Comments
```
# For Windows Modify End
```

## Usage
```
./noteshrinkMacAndWin.py IMAGE1 [IMAGE2 ...]
```

# 手順
本パッケージをダウンロード、Install_Command_List.mdの記載に従い、必要なPythonライブラリのインストールを実施
各ライブラリのインストールが完了したら、コマンドラインよりUsage記載の通り、コマンドラインにて実行を行う。

# 注意事項
機能の特徴として色調が明るくなる為、露出過多になる場合がある。
原本（変換前の画像）については、変換後の再確認を確実の実施ください。

# Original Source 
noteshrink at https://github.com/mzucker/noteshrink

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
