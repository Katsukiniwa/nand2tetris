# 01

## Nand関数

Nand関数はxとyが共に1の時のみ0になり、それ以外は1になる

|  |  |  |  |  |
|---|---|---|---|---|
|x  |0  |0  |1  |1  |
|y  |0  |1  |0  |1  |
|Nand  |1  |1  |1  |0  |
|  |  |  |  |  |

## And関数

|  |  |  |  |  |
|---|---|---|---|---|
|x  |0  |0  |1  |1  |
|y  |0  |1  |0  |1  |
|And  |0  |0  |0  |1  |
|  |  |  |  |  |

Nand関数の逆なのでxとyが共に1の時のみ1になり、それ以外は0になる

## DMux関数

|  |  |  |  |  |
|---|---|---|---|---|
|in  |0  |0  |1  |1  |
|sel  |0  |1  |0  |1  |
|DMux(a)  |0  |0  |1  |0  |
|  |  |  |  |  |

selを逆にすればAndと一緒になる

|  |  |  |  |  |
|---|---|---|---|---|
|in  |0  |0  |1  |1  |
|sel  |0  |1  |0  |1  |
|DMux(b)  |0  |0  |0  |1  |
|  |  |  |  |  |

Andと同じ

[ひとりNand2Tetris(1) -NANDから他のゲートを作る](http://blog.tojiru.net/article/426426278.html)
