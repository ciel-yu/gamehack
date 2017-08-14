NieR: Automata
==============

Nier的主要数据存放在静态数据段.

- 所持金: NieRAutomata.exe+197C4C0
- 经验值: NieRAutomata.exe+1984670

Chip
----
len: 0x30

|  |+00|+04|+08|+0C|
|---:|---|---|---|---|
|0|sort order|id|type|rank|
|10|cost|pos A|pos B|pos C|
|20|0xFFFFFFF|0xFFFFFFF|0xFFFFFFF|0x00000000|

Item
----
len: 0xC

|  |+00|+04|+08|+0C|
|---:|---|---|---|---|
|0|id|00 00 07 00|amount|--|
