# brainfuck debugger

## how to use

``` sh
    $ bfdb code.bf
```

## meta instructions

instruction | behavior
----------- | ------------
`#`         | break point

## input

 key            | command  | description
--------------- | -------- | -------------
 q              | quit     | debuggerを終了
 s              | step     | 1命令だけ実行
 n              | next     | 1命令だけ実行する。`[]`は1命令とみなす
 u              | up       | 今いる`[]`で最も内側のものを抜けるまで実行
 c              | continue | ずっと実行
 the other keys | stop     | ずっと実行、を停止
