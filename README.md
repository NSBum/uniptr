# uniptr

Unicode and UTF-8 printer
Print Unicode code points and UTF-8 sequences in text

Dependencies:
   ucpt - see https://github.com/NSBum/ucpt

Usage examples:

- `echo "私の犬にはノミがいます。" | uniptr`
- `uniptr "Это моя собака."`

```shell
echo "кошка" | ./uniptr                                                                    1 ↵
char   	| Unicode   	| UTF-8
--------|---------------|----------
к     	| U+043A    	| d0 ba
о     	| U+043E    	| d0 be
ш     	| U+0448    	| d1 88
к     	| U+043A    	| d0 ba
а     	| U+0430    	| d0 b0
```
