# Episode 2
> Make diagrams with pseudo-code

- [mermaidJS](http://knsv.github.io/mermaid/live_editor/)
- example: how to make lemonade

```
graph TD

1(pour water to glass)
2(cut lemons)
3(squeeze lemons)
4(add sugar)
5(mix)
6(taste)
7{tastes good?}
8(sell it to your friends)

1-->2
2-->3
3-->4
4-->5
5-->6
6-->7
7-->|yes|8
7-->|no|4
```