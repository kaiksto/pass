pass
====

private password generator

This is password generator i use every day. It takes value of easy to remember master password and converts it to strong one
depending on site address written in second input. It's basically based on this password generator(http://public.hronopik.de/passwd2.html?lang=en)
but with edited character list to fit my needs and lengthen output password. The other thing I changed is to hide output password by moving
it above top of a screen, but keeping it selectable with "Tab key", and kept order master>site>output. To make it even more secure
there is no send/generate button, password is generated every time you focus its field, without reloading. I wanted also use advantages of
HashMask(http://lab.arc90.com/2009/07/09/hashmask-another-more-secure-experiment-in-password-masking), but
it was too hard for me to code sth similar, and not light enough as this site should be. Then I found
Chroma-Hash(http://mattt.github.com/Chroma-Hash/) and took their method and written it my way (no animations etc.).

usage:

1. type in first field master password
2. check if colors are the same as usual, this helps to avoid typo
3. use tab key to switch to second field and type domain name (or whatever you want to be influencing hash key)
4. use tab key to switch to third field which is not visible (it is moved above the screen)
5. ctrl+c
6. paste password where you need it