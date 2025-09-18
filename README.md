# Systemless-Debloater
不要なシステムアプリを無効化します。
# 謝辞
[Systemless Debloater](https://github.com/zgfg/SystemlessDebloater)

[Systemless_DeGoogler](https://github.com/Systemless-DeBloaters/Systemless_DeGoogler)

[termux-aapt](https://github.com/rendiix/termux-aapt)

[JamesDSP (Cross-platform Audio Effect / Digital Signal Processing library)](https://github.com/james34602/JamesDSPManager)

[Anti bootloop](https://github.com/Magisk-Modules-Alt-Repo/abootloop/tree/v1.3.4)

[System App Nuker](https://github.com/chisewaguri/systemapp_nuker)

[Tricky Addon - Update Target List](https://github.com/KOWX712/Tricky-Addon-Update-Target-List)

上記から発想を得ました。
すべては上記のプロジェクトに関わった人たちに感謝申し上げます。

# 仕組み
テキストにapkパスが書き込まれ、そのapkパスのアプリをmount --bind "$DummyApk" "$ApkPath"として置き換えて無効化します。

# ⚠️必要不可欠なアプリを無効化してしまったら
**ブートループに陥ったときは、ボリュームアップキーとボリュームダウンキー、電源ボタンを同時に押してください。
すべてのモジュールが無効化されます。**
