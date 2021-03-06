# Keyboard-File-Types
This file attempts to list various kinds of keyboard layout files, and specifications.

_*Note*_: To add to this file, fork, edit, and send a pull request. 

##Formats
###As a text file
The included text file is included so that it can be refeenced by applications using BASH. If someone wants to make it a JSON array, fork, and send a pull requests. Otherwise, ordering has been thoughtless. Formating has been `<File extension>` `tab` `#` `Brief comment.` `tab` `See:` `space` `relevant URL`.


###As a table

File Extension | Brief Comment | Relevant URL
---|---|---
 .keylayout| OSX XML file for keyboard definition.|See: https://developer.apple.com/library/mac/technotes/tn2056/_index.html
 .bundle| OSX set of files containing various parts of the keyboard information including Language Metadata.|See: https://developer.apple.com/library/mac/documentation/CoreFoundation/Conceptual/CFBundles/BundleTypes/BundleTypes.html#//apple_ref/doc/uid/10000123i-CH101-SW13
 .kmn| Raw Keyman file|See: http://help.keyman.com/developer/7.0/filetype_kmn.php
 .kmx| Compiled Keyman file|See: http://help.keyman.com/developer/7.0/filetype_kmn.php
 .kxx| Compiled Keyman file|See: http://help.keyman.com/developer/7.0/filetype_kmn.php
 .xkb| Linux keyboard file|See: https://wiki.archlinux.org/index.php/X_KeyBoard_extension ; http://www.x.org/wiki/XKB/
 .klc| Raw keyboard layout file for MSKLC; Consider MSKLC|See: https://msdn.microsoft.com/en-us/goglobal/bb964665.aspx
 .msi| Compiled installer for keyboard layout file for MSKLC.|See: http://www.languagegeek.com/keyboard_general/msklc_installation.html
 .ahk| AutoHotKey script file.|See: http://www.autohotkey.com/docs/Scripts.htm
 .kcm| Native Keyboard Layout Files for Android.|See: https://source.android.com/devices/input/key-character-map-files.html
 .kl| A the keyboard layout format for kAndroid.|See: http://www.kandroid.org/online-pdk/guide/keymaps_keyboard_input.html
 .apk|  A packaged version of AnySoftKeyboard for Android.|See: https://github.com/AnySoftKeyboard/AnySoftKeyboard
 .json| This is technically a data format. Several JavaScript keyboard applications have use some sort of data serialization. This is used by JACKeyboards.|See: https://github.com/JaredCrawford/KeyboardLayouts
 .xml| CLDR data uses an XML Markup format.|See: http://cldr.unicode.org/index/charts/keyboards ; http://www.unicode.org/reports/tr35/tr35-keyboards.htmlContents

###List of file types

* .keylayout	# OSX XML file for keyboard definition.	See: https://developer.apple.com/library/mac/technotes/tn2056/_index.html
* .bundle	# OSX set of files containing various parts of the keyboard information including Language Metadata.	https://developer.apple.com/library/mac/documentation/CoreFoundation/Conceptual/CFBundles/BundleTypes/BundleTypes.html#//apple_ref/doc/uid/10000123i-CH101-SW13
* .kmn	# Raw Keyman file	See: http://help.keyman.com/developer/7.0/filetype_kmn.php
* .kmx	# Compiled Keyman file	See: http://help.keyman.com/developer/7.0/filetype_kmn.php
* .kxx	# Compiled Keyman file	See: http://help.keyman.com/developer/7.0/filetype_kmn.php
* .xkb	# Linux keyboard file	See: https://wiki.archlinux.org/index.php/X_KeyBoard_extension ; http://www.x.org/wiki/XKB/
* .klc	# Raw keyboardlayout file for MSKLC; Consider MSKLC	See: https://msdn.microsoft.com/en-us/goglobal/bb964665.aspx
* .msi	# Compiled installer for keyboard layout file for MSKLC.	See: http://www.languagegeek.com/keyboard_general/msklc_installation.html
* .ahk	# AutoHotKey script file.	See: http://www.autohotkey.com/docs/Scripts.htm
* .kcm	# Native Keyboard Layout Files for Android.	See: https://source.android.com/devices/input/key-character-map-files.html
* .kl	# A the keyboard layout format for kAndroid.	See: http://www.kandroid.org/online-pdk/guide/keymaps_keyboard_input.html
* .apk	#  A packaged version of anysoftkeyboard for Android.	See: https://github.com/AnySoftKeyboard/AnySoftKeyboard
* .json	# This is technically a data format. Several JavaScript keyboard applications have use some sort of data serialization. This is used by JACKeyboards.	See: https://github.com/JaredCrawford/KeyboardLayouts
* .xml	# CLDR data uses an XML Markup format.	See: http://cldr.unicode.org/index/charts/keyboards ; http://www.unicode.org/reports/tr35/tr35-keyboards.html#Contents