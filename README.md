# Setp1-CLI-CLIBasics

CLI Basics Homework

## Problem 1

找到在 Ubuntu 系统中可以用于计算文件内容 MD5 值的命令

**Answer**

```bash
md5sum
```

## Problem 2

找到在 Ubuntu 系统中可以用于比较两个文件的内容的差异的命令

**Answer**

```bash
diff
```

## Problem 3

实现一个名为 odd-or-even 的 Bash function，可以用来判断给其提供的第一个参数是奇数还是偶数，奇数时输出 odd，偶数时输出 even

**Answer**

```bash
function odd-or-even(){
 NUMBER=$1
 if [ `expr $NUMBER % 2` == 0 ]
 then
        echo "EVEN"
 else
        echo "ODD"
 fi
}
```

## Problem 4

实现一个名为 next 的脚本，当在 CLI 里执行 $ next （$为提示符，不需要输入）时就返回一个整数，第一次返回 1，每执行一次加 1

**Answer**

```bash
COUNTER=0
function next(){
 COUNTER=`expr $COUNTER + 1`
 echo $COUNTER
}
```

## Problem 5

一个文件含有 N 行内容，每行的内容都是一个大于等于 0 的整数，无任何空行或其它内容，使用 one-liner 的形式对该文件中的数字求和

**Answer**

嗯...什么命令都不知道的我真的对于此题毫无思路啊，等我看完homework和assignment后再回来！
