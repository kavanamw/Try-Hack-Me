leaq source, destination: this instruction sets destination to the address denoted by the expression in source
addq source, destination: destination = destination + source
subq source, destination: destination = destination - source
imulq source, destination: destination = destination * source
salq source, destination: destination = destination << source where << is the left bit shifting operator
sarq source, destination: destination = destination >> source where >> is the right bit shifting operator
xorq source, destination: destination = destination XOR source
andq source, destination: destination = destination & source
orq source, destination: destination = destination | source

Cheat Sheet:![[r2_cs.pdf]]

What is the value of **local\_ch** when its corresponding movl instruction is called (first if multiple)?
```
1
```
What is the value of **eax** when the imull instruction is called?  
```
6
```
What is the value of **local\_4h** before **eax** is set to 0?
```
6
```