# Lite8 files specification (format)

## Game File: `*.lite.txt`
```
lite8 https://github.com/lite8
ver. 0.1

__script__
.pas

procedure _init()
begin

end;


__palette__
0|ff8800
a|aabbcc
f|0088ff

__sprite__
0123456789...128

__map__
0123456789...256
```


## Games Collection File: `collection.lite.txt`
```
lite8 https://github.com/lite8
ver. 0.1

__toc__
Sudoku v.1|Your Name|0123456789...128x128
Fulltris|Your Friend Name|0123456789...128x128
```

## Repositories File: `sites.lite.txt`
```
lite8 https://github.com/lite8
ver. 0.1

__site__
10001 Fulltris|https://example.com/1001-fulltris/collection.lite.txt
Sudoku Games | https://example.com/games/lite8/sudoku-collections
```