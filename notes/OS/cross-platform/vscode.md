# Visual Studio Code Tips

## Release Note

Refer to [the official site]( https://code.visualstudio.com/updates ).

## Regex search and replace

You can use `(lib[a-z]*[0-9][0-9])` (note the parentheses here) to match `libavcodec56`, `libavcodec57`, `libavcodec58`, `libavformat56`, `libavformat57`, `libavformat58`, `libavdevice56`, `libavdevice57`, `libavdevice58` in the search field.

Wrap them with backtick `` ` `` using `` `$1` `` in the replace field.

References:

- [VS Code: Search-and-Replace Regex](https://dev.to/rfornal/vs-code-search-and-replace-regex-mn2)
- [🔎 vscode | regex find and replace](https://www.youtube.com/watch?v=xMhKstbdr3k)

## KWallet Related

See [[KWallet#KWallet and VSCode]]

[//begin]: # "Autogenerated link references for markdown compatibility"
[KWallet#KWallet and VSCode]: ../Linux/cross-distro/KWallet.md "KWallet"
[//end]: # "Autogenerated link references"
