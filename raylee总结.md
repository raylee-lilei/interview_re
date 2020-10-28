<!-- TOC -->

- [字符串](#字符串)
    - [1.单词顺序翻转](#1单词顺序翻转)
    - [2字符串替换成空格](#2字符串替换成空格)
    - [3字典序打印出字符串中所有的排序镜像](#3字典序打印出字符串中所有的排序)
    - [4字符串是否表示数值](#4字符串是否表示数值)
    - [5字符串正则匹配](#5字符串正则匹配)
    - [6字符串只出现一次得 字符并 返回他的位置](#6字符串只出现一次得-字符并-返回他的位置)
    - [7字符串转化为一个整数](#7字符串转化为一个整数)
    - [8 字符流中第一个只出现一次的字符](#8-字符流中第一个只出现一次的字符)
    - [9字符序列循环左移](#9字符序列循环左移)
- [栈和队列和数组](#栈和队列和数组)
    - [1.两个栈实现队列](#1两个栈实现队列)
    - [2.两个只出现一次的数字](#2两个只出现一次的数字)
    - [3.数组是否能组成顺子](#3数组是否能组成顺子)
    - [4.判断二位数组中是否含有该整数](#4判断二位数组中是否含有该整数)
    - [5.数组的旋转](#5数组的旋转)
    - [6.数组返回它的最大连续子序列的和](#6数组返回它的最大连续子序列的和)
    - [7数组中数字拼接求最小值](#7数组中数字拼接求最小值)
    - [8.数组中的逆序对数](#8数组中的逆序对数)
    - [9.数组中任意一个 重复的数字(哈希)](#9数组中任意一个-重复的数字哈希)
    - [10 找出数组中有一个数字出现的次数超过数组长度的一半](#10-找出数组中有一个数字出现的次数超过数组长度的一半)
    - [11数组中奇数放在前半,偶数放在后半部分](#11数组中奇数放在前半偶数放在后半部分)
    - [12  和为s的连续正数序列中的两个整数](#12--和为s的连续正数序列中的两个整数)
    - [13 有序数组查找和为s](#13-有序数组查找和为s)
    - [14滑动窗口](#14滑动窗口)
    - [15数据流中的中位数](#15数据流中的中位数)
    - [16 统计一个数字在排序数组中出现的次数](#16-统计一个数字在排序数组中出现的次数)
  - [code](#code)
    - [17  判断是否是出栈的序列](#17--判断是否是出栈的序列)
    - [18实现min函数栈](#18实现min函数栈)
    - [19.输入n个整数，找出其中最小的K个数。(快排,堆)](#19输入n个整数找出其中最小的k个数快排堆)
- [二叉树](#二叉树)
    - [1.从上往下打印出二叉树的每个节点，同层节点从左至右打印。](#1从上往下打印出二叉树的每个节点同层节点从左至右打印)
    - [2.输入一颗二叉树的根节点和一个整数，打印出二叉树中结点值的和为输入整数的所有路径。路径定义为从树的根结点开始往下一直到叶结点所经过的结点形成一条路径。](#2输入一颗二叉树的根节点和一个整数打印出二叉树中结点值的和为输入整数的所有路径路径定义为从树的根结点开始往下一直到叶结点所经过的结点形成一条路径)
    - [3.给定一棵二叉搜索树，请找出其中的第k小的结点](#3给定一棵二叉搜索树请找出其中的第k小的结点)
    - [4.输入一棵二叉搜索树，将该二叉搜索树转换成一个排序的双向链表。要求不能创建任何新的结点，只能调整树中结点指针的指向。](#4输入一棵二叉搜索树将该二叉搜索树转换成一个排序的双向链表要求不能创建任何新的结点只能调整树中结点指针的指向)
    - [5.判断二叉树B是不是A的子结构](#5判断二叉树b是不是a的子结构)
    - [6.判断该二叉树是否是平衡二叉树或者树的深度](#6判断该二叉树是否是平衡二叉树或者树的深度)
      - [6.1树的深度](#61树的深度)
      - [6.2判断树是否是平衡二叉树](#62判断树是否是平衡二叉树)
    - [7.判断该数组是不是二叉搜索树的后续遍历的结果](#7判断该数组是不是二叉搜索树的后续遍历的结果)
    - [8.判断一颗二叉树是不是对称](#8判断一颗二叉树是不是对称)
    - [9.前中 重建该二叉树](#9前中-重建该二叉树)
    - [10.层次遍历](#10层次遍历)
    - [11序列化和反序列化二叉树](#11序列化和反序列化二叉树)
    - [12源二叉树镜像](#12源二叉树镜像)
    - [13之字遍历](#13之字遍历)
    - [14中序遍历的后继节点](#14中序遍历的后继节点)
- [链表](#链表)
    - [1.输入一个链表，按链表从尾到头的顺序返回一个ArrayList。](#1输入一个链表按链表从尾到头的顺序返回一个arraylist)
    - [2 链表是否有环](#2-链表是否有环)
    - [3.链表进行深拷贝并返回拷贝后的结果](#3链表进行深拷贝并返回拷贝后的结果)
    - [4.链表中导数第k个结点&链表反转](#4链表中导数第k个结点链表反转)
    - [5两个链表第一个公共节点](#5两个链表第一个公共节点)
    - [6删除链表中重复的节点](#6删除链表中重复的节点)
    - [7.链表递增合并](#7链表递增合并)
- [矩阵](#矩阵)
    - [1.地上有一个m行和n列的方格。一个机器人从坐标0,0的格子开始移动，每一次只能向左，右，上，下四个方向移动一格，但是不能进入行坐标和列坐标的数位之和大于k的格子。 例如，当k为18时，机器人能够进入方格（35,37），因为3+5+3+7 = 18。但是，它不能进入方格（35,38），因为3+5+3+8 = 19。请问该机器人能够达到多少个格子？](#1地上有一个m行和n列的方格一个机器人从坐标00的格子开始移动每一次只能向左右上下四个方向移动一格但是不能进入行坐标和列坐标的数位之和大于k的格子-例如当k为18时机器人能够进入方格3537因为3537--18但是它不能进入方格3538因为3538--19请问该机器人能够达到多少个格子)
    - [2.输入一个矩阵，按照从外向里以顺时针的顺序依次打印出每一个数字。](#2输入一个矩阵按照从外向里以顺时针的顺序依次打印出每一个数字)
    - [3.判断在一个矩阵中是否存在一条包含某字符串所有字符的路径](#3判断在一个矩阵中是否存在一条包含某字符串所有字符的路径)
- [动态规划](#动态规划)
    - [1剪绳子](#1剪绳子)
- [数学式](#数学式)
    - [1.base的exponent次方](#1base的exponent次方)
  - [2.给定一个数组A[0,1,...,n-1],请构建一个数组B[0,1,...,n-1],其中B中的元素B[i]=A[0]*A[1]*...*A[i-1]*A[i+1]*...*A[n-1]。不能使用除法。（注意：规定B[0] = A[1] * A[2] * ... * A[n-1]，B[n-1] = A[0] * A[1] * ... * A[n-2];）](#2给定一个数组a01n-1请构建一个数组b01n-1其中b中的元素bia0a1ai-1ai1an-1不能使用除法注意规定b0--a1--a2----an-1bn-1--a0--a1----an-2)
    - [3.把只包含质因子2、3和5的数称作丑数（Ugly Number）。](#3把只包含质因子23和5的数称作丑数ugly-number)
    - [4.斐波那契](#4斐波那契)
    - [5.跳台阶一只青蛙一次可以跳上1级台阶，也可以跳上2级。求该青蛙跳上一个n级的台阶总共有多少种跳法](#5跳台阶一只青蛙一次可以跳上1级台阶也可以跳上2级求该青蛙跳上一个n级的台阶总共有多少种跳法)
    - [6.一只青蛙一次可以跳上1级台阶，也可以跳上2级……它也可以跳上n级。求该青蛙跳上一个n级的台阶总共有多少种跳法。](#6一只青蛙一次可以跳上1级台阶也可以跳上2级它也可以跳上n级求该青蛙跳上一个n级的台阶总共有多少种跳法)
    - [7.约瑟夫环](#7约瑟夫环)
    - [8求1+2+3+...+n，要求不能使用乘除法、for、while、if、else、switch、case等关键字及条件判断语句（A?B:C）](#8求123n要求不能使用乘除法forwhileifelseswitchcase等关键字及条件判断语句abc)
    - [9写一个函数，求两个整数之和，要求在函数体内不得使用+、-、*、/四则运算符号。](#9写一个函数求两个整数之和要求在函数体内不得使用-四则运算符号)
    - [10.任意非负整数区间中1出现的次数](#10任意非负整数区间中1出现的次数)
    - [11.判断二进制数中表示1的个数](#11判断二进制数中表示1的个数)
- [小技巧](#小技巧)
- [排序](#排序)

<!-- /TOC -->
# 字符串

### 1.单词顺序翻转

1. 定义一个临时数组存放一个单词
2. 遇到空格就把该单词存放在result中（注意拼接顺序）
3. 确定最后一个单词，拼接在result中

```C++
class Solution {
public:
    string ReverseSentence(string str) {
        string result = "";
        string tempArray = "";
        for(int i = 0;i<str.size();++i){
            if(str[i]== ' ' ){
                result = " " + tempArray + result;
                tempArray = "";
            }else{
                tempArray+=str[i];
            }
        }
        if(tempArray.size()){
            result = tempArray + result;
        }
        return result;
    }
};
```

### 2字符串替换成空格

```
class Solution { 
public: 
    void replaceSpace(char *str,int length) {
        //验空
        if(str ==nullptr || length<=0 ){
            return;
        }
        //求出原始字符串长度
        int blankSpaceCount = 0;
        int originStrLen = 0;
        //求出空格数
       for(int i = 0;str[i]!='\0';i++){
           originStrLen++;
           if(str[i]==' '){
               blankSpaceCount++;
           }
       }
        int newStrLen = blankSpaceCount*2 + originStrLen;
        char *originpStr = str + originStrLen;
        char *newpStr = str + newStrLen;
        while(originpStr < newpStr){
            if(*originpStr== ' '){
                *newpStr-- = '0';
                *newpStr-- = '2';
                *newpStr-- = '%';
            }else{
                *newpStr--= *originpStr;
            }
            originpStr--;
        }
}
};
```

### 3字典序打印出字符串中所有的排序

输入一个字符串,按字典序打印出该字符串中字符的所有排列。
例如输入字符串abc,则打印出由字符a,b,c所能排列出来的所有字符串abc,acb,bac,bca,cab和cba。

<form action="" method="">
<fieldset><legend font-weight:600>思路：</legend>
<div align=“Center”>递归</div>


1. 全排列
   &emsp;&emsp;（1）检查输出的字符串长度是否等于输入长度
   &emsp;&emsp;（2）如果相等使用find 函数判断是否存在重复的，添加不重复的

&emsp;&emsp;&emsp;&emsp;find(result.begin(),result.end(),str) == result.end() 
&emsp;&emsp;&emsp;&emsp;&emsp;返回的是指针
&emsp;&emsp;&emsp;&emsp;&emsp;如果在查找范围内不存在，返回result.end()
&emsp;&emsp;（3）固定位置，字符依次同后面字符交换
&emsp;&emsp;（4）递归后面字符的排列
&emsp;&emsp;（5）还原交换前的状态

2. 结果按字典排序

</fieldset>
</form>

code

``` C++
class Solution {
public:
    //(1) 遍历出所有可能出现在第一个位置的字符
    //(2) 固定第一个字符，求后面字符的排列
    vector<string> Permutation(string str) {
        vector<string> result;
        if(str.empty()){
            return result;
        }
        //全排列
        Permutation(str,result,0);
        //结果按字典排序
        sort(result.begin(),result.end());
        return result;
    }
    
    void Permutation(string str,vector<string> &result,int state){
        //结束条件，输出的字符串长度==输入的字符串长度
        if(state == str.size()-1){
            //find  返回的是指针
            // 如果在查找范围内不存在，返回a.end()
            
            //如果result中不存在str，才添加；避免重复添加的情况
            if(find(result.begin(),result.end(),str) == result.end()){
                result.push_back(str);
            }
        }else{
            for(int i= state;i<str.size();i++){
                //state 用来固定位置,第一个字符同后面所有字符交换
                swap(str[i],str[state]);
                //后面字符的排列——递归
                Permutation(str,result,state+1);
                //还原交换前的状态
                swap(str[i],str[state]);
            }
        }
    }
    
    void swap(char &str1 ,char &str2){
        char temp ;
        temp = str1;
        str1 = str2;
        str2 = temp;
    }
    
};
```

### 4字符串是否表示数值 

请实现一个函数用来判断字符串是否表示数值（包括整数和小数）。例如，字符串"+100","5e2","-123","3.1416"和"-1E-16"都表示数值。 但是"12e","1a3.14","1.2.3","+-5"和"12e+4.3"都不是。



1. +-15
2. +  || -
3. 两个 . . false
4. e10(e前面没有数)   1e12e（e前面已经有一个e）
5. e +
6. e + -
7. e后面没有数


``` bash 
class Solution {
public:
    bool isNumeric(char* string)
    {
        //e 后面没有数字
        //有其他字符
        //两个小数点
        //+-连续
        //e后面有小数点
        if(string == NULL){
            return false;
        }
        
        if(*string == '+' || *string == '-'){
            string++;
            //+- 15
            if(*string == '+' || *string == '-'){
                return false;
            }
            //+  || -
            if(*string = '\0'){
            return false;
            }
        }
        int decimal = 0,e = 0,number = 0;
        while(*string != '\0'){
            if(*string >= '0' && *string<= '9'){
                string++;
                number++;
            }else if(*string == '.'){
                // 两个小数点 ..  不行
                //e后面有.不行
                if(decimal>0 || e >0){
                    return false;
                }
                string++;
                decimal++;   
            }else if(*string == 'e' || *string == 'E'){
                //e10(e前面没有数)   1e12e（e前面已经有一个e）
                if(number == 0 || e> 0){
                    return  false;
                }
                string++;
                e++;
                //e+
                if(*string == '+' || *string == '-'){
                    string++;
                    //e+ +
                    if(*string == '+' || *string == '-'){
                        return false;
                    }
                }
                //e后面没有数
                if(*string == '\0'){
                    return false;
                }
            }else{
                return false;
            }
        }
        return true;
        
    }

};
```

### 5字符串正则匹配

请实现一个函数用来匹配包括'.'和'*'的正则表达式。模式中的字符'.'表示任意一个字符，而'*'表示它前面的字符可以出现任意次（包含0次）。 在本题中，匹配是指字符串的所有字符匹配整个模式。例如，字符串"aaa"与模式"a.a"和"ab*ac*a"匹配，但是与"aa.a"和"ab*a"均不匹配

B[i] == A[0] A[1] A[2] A[i-1] ... A[i+1]... A[n-1]
1. str 和pattern都为空 
2. str不为空 pattern为空
3. 都不为空
&emsp;&emsp;&emsp;(1).（aaa&emsp;&emsp;a.a;aaa&emsp;&emsp;.aa ）pattern+1不是为*，第一个相同继续比较下一个；str不为空，pattern为.继续比较下一个
&emsp;&emsp;&emsp;(2).（aa&emsp;&emsp;a*aa;aaa&emsp;&emsp;.*a ）pattern+1为*,第一个相同继续比较下一个pattern跳过两个；str不为空，pattern为.str向下移动;否则（aa&emsp;&emsp;c*aa）pattern跳过两个



``` bash ss
class Solution {
public:
    bool match(char* str, char* pattern)
    {
        if(*str =='\0' && *pattern == '\0'){
            return true;
        }
        if(*str !='\0' && *pattern == '\0'){
            return false;
        }
        
        //都不为空
        if(*(pattern+1) != '*'){ //aaa  a.a    aaa   .aa
            if(*str == *pattern || (*str != '\0')&& *pattern == '.'){
                return match(str+1,pattern+1);
            }else{
                return false;
            }
        }else{
            if(*str == *pattern || (*str != '\0')&& *pattern == '.'){
                return match(str,pattern+2) || match(str+1,pattern);
                //aa a*aa
                //aaa .*a 只需要看str 是否相同，.* *可以为n个
            }else{ // aa    c*aa
                return match(str,pattern+2);
            }
        }
    }
};
```

### 6字符串只出现一次得 字符并 返回他的位置

在一个字符串(0<=字符串长度<=10000，全部由字母组成)中找到第一个只出现一次的字符,并返回它的位置, 如果没有则返回 -1（需要区分大小写）.（从0开始计数）

<form action="" method="">
<fieldset><legend font-weight:600>思路:</legend>
<div align=“Center”>hash map</div>


1. 定义一个hash表 unordered_map<char,int> hash
2. 遍历统计每个字符出现的次数
3. 遍历出满足出现的次数

</fieldset>
</form>

code

``` C++
class Solution {
public:
    int FirstNotRepeatingChar(string str) {
        if(str.size() == 0) return -1;
        //遍历统计每个字符出现的次数
        unordered_map<char,int> hash;
        for(auto x : str){
            ++hash[x];
        }
        //遍历出现的次数
        for(int i = 0;i<str.length();++i){
            if(hash[str[i]] == 1){
                return i;
            }
        }
        return  -1;
    }
};
```

### 7字符串转化为一个整数

将一个字符串转换成一个整数，要求不能使用字符串转换整数的库函数。 数值为0或者字符串不是一个合法的数值则返回0

<form action="" method="">
<fieldset><legend font-weight:600>思路:</legend>
<div align=“Center”>遍历</div>


1. 定义 一个标记位
2. 判断第一个为‘-’，标记位为 -1，否则为1
3. 开始遍历，若果第一个字符为‘-’，就从第二个位置开始
4. 判断后面的字符是否是数字
5. 转化为数字
6. 乘以标记位得到结果

</fieldset>
</form>

code

``` bash
class Solution {
public:
    int StrToInt(string str) {
        int len=str.length();
        int result;
        if(len<0) result=0;
        int flag;
        if(str[0]=='-')
            flag=-1;
        else flag=1;

        for(int i=(str[i]=='-'||str[i]=='+')?1:0;i<len;++i)
            {
            if(!(str[i]>='0'&&str[i]<='9'))//不在范围内的返回0
                {
                return 0;
            }
           result=result*10+str[i]-'0';//范围内的字符转换为整数
        }
        return result*flag;

    }
};
```

### 8 字符流中第一个只出现一次的字符

请实现一个函数用来找出字符流中第一个只出现一次的字符。例如，当从字符流中只读出前两个字符"go"时，第一个只出现一次的字符是"g"。当从该字符流中读出前六个字符“google"时，第一个只出现一次的字符是"l"。
如果当前字符流没有存在出现一次的字符，返回#字符。

<form action="" method="">
<fieldset><legend font-weight:600>思路:</legend>
<div align=“Center”>hash map</div>


1. 输入字符串存入vec 中，然后写出hash表
2. 遍历hash表，返回表中的值为1的数

</fieldset>
</form>

code

``` bash
class Solution
{
public:
  //Insert one char from stringstream
    string vec;
    char hash[255] = {0};
    void Insert(char ch)
    {
        vec += ch;
        hash[ch]++;
    }
  //return the first appearence once char in current stringstream
    char FirstAppearingOnce()
    {
        for(int i =0;i<vec.size();++i){
            if(hash[vec[i]]==1){
                return vec[i];
            }
        }
        return '#';
    }

};
```

### 9字符序列循环左移

汇编语言中有一种移位指令叫做循环左移（ROL），现在有个简单的任务，就是用字符串模拟这个指令的运算结果。对于一个给定的字符序列S，请你把其循环左移K位后的序列输出。例如，字符序列S=”abcXYZdef”,要求输出循环左移3位后的结果，即“XYZdefabc”。是不是很简单？OK，搞定它！

<form action="" method="">
<fieldset><legend font-weight:600>思路:</legend>
<div align=“Center”>截取字符串</div>


1. 拿出前n位
2. 删除前n位
3. 拿出的前n位放到str之后 

</fieldset>
</form>

code

```C++
class Solution {
public:
    string LeftRotateString(string str, int n) {
        
        /*
        //截取前n位插入字符串的后面
        string tempStr="";
        if(n<0){
            return NULL;
        }
        if(n==0){
            return str;
        }
        tempStr = str.substr(0,n); //从第0 位开始截取str的n-1 个数
        str.erase(0,n);
        str+=tempStr;
        return str;
        
        */
        if(n<0){
            return NULL;
        }
        if(n==0){
            return str;
        }
        string tempStr = "";
        for(int i = n;i<str.size();++i){
            tempStr.push_back(str[i]);
        }
        for(int i = 0;i<n;++i){
            tempStr.push_back(str[i]);
        }
        return tempStr;
    }
};
```



# 栈和队列和数组

### 1.两个栈实现队列

用两个栈来实现一个队列，完成队列的Push和Pop操作。 队列中的元素为int类型。

```
class Solution
{
public:
    void push(int node) {
        stack1.push(node);
    }

    int pop() {
       if(stack2.empty()){
           while(!stack1.empty()){
               stack2.push(stack1.top());
               stack1.pop();
           }
       }
       int QueenTemp = stack2.top();
       stack2.pop();
       return QueenTemp;
    }

private:
    stack<int> stack1;
    stack<int> stack2;
};
```

### 2.两个只出现一次的数字

1. 遍历统计出现的次数
2. 定义vector存放只出现一次的数
3. 写出求的数

- code1:

```
class Solution {
public:
    void FindNumsAppearOnce(vector<int> data,int* num1,int *num2) {
       if(data.size() == 0){
            return;
        }
        //求num1 ^ num2
        int XorResult = 0;
        for(auto x: data){
            XorResult ^= x;
        }
        
        //统计移位次数
        int SiftCount = 0;
        while((XorResult&1)==0){
            XorResult = XorResult>>1;
            ++SiftCount;
        }
        
        //分组
        for(auto x:data){
            if(((x>>SiftCount)&1) == 1){
                *num1 ^= x;
            }else{
                *num2 ^= x;
            }
        }
        return;     
    }
};
```

-  code2:

```
class Solution {
public:
    void FindNumsAppearOnce(vector<int> data,int* num1,int *num2) {
        //使用Map
        unordered_map<int,int> hash;
        for(auto x: data) hash[x]++;
        vector<int> temp;//存放num1 和 num2
        for(auto x:data){
           if(hash[x] ==1){
               temp.push_back(x);
           }
        }
        *num1 = temp[0];
        *num2 = temp[1];       
    }
};
```

### 3.数组是否能组成顺子

1. 统计0的个数
2. 统计间隙数
3. 如果0的个数大于等于间隙数，0可以填充在他们之间构成顺子，否则return  false。

```
class Solution {
public:
    bool IsContinuous( vector<int> numbers ) {
        if(numbers.size()<5){
            return false;
        }
        sort(numbers.begin(),numbers.end());
        int NumOfZero = 0, SpaceCount = 0;
            //统计0的个数
        for(int i = 0;i<numbers.size();++i ){
            if(numbers[i]== 0)NumOfZero++;
        }
           //统计间隙数
        for(int j = NumOfZero+1;j<numbers.size();j++){
            if(numbers[j]==numbers[j-1])return false;
            else{
                SpaceCount+= numbers[j]-numbers[j-1] -1;
            }
        }
        if(NumOfZero >= SpaceCount){
            return true;
        }else{
            return false;
        }
    }
};
```

### 4.判断二位数组中是否含有该整数

确定右上角数的X、Y坐标。
&emsp;&emsp;如果target比右上角值大，肯定在下一行，行往下找。
&emsp;&emsp;如果target比右上角值小，肯定在最后一列的左边，列往左找。

```
class Solution{
public:
    bool Find (int target, vector<vector<int> > array){
        //找到数组的行
        int rows = array.size();
        //找到数组的列
        int cols = array[0].size();
        //找到右上角的数的X Y坐标
        int rowX = 0;
        int rowY = cols-1;
        //数组范围内查找
        while(rowX < rows && 0 <= rowY){
            if(target > array[rowX][rowY]){
                rowX++;
            }else if(target < array[rowX][rowY]){
                rowY--;
            }else
                return true;
        }
        return false;
    }
};
```

### 5.数组的旋转

把一个数组最开始的若干个元素搬到数组的末尾，我们称之为数组的旋转。
**输入一个非递减排序的数组的一个旋转，输出旋转数组的最小元素。**
*例如数组{3,4,5,1,2}为{1,2,3,4,5}的一个旋转，该数组的最小值为1。*
*NOTE：给出的所有元素都大于0，若数组大小为0，请返回0。*

二分法查找
由于数组是递增的，旋转之后实际上前一部分是递增的，后一部分也是递增的。
利用二分查找：
如果中间元素值大于最后一个元素值，说明最小值在右半区间，
如果中间元素值小于最后一个元素值，说明最小值在左半区间，或者min就是这个中间值
如果相等说明有相同元素，需要将判断区间往前缩一下，继续判断。
不断循环，当二分查找的的左右区间相等了，就说明找到最小值了。

```
class Solution {
public:
    int minNumberInRotateArray(vector<int> rotateArray) {
        if(rotateArray.size()==0){
            return 0;
        }
        //定义组数开始、中间、结尾的下标
        int first = 0;
        int end = rotateArray.size()-1;
        int middle = 0;
        
        while(first<end){
            middle = (first+end)/2;
            //当中间元素 大于 最后一个元素，说明最小值在右半区间 
            //此时缩小区间first 到 end
            if(rotateArray[middle]>rotateArray[end]){
                first +=1;
            }else if(rotateArray[middle]<rotateArray[end]){
                //当中间元素 小于 最后一个元素 ，说明最小值在右半区间，并且这个中间值也可能是最小值
                end = middle;
            }else{
                //中间元素 等于 最后一个元素，存在重复的元素，只能缩小一个范围
                end -=1;
            }
        }
        
        return rotateArray[first];
    }    
};
```

### 6.数组返回它的最大连续子序列的和

```
class Solution {
public:
    int FindGreatestSumOfSubArray(vector<int> array) {
        if(array.empty()){
            return 0;
        }
        vector<int> F_i(array.size());
        F_i[0] = array[0];
        
        for(int i =1; i < array.size(); ++i){
            if(F_i[i-1]<=0){
                F_i[i] = array[i];
            }else{
                F_i[i] = F_i[i-1]+array[i];
             }
        }
        return *max_element(F_i.begin(),F_i.end()); 
        
    }
};
```

### 7数组中数字拼接求最小值

1. a + b < b + a 则  a  排在前面
2. 利用sort排序，排序方式按照camp 排序
3. 输出字符串

```
class Solution {
public:
    static bool camp(int a, int b){
        string a_s = to_string(a);
        string b_s = to_string(b);
        return a_s + b_s < b_s + a_s;
    }
    string PrintMinNumber(vector<int> numbers) {
        string result;
        sort(numbers.begin(),numbers.end(),camp);
        for(auto x :numbers){
            result += to_string(x);
        }
        return result;
    }
};
```

### 8.数组中的逆序对数

1. 分治（分成左右两边相等的两个数组，递归继续划分，直到只剩下数组只有 1个元素）
2. 合并排序，定义一个临时数组存放排序后的结果（在合并的过程中就能找出逆序对）
3. 主要是找 左边和右边  断开的逆序对
   &emsp;&emsp;若果此时i 的值比j的值小，他们之间不构成逆序对，把最小的值放入临时数组中，并且指向i 的指针向后移动继续比较
   &emsp;&emsp;若果发现此时i 的值比j 的值大，他们构成逆序对，并且他们之间有 （mid - i + 1）对
4. 判断前半部分
5. 判断后半部分
6. 排序好的覆盖原来的

```
class Solution {
public:
    int count;
    int InversePairs(vector<int> nums) {
        if(nums.size()!=0){
            //分治   划分整个数组
            divide(nums ,0,nums.size()-1);
        }
        return count;
    }
    //分治思路
    void divide(vector<int> &nums,int start,int end){
        if(start >= end) return;
        //取中间值
        int mid = start + (end-start)/2;
        //递归左右两边数组   
        divide(nums,start,mid);
        divide(nums,mid+1,end);
        //合并排序
        merge(nums,start,mid,end);
    }
    
    //合并
    void merge(vector<int> &nums,int start ,int mid, int end){
        //定义临时数组
        vector<int> temp;
        int i = start , j = mid+1,k = 0;
        //比较左右两边间隙，中间存在逆序对 【start....i.....mid】【mid+1.....j.....end】
        while(i<=mid && j<=end){
            //若果此时i 的值比j的值小，他们之间不构成逆序对，把 最小的值放入临时数组中，并且指向i 的指针向后移动继续比较
            if(nums[i] <= nums[j]){
                temp.push_back(nums[i++]);
            }else{
                //若果发现此时i 的值比j 的值大，他们构成逆序对，并且他们之间有 （mid - i + 1）对
                temp.push_back(nums[j++]);
                count = (count + mid-i+1)%1000000007;
            }
        }
        //判断前半部分 
        while(i<=mid){
            temp.push_back(nums[i++]);
        }
        //判断后半部分
        while(j<=end){
            temp.push_back(nums[j++]);
        }
        //排序好的覆盖原来的
        for(k;k<temp.size();++k){
            nums[start+k] = temp[k];
        }
    }
    
};
```

### 9.数组中任意一个 重复的数字(哈希)

```
class Solution {
public:
    // Parameters:
    //        numbers:     an array of integers
    //        length:      the length of array numbers
    //        duplication: (Output) the duplicated number in the array number
    // Return value:       true if the input is valid, and there are some duplications in the array number
    //                     otherwise false

    bool duplicate(int numbers[], int length, int* duplication) {

        if(numbers== NULL || length ==0){
            return 0;
        }
        //hash map
        int hashTable[255] = {0};
        for(int i= 0;i<length;++i){
            hashTable[numbers[i]]++;
        }
        int count = 0;
        for(int i = 0 ;i<length;++i){
            if(hashTable[numbers[i]]>1){
                duplication[count++]=numbers[i];
                return  true;
            }
        }
        return false;
    }
};
```

### 10 找出数组中有一个数字出现的次数超过数组长度的一半

数组中有一个数字出现的次数超过数组长度的一半，请找出这个数字。
例如输入一个长度为9的数组{1,2,3,2,2,2,5,4,2}。由于数字2在数组中出现了5次，超过数组长度的一半，因此输出2。如果不存在则输出0。

```
sort排序
1. 找数（中间的值即为所求）
2. 遍历计算计数
3. 判断是否满足条件
class Solution {
public:
    int MoreThanHalfNum_Solution(vector<int> numbers) {      
        if(numbers.empty()){
            return 0;
        }
        //排序 如果满足条件，中间的值即为所求
        sort(numbers.begin(),numbers.end());
        int numSize = numbers.size();
        int halfNumSize = numSize >> 1;
        int middle = numbers[halfNumSize];
        
        //遍历计算计数
        int count = 0;
        for(auto x : numbers){
            if(middle == x){
                ++count;
            }
        }
        return (count > halfNumSize) ? middle : 0;
    }
};
```

code2

```
1.数组规律
2. 重新计算count的值
3. 判断是否满足条件
class Solution {
public:
    int MoreThanHalfNum_Solution(vector<int> numbers) {
        if(numbers.empty()){
            return 0;
        }
        int curVal,count = 0;
        int numSize = numbers.size();
        int halfNumSize = numSize >> 1;
        //int boundary = numSize >> 1;
        //作用就是迭代容器中所有的元素，每一个元素的临时名字就是x，等同于
        //for (vector<int>::iterator iter = nums.begin(); iter != nums.end(); iter++)
        //找出这个数字(如果有符合条件的数字，则它出现的次数比其他所有数字出现的次数和还要多)
        for(auto x : numbers){
            //如果相等计数加一
            if(curVal == x){
                ++count;
            }else{ //不相等继续判断，如果count不等于0，计数减一
                if(count>0){
                    --count;
                }else{//如果等于0 ，curVal当前值存放下一个值，并且把count置1
                    curVal=x;
                    count=1;
                }
            }
        }
        //重新计算count的值，来判断是否满则条件
        for(auto x : numbers){
            if(curVal == x){
                ++count;
            }
        }
        return (count > halfNumSize) ? curVal : 0;
    }
};
```

### 11数组中奇数放在前半,偶数放在后半部分

输入一个整数数组，实现一个函数来调整该数组中数字的顺序，使得所有的奇数位于数组的前半部分，所有的偶数位于数组的后半部分，并保证奇数和奇数，偶数和偶数之间的相对位置不变。

```
class Solution {
public:
    void reOrderArray(vector<int> &array) {
        vector<int> tempArray;
        vector<int>::iterator iter = array.begin();
        for(;iter!=array.end();){
            if(((*iter)&1) == 0){
                tempArray.push_back(*iter); //偶数放在临时数组中
                iter = array.erase(iter); //删除偶数的位置
            }else{
                iter++; //奇数迭代器加1
            }
        }
        //把新得的偶数放回array 中
        vector<int>::iterator iterNew = tempArray.begin();
        for(;iterNew != tempArray.end();iterNew++){
            array.push_back(*iterNew);
        }
        
    }
};
```

code2

```
class Solution {
public:
    void reOrderArray(vector<int> &array) {
        int PreToEnd = 0;
        int EndToPre = array.size()-1;
        int *temp = new int[array.size()]();
        for (int i = 0; i < array.size(); i++) {
            if ((array[i]&1)==1) {
                temp[PreToEnd++] = array[i];
            }
            if ((array[array.size() - i - 1]&1) == 0) {
                temp[EndToPre--] = array[array.size() - i - 1];
            }
        }
        
        for(int i= 0;i<array.size();i++){
            array[i]=temp[i];
        }
       
    }
};
```



### 12  和为s的连续正数序列中的两个整数

输出所有和为S的连续正数序列。序列内按照从小至大的顺序，序列间按照开始数字从小到大的顺序

1. 在两个指针内等差数列求和 
2. 如果和比输入数小，大指针向后移（先加上大的）
3. 相等的话依次将数插入数组中
4. 再把数组序列插入结果中，小指针继续加加，向后找
5. 如果和比输入数大，小指针向后移（先减去小的）

```
class Solution {
public:
    vector<vector<int> > FindContinuousSequence(int sum) {
       vector<vector<int> >result;
        int small=1,big=2;
        while(small<big){
            int cur=(small+big)*(big-small+1)/2;
            if(cur<sum) big++;
            else if(cur==sum){
                vector<int> temp;
                for(int i=small;i<=big;i++){
                    temp.push_back(i);
                }
                result.push_back(temp);
                small++;
            }
            else small++;
        }
        return result;
    }
};
```

### 13 有序数组查找和为s

输入一个递增排序的数组和一个数字S，在数组中查找两个数，使得他们的和正好是S，如果有多对数字的和等于S，输出两个数的乘积最小的。
对应每个测试案例，输出两个数，小的先输出。

1. 在头尾指针里面
2. 如果相等，直接把头尾指针放到数组中输出
3. 如果比输入值小，头指针向后移动 
4. 如果比输入值大，尾指针向前移动

```
class Solution {
public:
    vector<int> FindNumbersWithSum(vector<int> array,int sum) {
        vector<int> result;
        if(array.size() == 0 ){
            return result;
        }
        int leftP = 0;
        int rightP = array.size()-1;
        while(leftP < rightP){
            int toltal = array[leftP]+array[rightP];
            if(toltal == sum){
                result.push_back(array[leftP]);
                result.push_back(array[rightP]);
                break;
            }else if(toltal < sum){
                ++leftP;
            }else{
                --rightP;
            }
        }
        return result;
    }
};
```

### 14滑动窗口

给定一个数组和滑动窗口的大小，找出所有滑动窗口里数值的最大值。例如，如果输入数组{2,3,4,2,6,2,5,1}及滑动窗口的大小3，那么一共存在6个滑动窗口，他们的最大值分别为{4,4,6,6,6,5}； 针对数组{2,3,4,2,6,2,5,1}的滑动窗口有以下6个： {[2,3,4],2,6,2,5,1}， {2,[3,4,2],6,2,5,1}， {2,3,[4,2,6],2,5,1}， {2,3,4,[2,6,2],5,1}， {2,3,4,2,[6,2,5],1}， {2,3,4,2,6,[2,5,1]}。

1. 定义一个队列，存放数组的下标
2. 当后一个比 队列中下标的值大，删除队列中的元素（最大的排在最前面）
3. 队列中插入下标
4. 如果窗口都划出了size个了，某个值还是最大，删除前面的大值
5. 只要大于3之后每次都将队列最前面的值插入结果中

```
class Solution {
public:
    vector<int> maxInWindows(const vector<int>& num, unsigned int size)
    {
         vector<int> result;
        if(size<1 || num.size()<size){
            return result;
        }
        deque<int> qmax;
        for(int i=0; i<num.size(); ++i){
            //遍历大小，最大的排在最前面
            while(!qmax.empty() && num[qmax.back()]<=num[i]){
                qmax.pop_back();
            }
            //队列插入下标
            qmax.push_back(i);
            
            //如果窗口都划出了size个了，某个值还是最大，删除前面的大值
            if(qmax.front() == i-size)
                {
                qmax.pop_front();
            }
            //只要大于3之后每次都将最前面的值插入结果中
            if(i >= size - 1){
                result.push_back(num[qmax.front()]);
            }
        }
        return result; 
    }
};
```

### 15数据流中的中位数

如何得到一个数据流中的中位数？如果从数据流中读出奇数个数值，那么中位数就是所有数值排序之后位于中间的数值。如果从数据流中读出偶数个数值，那么中位数就是所有数值排序之后中间两个数的平均值。我们使用Insert()方法读取数据流，使用GetMedian()方法获取当前读取数据的中位数。

1. 插入数组时，使用upper_bound(),返回数组中最后一个大于等于num 的值
2. 找中位数如果为偶数返回中间两个值的平均
3. 如果为奇数，返回中间值

方式二

<form action="" method="">
<fieldset><legend font-weight:600>思路二 :</legend>
<div align=“Center”>优先队列</div>
    priority_queue<int, vector<int>,greater<int>> right;//越小越优先[5,6,7] 拿出5 小根堆（数较大） 升序优先队列，优先删除最小 的
    priority_queue<int, vector<int>,less<int>> left; //越大越优先 [4,3,1]拿出4  大根 对（数较小）   降序    优先删除最大的



1. 将数组划分两个数组流
2. 先放入往左边数组放一个值 ，根据大小顶对的特点插入数据
3. 最终大根堆降序，小根堆升序
4. 取出中位数

```
class Solution {
public:
#if 0
    vector<int> DataStream;
    void Insert(int num)
    {
        //使用STL中upper_bound(),返回数组中最后一个大于等于num 的值
        auto position = upper_bound(DataStream.begin(), DataStream.end(), num);
        DataStream.insert(position, num);
    }

    double GetMedian()
    { 
        int size = DataStream.size();
        if(size%2==0){
            return 1.0*(DataStream[size/2-1]+DataStream[size/2])/2;
        }else{
            return DataStream[size/2]*1.0;
        }
    }
#endif
    //[1,3,4,5,6,7]   [1,3,4]和[5,6,7]
    //优先队列
    priority_queue<int, vector<int>,greater<int>> right;//越小越优先[1,3,4] 拿出4
    priority_queue<int, vector<int>,less<int>> left; //越大越优先[5,6,7] 拿出5
    void Insert(int num)
    {
        left.push(num);
        if(left.size()-right.size()>1) {
			//从大根堆拿最大的元素在小根 堆中
            right.push(left.top());
            left.pop();
        }
        if(right.size()>0 && left.top()>right.top()){
            int tmp=left.top();
            left.pop();
            left.push(right.top());
            right.pop();
            right.push(tmp);
        }
    }

    double GetMedian()
    { 
        if(left.size()==right.size()) return 1.0*(left.top()+right.top())/2;
        else return left.top();
    }
};
```

### 16 统计一个数字在排序数组中出现的次数

统计一个数字在排序数组中出现的次数。

<form action="" method="">
<fieldset><legend font-weight:600>思路:</legend>
<div align=“Center”>二分法</div>


1. 将数组二分
2. 二分直到 找到和k 相同的位置
3. 相同位置 往前找相同数
4. 相同位置 往后找相同数
5. 返回计数

</fieldset>
</form>

## code

``` C++
class Solution {
public:
    int GetNumberOfK(vector<int> data ,int k) {
        //二分法找中间
        int Len = data.size();
        if(Len ==0){
            return 0;
        }
        int start = 0,mid = 0,end = Len-1,count=0;
        //二分直到 找到和k 相同的位置
        while(start < end){
            mid = (end + start)>>1;
            if(k<data[mid]){
                end = mid-1;
            }
            if(k>data[mid]){
                start = mid+1;
            }
            if(k == data[mid]){
                break;
            }
        }
        //相同位置 往前找相同数
        int i = mid;
        while(i>=0 && k==data[i]){
            --i;
            ++count;
        }
        //相同位置 往后找相同数
        i = mid+1;
        while(i<Len && k==data[i]){
            ++i;
            ++count;
        }
        
        return count;
    }
};
```

### 17  判断是否是出栈的序列

输入两个整数序列，第一个序列表示栈的压入顺序，请判断第二个序列是否可能为该栈的弹出顺序。假设压入栈的所有数字均不相等。
例如序列1,2,3,4,5是某栈的压入顺序，序列4,5,3,2,1是该压栈序列对应的一个弹出序列，但4,3,5,1,2就不可能是该压栈序列的弹出序列。
（注意：这两个序列的长度是相等的）

思路：
借助一个辅助vector
1. 遍历序列1，依次存入辅助vector  TempArray中
2. 遍历的同时比较依次插入TempArray中的最后一个元素是否和序列2 中的第一个元素相等
3. 如果不相等继续往下遍历序列1
4. 如果相等，就把TempArray的最后一个元素删除，再比较序列2中的下一个元素
5. 最后返回TempArray是否为空，为空则是弹出序列

```
class Solution {
public:
    bool IsPopOrder(vector<int> pushV,vector<int> popV) {
        if(pushV.empty()){
            return false;
        }
        vector<int> TempArray;
        for(int i=0,j =0;i<=pushV.size()-1;i++){
            TempArray.push_back(pushV[i]);
            while(j<=pushV.size()-1 && TempArray.back() == popV[j]){
                TempArray.pop_back();
                j++;
            }
        }
        return TempArray.empty();
    }
};
```

### 18实现min函数栈

助一个辅助栈找min
1. 对操作栈压栈，辅助栈压入一个值
2. 比较压入栈的值与栈顶元素的大小；如果小就压栈，否则不压栈
3. 如果辅助栈的值与操作栈的值相等辅助栈出栈
4. 操作栈出栈
5. 返回操作栈栈顶元素
6. 返回辅助栈栈顶元素就是最小值

```
class Solution {
public:
    stack<int> StackStructure,AssistStack; 
    void push(int value) {
        StackStructure.push(value);
        if(AssistStack.empty()){
            AssistStack.push(value);
        }else if(value <= AssistStack.top()){
            AssistStack.push(value);
          }
    }
    void pop() {
        if(StackStructure.top() == AssistStack.top()){
            AssistStack.pop();
        }
        StackStructure.pop();
    }
    int top() {
        return StackStructure.top();
    }
    int min() {
        return AssistStack.top();
    }
};
```

### 19.输入n个整数，找出其中最小的K个数。(快排,堆)

```
class Solution {
public:
    vector<int> GetLeastNumbers_Solution(vector<int> input, int k) {
        vector<int> MinResult;
        int size = input.size();
        if(input.empty()||k>size){
            return MinResult;
        }
        sort(input.begin(),input.end());
        
        for(int i = 0;i<k;++i){
            MinResult.push_back(input[i]);
        }
        return MinResult;
    }
};
```



# 二叉树

### 1.从上往下打印出二叉树的每个节点，同层节点从左至右打印。

借助一个辅助队列
1. 把二叉树存放在队列里面
2. 队列的front的值放入vector中
3. 如果左子树为真，左子树放入vector中
4. 如果右子树为真，右子树放入vector中
5. 出队列
6. 返回PrintTreeNode打印出节点

```C++ 
/*
struct TreeNode {
	int val;
	struct TreeNode *left;
	struct TreeNode *right;
	TreeNode(int x) :
			val(x), left(NULL), right(NULL) {
	}
};*/
class Solution {
public:
    vector<int> PrintFromTopToBottom(TreeNode* root) {
        vector<int> PrintTreeNode;
        //辅助队列
        queue<TreeNode*> TempQueue;
        if(root == NULL){
            return PrintTreeNode;
        }
        TempQueue.push(root);
        while(!TempQueue.empty()){
            PrintTreeNode.push_back(TempQueue.front()->val);
            if(TempQueue.front()->left){
                TempQueue.push(TempQueue.front()->left);
            }
            if(TempQueue.front()->right){
                TempQueue.push(TempQueue.front()->right);
            }
            TempQueue.pop();
        }
        return PrintTreeNode;
    }
};
```

### 2.输入一颗二叉树的根节点和一个整数，打印出二叉树中结点值的和为输入整数的所有路径。路径定义为从树的根结点开始往下一直到叶结点所经过的结点形成一条路径。

1. 定义一个临时数组存储路径 ； 一个返回二维存放路径（全局变量）
2. 把根的值放入tempArray，判断是否与输入整数相等，是否为叶节点
3. 若果不满足，递归判断左子树，直到叶节点

4. 删除最后一个叶节点（即回到上一个节点）继续递归右子树
   if(tempArray.size()!= 0){
          tempArray.pop_back();
      }

5. 重复3——4步骤，直到所有路劲遍历完
6. 返回满足条件的path



```C++
#include<iostream>
#include<vector>
using namespace std;

struct TreeNode {
	int val;
	struct TreeNode *left;
	struct TreeNode *right;
	TreeNode(int x) :
			val(x), left(NULL), right(NULL) {
	}
};

class Solution {
private:
    vector<int> tempArray;
    vector<vector<int>> Path;
public:
    vector<vector<int>> FindPath(TreeNode* root,int expectNumber) {
        

        if(root ==NULL){
            return Path;
        }
        tempArray.push_back(root->val);
        
        if(root->val == expectNumber&& root->left ==NULL && root->right == NULL){
            Path.push_back(tempArray);
        }
    
        if(root->val !=expectNumber && root -> left != NULL ){
            FindPath(root->left,expectNumber-root->val);
        }
        if(root->val!=expectNumber && root->right !=NULL){
              FindPath(root->right,expectNumber-root->val);
        }
    
        if(tempArray.size()!= 0){
            tempArray.pop_back();
        }
        return Path;
    }

};

int main()
{  
	//构建二叉树
	Solution tree;
	vector<vector<int> > result;
	TreeNode* root = new TreeNode(22);
	root->left = new TreeNode(10);
	root->right = new TreeNode(13);
	root->right->right = new TreeNode(5);
	root->left->left = new TreeNode(4);
	root->left->right = new TreeNode(8);
	

	result = tree.FindPath(root, 40);
	
	for (int i = 0; i < result.size(); i++)
	{
		for (int j = 0; j < result[i].size(); j++)
		{
			cout << result[i][j] << " ";
		}
		cout << endl;
	}
	return 0;

}
```

### 3.给定一棵二叉搜索树，请找出其中的第k小的结点

中序遍历的结果按照从小到大的顺序排列的

1. 遍历左子树
2. k--
3. 如果k==0，res = 节点
4. 遍历右子树

```C++
/*
struct TreeNode {
    int val;
    struct TreeNode *left;
    struct TreeNode *right;
    TreeNode(int x) :
            val(x), left(NULL), right(NULL) {
    }
};
*/
class Solution {
public:
    TreeNode* res = NULL;
    //中序遍历结果就是从小到大顺序
    TreeNode* KthNode(TreeNode* pRoot, int k)
    {
        DFS(pRoot,k);
        return res;
    }
    void DFS(TreeNode* pRoot, int &k){
        if(!pRoot){
            return;
        }
        //左
        DFS(pRoot->left,k);
        //根
        k--;
        if(k==0){
            res = pRoot;
        }
        //右
        DFS(pRoot->right,k);
    }


};
```

### 4.输入一棵二叉搜索树，将该二叉搜索树转换成一个排序的双向链表。要求不能创建任何新的结点，只能调整树中结点指针的指向。

1. 定义一个栈；定义一个指针pre记录上一次出栈值
2. 遍历左子树放入栈中
3. 取出栈顶元素就是最小值也是链表头结点
4. 出栈，第一次出栈，前一次指针pre为空；如果不为空穿线，pre后继直线当前位置，当前位置的前继指向pre的位置
5. pre指向当前位置
6. 继续遍历右子树

```C++
/*
struct TreeNode {
	int val;
	struct TreeNode *left;
	struct TreeNode *right;
	TreeNode(int x) :
			val(x), left(NULL), right(NULL) {
	}
};*/
class Solution {
public:
    TreeNode* Convert(TreeNode* pRootOfTree)
    {
        if(pRootOfTree == NULL){
            return NULL;
        }
        

        TreeNode *head = NULL;
        TreeNode *pre = NULL;
        stack<TreeNode*> tempStack;
        
        while(pRootOfTree || !tempStack.empty()){
            //找到左子树的最小值并依次压栈
            while(pRootOfTree){
                tempStack.push(pRootOfTree);
                pRootOfTree = pRootOfTree->left;
            }
            //当前指针指向最小值
            if(!tempStack.empty()){
                pRootOfTree = tempStack.top();
                tempStack.pop();
                if(pre != NULL){
                    //pre的后继指向当前（最开始指向最小值）
                    pre->right = pRootOfTree;
                    //当前的前继指向pre
                    pRootOfTree->left = pre; 
                }else{
                    //返回头结点
                    head = pRootOfTree;
                }
            //pre向后移动
            pre = pRootOfTree;
            //找是否存在右子树
            pRootOfTree = pRootOfTree->right;
        }
     }
    return head;
    }

};
```

### 5.判断二叉树B是不是A的子结构

输入两棵二叉树A，B，判断B是不是A的子结构。（ps：我们约定空树不是任意一个树的子结构）

<form action="" method="">
<fieldset><legend font-weight:600>思路：</legend>
<div align=“Center”>二叉树递归</div>
1. 判断根节点是否相同
2. 若果不同，A的左子树与B的根比较；A的右子树与B的根比较
3. 判断是否是子结构
4. 检查A和B是否已经遍历完了
5. 不相等就返回false
6. 相等A和B的左子树是否相等，A和B的右子树是否相等，都相等B是A的子结构，否则不是

```
/*
struct TreeNode {
	int val;
	struct TreeNode *left;
	struct TreeNode *right;
	TreeNode(int x) :
			val(x), left(NULL), right(NULL) {
	}
};*/
class Solution {
public:
    bool HasSubtree(TreeNode* pRoot1, TreeNode* pRoot2)
    {
        //B为空不是子结构
        if(pRoot2 == NULL){
            return false;
        }
        //A为空肯定没有子结构
        if(pRoot1 == NULL){
            return false;
        }
        
        //判断第一个根节点是否相同
        bool flag = IsSubTree(pRoot1,pRoot2);
        
        //判断A的左子树有没有B子结构
        if(!flag){
           flag = HasSubtree(pRoot1->left,pRoot2); 
        }
          //判断A的右子树有没有B子结构
        if(!flag){
           flag = HasSubtree(pRoot1->right,pRoot2);
        }
        return flag;
    }    
    bool IsSubTree(TreeNode* pSub1,TreeNode* pSub2){
        
        //判断B中还是否有子树
        if(pSub2 == NULL){
            //B已经没有子树了，但是和A是相同的
            return true;
        }
        //A已经没有子树了，B还有，则B肯定不是A的子结构
        if(pSub1 == NULL){
            return false;
        }
        if(pSub1->val != pSub2->val){
            return false;
        }
        //继续遍历左右子树
        return IsSubTree(pSub1->left,pSub2->left) && IsSubTree(pSub1->right,pSub2->right);
    }

};
```

### 6.判断该二叉树是否是平衡二叉树或者树的深度

#### 6.1树的深度

1. 递归遍历左子树

2. 递归遍历右子树

3. 返回最大值加一

   ```
   /*
   struct TreeNode {
   	int val;
   	struct TreeNode *left;
   	struct TreeNode *right;
   	TreeNode(int x) :
   			val(x), left(NULL), right(NULL) {
   	}
   };*/
   class Solution {
   public:
       int TreeDepth(TreeNode* pRoot)
       {
           if(pRoot ==  NULL) return 0;
           return max(TreeDepth(pRoot->left),TreeDepth(pRoot->right))+1;
       }
   };
   ```

#### 6.2判断树是否是平衡二叉树

输入一棵二叉树，判断该二叉树是否是平衡二叉树。
在这里，我们只需要考虑其平衡性，不需要考虑其是不是排序二叉树

**平衡二叉树又称AVL树，它是一棵空树或它的左右两个子树的高度差的绝对值不超过1，并且左右两个子树都是一棵平衡二叉树。**

1. 找出左右子树的深度 
2. 判断深度差是否小于1

```
class Solution {
public:
    bool status = true;
    bool IsBalanced_Solution(TreeNode* pRoot)
    {
       GetDeep(pRoot);
       return status;
    }  
    
    int GetDeep(TreeNode* pRoot){
       if(pRoot == NULL){
           return 0;
       }
       int leftDeep = GetDeep(pRoot->left);
       int rightDeep = GetDeep(pRoot->right);
       if(abs(leftDeep-rightDeep)>1){
            status = false;
       }
       return max(leftDeep,rightDeep)+1;
     }
};
```

### 7.判断该数组是不是二叉搜索树的后续遍历的结果

输入一个非空整数数组，判断该数组是不是某二叉搜索树的后序遍历的结果。如果是则输出Yes,否则输出No。假设输入的数组的任意两个数字都互不相同。

```
class Solution {
public:
    bool VerifySquenceOfBST(vector<int> sequence) {
        //存放数组前半部分左子树， 后半部分右子树
        vector<int> leftArray,rightArray;
        int  TreeRoot = sequence.back();
        if(sequence.empty()){
            return false;
        }
        //找出分解线
        int i = 0;//把i写成去全局
        for(;i < sequence.size()-1;++i){
            if(sequence[i]>TreeRoot)
                break;
        }
        //判断右边
        for(int j = i;j<sequence.size()-1;++j){
            if(sequence[j]<TreeRoot)
               return false;
            }
        //前半部分放入左子树
        for(int m = 0;m < i;++m){
            leftArray.push_back(sequence[m]);
        }
        //后半部分放入右子树
        for(int n = i;n < sequence.size()-1;++n){
            rightArray.push_back(sequence[n]);
        }
        //判断左右子树是否为二叉搜索树
        bool leftTree = true;
        bool rightTree = true;
        if(leftArray.size()>0){
            leftTree = VerifySquenceOfBST(leftArray);
        }
        if(rightArray.size()>0){
            rightTree = VerifySquenceOfBST(rightArray);
        }
        return (leftTree && leftTree);
    }
};
```

### 8.判断一颗二叉树是不是对称

请实现一个函数，用来判断一颗二叉树是不是对称的。注意，如果一个二叉树同此二叉树的镜像是同样的，定义其为对称的。

1. 左子树的左子树和右子树的右子树相等
2. 左子树的右子树和右子树的左子树相等

```
/*
struct TreeNode {
    int val;
    struct TreeNode *left;
    struct TreeNode *right;
    TreeNode(int x) :
            val(x), left(NULL), right(NULL) {
    }
};
*/
class Solution {
public:
    //左子树的左子树和右子树的右子树相等
    //左子树的右子树和右子树的左子树相等
    bool isSymmetrical(TreeNode* pRoot)
    {
        if(pRoot == NULL){
            return true;
        }
        return IsMirror(pRoot->left,pRoot->right);
    }
    bool IsMirror(TreeNode* pRoot1,TreeNode* pRoot2){
        if(pRoot1 == NULL && pRoot2 == NULL){
            return true;
        }
        if(pRoot1 == NULL || pRoot2 == NULL){
            return false;
        }
        if(pRoot1->val != pRoot2->val){
            return false;
        }
        return(IsMirror(pRoot1->left,pRoot2->right) && IsMirror(pRoot1->right,pRoot2->left));
    }

};
```

### 9.前中 重建该二叉树

输入某二叉树的前序遍历和中序遍历的结果，请重建出该二叉树。

假设输入的前序遍历和中序遍历的结果中都不含重复的数字。例如输入前序遍历序列{1,2,4,7,3,5,6,8}和中序遍历序列{4,7,2,1,5,3,8,6}，则重建二叉树并返回。

```
/**
 * Definition for binary tree
 * struct TreeNode {
 *     int val;
 *     TreeNode *left;
 *     TreeNode *right;
 *     TreeNode(int x) : val(x), left(NULL), right(NULL) {}
 * };
 */
class Solution {
public:
    TreeNode* reConstructBinaryTree(vector<int> pre,vector<int> vin) {
      if(pre.empty()||vin.empty()||pre.size()!=vin.size()){
          return NULL;
      }
      return Pre_Mid_ConstructBinaryTree(pre,vin);
}
      TreeNode*  Pre_Mid_ConstructBinaryTree(vector<int> &pre,vector<int> &mid){
          //确定根（前序遍历的第一个数就是根）
          int Root = pre[0];         
          //New一个重建二叉树
          TreeNode* PTree = new TreeNode(Root);
          
          //将中序遍历的结果分为左右两个部分放入vector中
          vector<int> MidL;
          vector<int> MidR;
          //前序遍历的结果从根之后开始依次是左子树和右子树，同样也单独存放在vector中
          vector<int> PreL;
          vector<int> PreR;
          int i = 0;int j =1;
          //分别找出前序和中序的左子树
          while(mid[i]!=Root){
             MidL.push_back(mid[i++]);
             PreL.push_back(pre[j++]);
          }
          //跳过中序遍历中的根
          ++i;
          //分别找出前序和中序的右子树
          while(i<mid.size()){
             MidR.push_back(mid[i++]);
             PreR.push_back(pre[j++]);
          }
          
          //构建左右子树
          if(!MidL.empty()&& !PreL.empty()){
             PTree->left = Pre_Mid_ConstructBinaryTree(PreL,MidL);
          }
          if(!MidR.empty()&& !PreR.empty()){
             PTree->right = Pre_Mid_ConstructBinaryTree(PreR,MidR);
          }
          return PTree;
      }
};
```

code

```
//前序中序还原建立二叉树
TreeNode* pre_mid_createBiTree(char *pre,char *mid,int len) 
{
    if(len==0)
        return NULL;
    char ch=pre[0];  //找到先序中的第一个结点
    int index=0;
    while(mid[index]!=ch)//在中序中找到的根结点的左边为该结点的左子树，右边为右子树
    {
        index++;
    }
    TreeNode* T=new TreeNode(ch);//创建根结点
    T->data=ch;
    T->lchild=pre_mid_createBiTree(pre+1,mid,index);//建立左子树
    T->rchild=pre_mid_createBiTree(pre+index+1,mid+index+1,len-index-1);//建立右子树
    return T;
}

//后序中序还原建立二叉树
TreeNode* pro_mid_createBiTree(char *last,char *mid,int len)
{
    if(len==0)
       return NULL;
    char ch=last[len-1]; //取得后序遍历顺序中最后一个结点
    int index=0;//在中序序列中找根结点，并用index记录长度
    while(mid[index]!=ch)//在中序中找到根结点，左边为该结点的左子树，右边为右子树
       index++;
    TreeNode* T=new TreeNode(ch);;//创建根结点
    T->data=ch;
    T->lchild=pro_mid_createBiTree(last,mid,index);//建立左子树
    T->rchild=pro_mid_createBiTree(last+index,mid+index+1,len-index-1);//建立右子树
    return T;
}
```

### 10.层次遍历

从上到下按层打印二叉树，同一层结点从左至右输出。每一层输出一行。

1. 定义一个队列和一个指向队列头的指针
2. 往队列里面添加树根
3. 在队列不为空的条件下，定义一个临时数组
4. 队列出队
5. 向临时数组中添加指针指向的值
6. 遍历每一层，将 每一层的值插入队列中
7. 每一层的值放入Result中
8. 返回Result

```
/*
struct TreeNode {
    int val;
    struct TreeNode *left;
    struct TreeNode *right;
    TreeNode(int x) :
            val(x), left(NULL), right(NULL) {
    }
};
*/
class Solution {
public:
        vector<vector<int> > Print(TreeNode* pRoot) {
            vector<vector<int>> Result;
            if(pRoot == NULL){
                return Result;
            }
            TreeNode* MoveNode = NULL;
            queue<TreeNode*> queTree;
            queTree.push(pRoot);
            while(!queTree.empty()){
                int size = queTree.size();
                vector<int> temp;
                while(size--){
                    MoveNode = queTree.front();
                    queTree.pop();
                    temp.push_back(MoveNode->val);
                    if(MoveNode->left!=NULL){
                        queTree.push(MoveNode->left);
                    }
                    if(MoveNode->right!=NULL){
                        queTree.push(MoveNode->right);
                    }
                }
                Result.push_back(temp);
            }
            return Result;
        
        }
};
```

### 11序列化和反序列化二叉树

请实现两个函数，分别用来序列化和反序列化二叉树

二叉树的序列化是指：把一棵二叉树按照某种遍历方式的结果以某种格式保存为字符串，从而使得内存中建立起来的二叉树可以持久保存。序列化可以基于先序、中序、后序、层序的二叉树遍历方式来进行修改，序列化的结果是一个字符串，序列化时通过 某种符号表示空节点（#），以 ！ 表示一个结点值的结束（value!）。

二叉树的反序列化是指：根据某种遍历顺序得到的序列化字符串结果str，重构二叉树。

例如，我们可以把一个只有根节点为1的二叉树序列化为"1,"，然后通过自己的函数来解析回这个二叉树

<form action="" method="">
<fieldset><legend font-weight:600>思路:</legend>
<div align=“Center”>二叉树遍历</div>


1. 序列化（树——>字符串）
2. char——>string
3. 如果为空res = '#'
4. 如果不为空，每个树节点之后加上字符","
5. 遍历左子树
6. 遍历右子树
7. 反序列化（字符串——>树）
8. 计算下每个节点字符的长度
9. 判断字符是否为空
10. 定义一个符号位
11. 如果字符串中遇到"-"符号位= -1
12. 计数指针向后移动一位
13. 将每个节点的字符转成数字
14. 数字乘上符号位
15. 计数指针往后移动判断下一个节点的数字
16. 生成二叉树（递归反序列化左子树、右子树）


</fieldset>
</form>

code

``` bash
/*
struct TreeNode {
    int val;
    struct TreeNode *left;
    struct TreeNode *right;
    TreeNode(int x) :
            val(x), left(NULL), right(NULL) {
    }
};
*/
class Solution {
public:
    char* Serialize(TreeNode *root) { 
        string res;
        //深度优先遍历算法
        DFS1(root,res);
        //string  转 char
        char* p = new char[res.size()];
        strcpy(p, res.c_str());
        return p;
    }
    //二叉树序列化
    void DFS1(TreeNode *root,string &res){
        //遍历到空节点
        if(!root){
            res += "#,";
            return;
        }
        //非空节点
        res += to_string(root->val) + ",";
        DFS1(root->left, res);
        DFS1(root->right, res);
        
    }
    //反序列化
    TreeNode* Deserialize(char *str) {
        int index = 0;
        return DFS2(str,index);
    }
    //index 字符串串长度
    TreeNode* DFS2(char *str,int &index){
        //确定每个数字 长度  135长度为3   3 长度1
        int len = index;
        while(str[len] != ','){
            len++;
        }
        //空节点
        if(str[index]=='#'){
            index = len+1;
            return NULL;
        }
        //非空节点
        int num = 0;
        //符号
        int sign = 1;
        if(index<len && str[index] == '-'){
            sign = -1;
            index++;
        }
        for(int i = index;i<len;++i){
            num = num *10 + str[i] - '0';
        }
        num *= sign;
        //index往下走
        index = len+1;
        
        auto root = new TreeNode(num);
        root->left = DFS2(str,index);
        root->right = DFS2(str,index);
        return root;
    }

};
```

###   12源二叉树镜像

操作给定的二叉树，将其变换为源二叉树的镜像。

```
/*
struct TreeNode {
	int val;
	struct TreeNode *left;
	struct TreeNode *right;
	TreeNode(int x) :
			val(x), left(NULL), right(NULL) {
	}
};*/
class Solution {
public:
    void Mirror(TreeNode *pRoot) {
        if(!pRoot){
            return;
        }
        TreeNode* tempTree = pRoot->left;
        pRoot->left = pRoot->right;
        pRoot->right = tempTree;
        
        //递归左子树
        Mirror(pRoot->left);
        //递归右子树
        Mirror(pRoot->right);
    }
};
```

### 13之字遍历

```
从上到下按层打印二叉树，同一层结点从左至右输出。每一层输出一行。

<form action="" method="">
<fieldset><legend font-weight:600>思路:</legend>
<div align=“Center”>层次遍历  队列</div>


1. 定义一个队列和一个指针指向队列的头部 
2. 先把根存放在队列中
3. 在队列不为空的条件下遍历
4. 定义一个临时数组
5. 出队列
6. 把指针指向的值存放在临时数组中
7. 找指针的左右子树，放入队列中
8. 一层遍历完之后，把临时数组放入Result中
9. 返回Result

</fieldset>
</form>

## code2

​``` bash
/*
struct TreeNode {
    int val;
    struct TreeNode *left;
    struct TreeNode *right;
    TreeNode(int x) :
            val(x), left(NULL), right(NULL) {
    }
};
*/
class Solution {
public:
        vector<vector<int> > Print(TreeNode* pRoot) {
            vector<vector<int>> Result;
            if(pRoot == NULL){
                return Result;
            }
            TreeNode* MoveNode = NULL;
            queue<TreeNode*> queTree;
            queTree.push(pRoot);
            while(!queTree.empty()){
                int size = queTree.size();
                vector<int> temp;
                while(size--){
                    MoveNode = queTree.front();
                    queTree.pop();
                    temp.push_back(MoveNode->val);
                    if(MoveNode->left!=NULL){
                        queTree.push(MoveNode->left);
                    }
                    if(MoveNode->right!=NULL){
                        queTree.push(MoveNode->right);
                    }
                }
                Result.push_back(temp);
            }
            return Result;
        
        }
};
```

### 14中序遍历的后继节点

1. 判断是否有右子树
2. 有右子树：下个结点就是右子树最左边的点（D，B，E，A，C，G）
3. 没有右子树：（1）这个节点是父节点左孩子（N，I，L）——父节点就是下一个节点
   &emsp;&emsp;&emsp; &emsp;&emsp;（2）这个节点是父节点右孩子（H，J，K，M）——找他的父节点的父节点的父节点...直到找的这个节点是他父节点的左孩子位置，如果没有，比如M，那么他就是尾节点。

```
/*
struct TreeLinkNode {
    int val;
    struct TreeLinkNode *left;
    struct TreeLinkNode *right;
    struct TreeLinkNode *next;
    TreeLinkNode(int x) :val(x), left(NULL), right(NULL), next(NULL) {
        
    }
};
*/
class Solution {
public:
    TreeLinkNode* GetNext(TreeLinkNode* pNode)
    {
        if(pNode == NULL){
            return NULL;
        }
        //输入D 存在右孩子的时候，下一个节点就是找一直找左孩子
        if(pNode->right != NULL){
            pNode = pNode->right;
            while(pNode->left !=NULL){
                pNode = pNode->left;
            }
            return pNode;
        }
        //没有右孩子找父节点，只要父节点不为空一直遍历
        while(pNode->next !=NULL){
            //定义一个父节点
            TreeLinkNode* pRoot = pNode->next;
            //N是父节点的左孩子，返回父节点
            if(pRoot->left == pNode){
                return pRoot;
            }
            //.J是右孩子，一直找父节点的父节点
            pNode = pNode->next;
        }
        //其他情况返回NULL
        return NULL;
    }
};
```



# 链表

### 1.输入一个链表，按链表从尾到头的顺序返回一个ArrayList。

借助栈stack先进后出反弹至vector中
1.定义一个链表指针指向输入的链表 保存链表类型的地址。
2.遍历输入的链表，依次压栈。
3.每次取出栈顶元素放入vector容器中。
4.出栈

```C++
class Solution {
public:
    vector<int> printListFromTailToHead(ListNode* head) {
        //借助栈
        //创建一个链表指针指向输入的链表
        ListNode *p =NULL;
        p = head;
        

        stack<int> TempStack; //定义一个栈
        vector<int> ArrayList; //定义一个vector容器
        while(p!=NULL){
            //压栈
            TempStack.push(p->val);
            p=p->next;
        }
        while(!TempStack.empty()){
            //把出栈的值放到vector容器中也就是返回的ArrayList
            ArrayList.push_back(TempStack.top());//栈顶的元素放到ArrayList中
            //出栈
            TempStack.pop();  
        }
        return ArrayList;
        
    }

};
```

* ```C++
  使用反向迭代器所有容器都定义了 begin 和 end 成员，分别返回指向容器首元素和尾元素下一位置的迭代器。容器还定义了 rbegin 和 rend 成员，分别返回指向容器尾元素和首元素前一位置的反向迭代器
  /**
  
  *  struct ListNode {
  *  int val;
  *  struct ListNode *next;
  *  ListNode(int x) :
  *  val(x), next(NULL) {
  *  }
  *  };
     */
     class Solution {
     public:
      vector<int> printListFromTailToHead(ListNode* head) {       
          vector<int> ArrayList; //定义一个vector容器
          //创建一个链表指针指向输入的链表
          ListNode *p =NULL;
          p = head;
          while(p!=NULL){
              ArrayList.push_back(p->val);
              p = p->next;
          }
     	//返回一个反向迭代器
          return vector<int>(ArrayList.rbegin(),ArrayList.rend());        
      }
     };
  ```

### 2 链表是否有环

1. 定义快慢指针（快指针一次走两步，慢指针一次走一步）
2. 找第一次相遇点，一定相遇在环内
3. 慢指针指向头指针
4. 快慢指针一次走一步，如果相等则说明再次相遇点是环的入口
5. 返回任意一个指针

```
/*
struct ListNode {
    int val;
    struct ListNode *next;
    ListNode(int x) :
        val(x), next(NULL) {
    }
};
*/
class Solution {
public:
    ListNode* EntryNodeOfLoop(ListNode* pHead)
    {
        if(pHead == NULL){
            return NULL;
        }
        ListNode* fast = pHead;
        ListNode* slow = pHead;
        //相遇点
        while(fast && fast->next){
            fast = fast->next->next;
            slow = slow->next;
            if(slow == fast){
                break;
            }
        }
        if(!fast || !fast->next){
            return NULL;
        }
        slow = pHead;
        while(fast!=slow){
            slow = slow->next;
            fast = fast->next;
        }
        return fast;
    }
};
```

### 3.链表进行深拷贝并返回拷贝后的结果

1. 复制一个与前一个值相同的结点
2. 穿线链接成一个新的链表
3. 设置新链表的随机指针作用域
   pClone->random =pNode->random->next;
4. 指向新链表的第二个结点即拷贝好的链表的头结点
5. 穿线操作拆分成两个链表（复制和被复制）

```
/*
struct RandomListNode {
    int label;
    struct RandomListNode *next, *random;
    RandomListNode(int x) :
            label(x), next(NULL), random(NULL) {
    }
};
*/
class Solution {
public:
    RandomListNode* Clone(RandomListNode* pHead)
    {
        if(pHead == NULL){
            return NULL;
        }
        //复制链表节点并连线
        CloneNodeConnect(pHead);
        //新结点设置随机指针
        SetNodeRandom(pHead);
        //把链表从新拆分成两个链表
        return ReConnect(pHead);
    }
    
    void CloneNodeConnect(RandomListNode* Head){
        RandomListNode *pNode = Head;
        while(pNode != NULL){
            RandomListNode *pClone = new RandomListNode(pNode->label);
            pClone->next = pNode->next;
            pNode->next = pClone;
            pNode = pClone->next;
            
        }
    }
    
    void SetNodeRandom(RandomListNode* Head){
        RandomListNode *pNode = Head;
        while(pNode != NULL){
            RandomListNode *pClone = pNode->next;
            if(pNode->random){
                pClone->random =pNode->random->next;  
            }
            pNode = pClone->next;
        }
    }
    
    RandomListNode* ReConnect(RandomListNode* Head){
        RandomListNode* pNode = Head;
        //返回头结点
        RandomListNode* pCloned = Head->next;
        while(pNode != NULL){
            RandomListNode* pClone = pNode->next;
            //重连原链表
            pNode->next = pClone->next;
            pNode = pNode->next;
            if(pNode != NULL){
                //重连新链表
                pClone->next = pNode->next;
            }
        }
        return pCloned;
        
    }
};
```

### 4.链表中导数第k个结点&链表反转

头插法

1. 从原链表的头部一个一个取节点并插入到新链表的头部

```
/*
struct ListNode {
	int val;
	struct ListNode *next;
	ListNode(int x) :
			val(x), next(NULL) {
	}
};*/
class Solution {
public:
    ListNode* ReverseList(ListNode* pHead) {

        ListNode* reversal = NULL;
        ListNode* initial = pHead;
        if(pHead == NULL || pHead->next == NULL){
            return pHead;
        }
 
        while(initial != NULL){
            ListNode* next = initial->next;
            initial->next = reversal;  //反转
            reversal = initial;
            initial = next;
        }
        return reversal;
    }
};
```

### 5两个链表第一个公共节点

输入两个链表，找出它们的第一个公共结点。（注意因为传入数据是链表，所以错误测试数据的提示是用其他方式显示的，保证传入数据是正确的）

1. 定义两个指针分别指向两个链表
2. 在p1 != p2 条件下
3. p1 指向空的时候，让他指向pHead2
4. p2 指向空的时候，让他指向pHead1，p1 ！=  p2 p1继续往下指，直到指向空
5. 两个指针分别向后指
6. 返回p1

```
/*
struct ListNode {
	int val;
	struct ListNode *next;
	ListNode(int x) :
			val(x), next(NULL) {
	}
};*/
class Solution {
public:
    ListNode* FindFirstCommonNode( ListNode* pHead1, ListNode* pHead2) {
        if(pHead1== NULL || pHead2 ==  NULL){
            return NULL;
        }
        ListNode *p1 = pHead1;
        ListNode *p2 = pHead2;
        while(p1!=p2){
            //p1 指向空的时候，让他指向pHead2
            p1 = (p1 == NULL ? pHead2 : p1->next );
            //p2 指向空的时候，让他指向pHead1，p1 ！=  p2 p1继续往下指，直到指向空
            p2 = (p2 == NULL ? pHead1 : p2->next );
        }
        return p1;
    }
};
```

### 6删除链表中重复的节点

1. 定义三个指针分别指向头指正和NULL，
2. 在当前指针不为空的条件下遍历
3. 如果当前指针和指针指向的下一个相等，last 指向当前的下一个，否则，pre 指向当前指针，当前指针指向下一个
4. 若果当前指针和指针指向的下一个相等，继续 向下遍历判断last的值和当前的指针任然一样，则last往后移动，知道不等于当前指针的值
5. 若果当前指针和指针指向的下一个相等，last移动后的值已经不等于当前值了，此时我们要删除节点，如果当前指针指向头结点的话，我们要删除从头结点到last的下一个。如果 当前节点没有在头结点，我们删除pre的下一个到last的下一个
6. 更新当前指针，指向last的下一个位置
7. 返回此链表

```
/*
struct ListNode {
    int val;
    struct ListNode *next;
    ListNode(int x) :
        val(x), next(NULL) {
    }
};
*/
class Solution {
public:
    ListNode* deleteDuplication(ListNode* pHead)
    {
        ListNode* cur = pHead;
        ListNode* pre = NULL;
        ListNode* last = NULL;
        if(pHead == NULL){
            return NULL;
        }
        if(pHead->next ==NULL){
            return pHead;
        }
        while(cur!=NULL ){
            if(cur->next!= NULL && cur->next->val == cur->val){
               last = cur->next;
               while(last!=NULL && last->next!=NULL && last->next->val ==  cur->val ){
                   last = last->next;
               }
               if(cur == pHead){
                    pHead = last->next;
               }else{
                    pre->next = last->next;
               }
               cur = last->next;
                
            }else{
                 pre = cur;
                 cur = cur->next;
            }
        }
        return pHead;
    }
};
```

### 7.链表递增合并

输入两个单调递增的链表，输出两个链表合成后的链表，当然我们需要合成后的链表满足单调不减规则。

```
/*
struct ListNode {
	int val;
	struct ListNode *next;
	ListNode(int x) :
			val(x), next(NULL) {
	}
};*/
class Solution {
public:
    ListNode* Merge(ListNode* pHead1, ListNode* pHead2)
    {
        if(!pHead1){
            return pHead2;
        }
        if(!pHead2){
            return pHead1;
        }
        
        ListNode* newList  = NULL;
        //拿出一个小的值作为头结点
        if(pHead1->val<=pHead2->val){
            newList = pHead1;
            pHead1 = pHead1->next;
        }else{
            newList = pHead2;
            pHead2 = pHead2->next;
        }
        ListNode* newListP  = newList;
        while(pHead1 && pHead2){
          if(pHead1->val<=pHead2->val){
             newListP->next = pHead1;//穿线 
             pHead1 = pHead1->next;//第一个指针向后移
             newListP = newListP->next;//合并后的指针也向后移动
          }else{
             newListP->next = pHead2;//穿线
             pHead2 = pHead2->next;//第二个指针向后移
             newListP = newListP->next; 
           }
         }
        //如果两个链表长度不一样
        if(pHead1 == NULL){
            newListP->next = pHead2;
        }
        if(pHead2==NULL){
            newListP->next = pHead1;
        } 
       return newList;
   }
};
```

思路2:新建一个链表利用归并排序

1. 定义一个新的链表
2. 比较大小,较小的依次放入newList
3. newList下一个用未比较的继续比较，较小的依次放入newList

```
/*
struct ListNode {
	int val;
	struct ListNode *next;
	ListNode(int x) :
			val(x), next(NULL) {
	}
};*/
class Solution {
public:
    ListNode* Merge(ListNode* pHead1, ListNode* pHead2)
    {
        if(!pHead1){
            return pHead2;
        }
        if(!pHead2){
            return pHead1;
        }
        ListNode* newList  = NULL;
        
        if(pHead1->val<=pHead2->val){
            newList = pHead1;
            newList->next = Merge(pHead1->next,pHead2);
        }else{
            newList = pHead2;
            newList->next = Merge(pHead1,pHead2->next);
        }
       return newList;
   }
};
```



# 矩阵

### 1.地上有一个m行和n列的方格。一个机器人从坐标0,0的格子开始移动，每一次只能向左，右，上，下四个方向移动一格，但是不能进入行坐标和列坐标的数位之和大于k的格子。 例如，当k为18时，机器人能够进入方格（35,37），因为3+5+3+7 = 18。但是，它不能进入方格（35,38），因为3+5+3+8 = 19。请问该机器人能够达到多少个格子？

1. 定义有一个和矩阵一样的一维数组，初始化为0
2. 首先要判断上下左右是否划出了边界 
3. 数位值之和大于阈值，已近走过
4. 递归找这个值上下左右的位置，满足条件计数加一

```C++
class Solution {
public:
    int movingCount(int threshold, int rows, int cols)
    {
        //定义 一个二维矩阵记录标记
        vector<vector<int>> flag(rows);  //行
        for(int i =0;i<rows;i++){   //列
            flag[i].resize(cols);
        }
        

        return DFS(threshold, rows, cols,flag,0,0);
    }
    
    int DFS(int threshold, int rows, int cols,vector<vector<int>> &flag,int i,int j){
        if(i<0 || i>=rows ||j<0 || j>=cols || CountSum(i)+CountSum(j) > threshold || flag[i][j]== 1){
            return 0;
        }
        flag[i][j]= 1;
        return 1
               +DFS(threshold,rows, cols,flag,i-1,j)
               +DFS(threshold,rows, cols,flag,i+1,j)
               +DFS(threshold,rows, cols,flag,i,j-1)
               +DFS(threshold,rows, cols,flag,i,j+1);
               
    }
    int CountSum(int i){
        int sum = 0;
        while(i>0){
            sum += i % 10;
            i /= 10;
        }
        return sum;
    }

};
```

### 2.输入一个矩阵，按照从外向里以顺时针的顺序依次打印出每一个数字。

1. 从左向右遍历
2. 从上向下遍历
3. 从右向左遍历
4. 从下向上遍历
5. 缩小一圈

```
class Solution {
public:
    vector<int> printMatrix(vector<vector<int> > matrix) {
        //矩阵的行列
        int rows = matrix.size();
        int  cols = matrix[0].size();
        vector<int> PrintArray;
        if(rows == 0||cols == 0){
            return PrintArray;
        }
        int top = 0;  int right = cols-1;  int bottom =rows-1; int left = 0;
        while (left <= right && top <= bottom){
        //从左到右
        for(int i= top;i<=right;++i){
            PrintArray.push_back(matrix[top][i]);
        }

        //从上到下
        for(int j =top+1;j<=bottom;++j){
            PrintArray.push_back(matrix[j][right]);
        }
        //从右到左
        if (top != bottom)
        for(int m =right-1;m >=left; --m){
             PrintArray.push_back(matrix[bottom][m]);
        }
        //从下到上
        if (left != right)
        for(int n = bottom-1;n>top;--n){
            PrintArray.push_back(matrix[n][left]);
        }
        ++top;
        --right;
        --bottom;
        ++left;
      }
    return PrintArray;
    }
};
```

### 3.判断在一个矩阵中是否存在一条包含某字符串所有字符的路径

1. 定义有一个和矩阵一样的一维数组，初始化为0
2. 遍历矩阵，找字符串第一个在矩阵中的位置（首先要判断上下左右是否划出了边界）
3. 修改标志位的值，表示这个位置已经走过
4. 判断下str下一个是否是最后一个
5. 找这个值上下左右的位置
6. 没找到这个字符的上下左右是字符串中的路径，当前值变为未走过，继续去找下一个

```
class Solution {
public:
    bool hasPath(char* matrix, int rows, int cols, char* str)
    {
        //矩阵是一维的[a b c e   s f c s   a d e e] 
        //字符串一维 b c c e d 
        //找一个标志位实际上是和矩阵一样的一个数组  用来判断是否走过  0  未走过  1  表示走过
        vector<char> flag(rows*cols,0);
        bool Result = false;
        //遍历矩阵
        for(int i = 0;i < rows;++i){
            for(int j = 0;j< cols;++j){
                Result = (Result || IsPath(matrix,flag,i,j,str,rows,cols));
            }
        }
        return Result;
    }
    
    bool IsPath(char* matrix,vector<char> flag,int x,int y,char *str,int rows, int cols){
        //判断是否溢出了矩阵的边界
        if(x<0 || x>= rows || y<0 || y>=cols){
            return false;
        }
        //找字符串第一个在矩阵中的位置
        if(matrix[x*cols+y] == *str && flag[x*cols+y] == 0){
            //修改标志位的值，表示这个位置已经走过
            flag[x*cols+y] = 1;
            //判断下str 是否是最后一个
            if(*(str+1)==0){
                return true;
            }
            //找这个值上下左右的位置
            bool Result = IsPath(matrix,flag,x,y+1,str+1,rows,cols) ||  
                          IsPath(matrix,flag,x-1,y,str+1,rows,cols) ||
                          IsPath(matrix,flag,x+1,y,str+1,rows,cols) ||
                          IsPath(matrix,flag,x,y-1,str+1,rows,cols);
            //没找到这个字符的上下左右是字符串中的路径，当前值变为未走过
            if(Result == false){
                 flag[x*cols+y] = 0;
            }
            return Result;
         }else{
            return false;
        }
    }

};
```

# 动态规划

给你一根长度为n的绳子，请把绳子剪成整数长的m段（m、n都是整数，n>1并且m>1，m<=n），每段绳子的长度记为k[1],...,k[m]。请问k[1]x...xk[m]可能的最大乘积是多少？例如，当绳子的长度是8时，我们把它剪成长度分别为2、3、3的三段，此时得到的最大乘积是18。

### 1剪绳子 

```
class Solution {
public:
    int cutRope(int number) {
        if(number<=3){
            return number-1;
        }
        //记录最大值
        int dp[number+1];
        dp[0] = 0;
        dp[1] = 1;
        dp[2] = 2;
        dp[3] = 3;
        int res = 0;
        for(int i =4;i<=number;++i){
            for(int j =1;j<=i/2;++j){
                res = max(res,dp[j]*dp[i-j]);
            }
            dp[i] = res;
        }
        return dp[number];
    }
};
```



# 数学式


### 1.base的exponent次方

给定一个double类型的浮点数base和int类型的整数exponent。求base的exponent次方。保证base和exponent不同时为0。

```C++
class Solution {
public:
    double Power(double base, int exponent) {
        if(base == 0){
            if(exponent >0){return 0;}
            else {
                throw std::invalid_argument("input error（divisor！=0）||0 at the same time）");
            }
         }else{
            if(exponent > 0){ return PerformOperation(base,exponent);}
            else if(exponent == 0){return 1;}
            else{return 1/PerformOperation(base,-exponent);}
             }
    }
    

    double PerformOperation(double base,int exponent){
        if(exponent == 1){return base;}
        if((exponent & 1) ==0){
            double Temp_Even = PerformOperation(base,exponent >> 1);
            return Temp_Even*Temp_Even;
        }else{
            double Temp_Odd = PerformOperation(base,(exponent - 1) >> 1);
            return Temp_Odd*Temp_Odd*base;
        }
    }

};
```

## 2.给定一个数组A[0,1,...,n-1],请构建一个数组B[0,1,...,n-1],其中B中的元素B[i]=A[0]*A[1]*...*A[i-1]*A[i+1]*...*A[n-1]。不能使用除法。（注意：规定B[0] = A[1] * A[2] * ... * A[n-1]，B[n-1] = A[0] * A[1] * ... * A[n-2];）

```C++ 
class Solution {
public:
    vector<int> multiply(const vector<int>& A) {
        int n = A.size();
        vector<int>  B(n);
        int ret = 1;
        //B[i] == A[0] A[1] A[2] A[i-1] ... A[i+1]... A[n-1]
        //前半部分
        for(int i = 0;i< n; ret*= A[i++]){
            B[i] = ret;
        }
        ret = 1;
        //后半部分
        for(int i = n-1;i>=0;ret*= A[i--]){
            B[i] *=  ret;
        }
        return B;
    }
};
```

### 3.把只包含质因子2、3和5的数称作丑数（Ugly Number）。

1. 定义一个丑数数组
2. 定义三个数分别指向乘以2、3、5的虚队列
3. 找到分别乘以2,3,5的虚拟队列的最小值
4. 如果最小值与乘以2,3,5中P指向相等，则把P指向的数插入到丑数数组中，并且指向往后移
5. 返回丑数数组最后一个数

```C++
class Solution {
public:
    int GetUglyNumber_Solution(int index) {
        if (index <= 0){
            return 0;
        }
        if(index < 7){
            return index;
        }
        vector<int> UglyResult;
        int P2= 0,P3 =  0,P5 = 0; 
        int MinUgly = 1;
        UglyResult.push_back(MinUgly);
        while(UglyResult.size() < index){
            MinUgly = min(UglyResult[P2]*2,min(UglyResult[P3]*3,UglyResult[P5]*5));
            if(UglyResult[P2]*2 == MinUgly) ++P2;
            if(UglyResult[P3]*3 == MinUgly) ++P3;
            if(UglyResult[P5]*5 == MinUgly) ++P5;
             UglyResult.push_back(MinUgly);
        }
        return UglyResult.back();
    }
};
```

### 4.斐波那契

```
class Solution {
public:
    int Fibonacci(int n) {
        int temp;
        if(n<=0)
            return 0;
        int *Arraylist=new int[n+1];
        Arraylist[1]=Arraylist[2]=1;
        for(int i=3;i<=n;i++)
        {
            Arraylist[i]=Arraylist[i-1]+Arraylist[i-2];
        }
        

        temp=Arraylist[n];
        return temp;
        delete []Arraylist;

 }
};
```



```
class Solution {
public:
    int Fibonacci(int n) {
        int i;
        int PreItem =0;
        int CurrentItem =1;
        if(n<=0)
            return 0;
        if(n==1)
            return 1;
        for(i=2;i<=n;i++){
            CurrentItem = PreItem+CurrentItem;
            PreItem = CurrentItem-PreItem;
        }
        return CurrentItem;
 }
};
```



### 5.跳台阶一只青蛙一次可以跳上1级台阶，也可以跳上2级。求该青蛙跳上一个n级的台阶总共有多少种跳法

```
class Solution {
public:
    int jumpFloor(int number) {
        int temp;
        int *Arraylist=new int[number+1];
        Arraylist[0]=1;
        Arraylist[1]=1;
        for(int i=2;i<=number;i++)
        {
            Arraylist[i]=Arraylist[i-1]+Arraylist[i-2];
        }       
        temp=Arraylist[number];
        return temp;
        delete []Arraylist;
    }
};
```



### 6.一只青蛙一次可以跳上1级台阶，也可以跳上2级……它也可以跳上n级。求该青蛙跳上一个n级的台阶总共有多少种跳法。

```
class Solution {
public:
    int jumpFloorII(int number) {
        int  shift = 1;  //将要移位的数  1* 2^(n-1)
        return 1<<(number - 1);
    }
};
```

### 7.约瑟夫环

```
class Solution {
public:
    int LastRemaining_Solution(int n, int m)
    {
        if(n<=0){
            return -1;
        }
        return (LastRemaining_Solution(n-1,m)+m)%n;
    }
};
```

### 8求1+2+3+...+n，要求不能使用乘除法、for、while、if、else、switch、case等关键字及条件判断语句（A?B:C）

```
class Solution {
public:
    int Sum_Solution(int n) {
        int result = n;
        (n>0) && (result += Sum_Solution(n-1));
        return result;
    }
};
```

### 9写一个函数，求两个整数之和，要求在函数体内不得使用+、-、*、/四则运算符号。

异或^
1. 两个数取异或（相同为0，不相同为1）特性就是不进位的加法
2. 两个数取&左移1位确定进位数
3. num1 = num1^num2
4. num2 = (num1&num2)<<1;
5. 进位为0结束

```
class Solution {
public:
    int Add(int num1, int num2)
    {
        int sum,carryLShift;
        while(num2!=0){
            sum = num1^num2;
            carryLShift = (num1&num2)<<1;
            num1 = sum;
            num2 = carryLShift;
        }
        return num1;
    }
};
```

### 10.任意非负整数区间中1出现的次数 

1. 找出当前位、高位、低位
2. 判断当前位是0、1、大于1
3. 遍历个十百千位...

```
class Solution {
public:
    int NumberOf1Between1AndN_Solution(int n)
    {
        if( n<=0 ){
            return 0;
        }
       
        int count = 0;
        int digit = 1;   //个十百千..1.10  100  1000
        
        while(n/digit!=0){
        int CurNum = (n/digit)%10;  //数字的当前个十百千位
        int HightNum = n/(digit*10); //当前位前面的数字
        int LowNum = n % digit;   //当前位后面的数字
            
        if(CurNum == 0){
            count += HightNum * digit;
        }else if(CurNum == 1){
            count += HightNum*digit + LowNum +1;
        }else{
            count += digit*(HightNum +1);
             }
            digit *= 10;
        }
        
        return count;
    }
};
```

### 11.判断二进制数中表示1的个数

1.把一个整数减去1
2.再和原整数做与运算（整数的二进制有多少个1，就可以进行多少次这样的操作）
3.直到变为0结束

```
class Solution {
public:
     int  NumberOf1(int n) {
        int count = 0;
        while(n!= 0){
            ++count;
            n = n & (n - 1);
         }
        return count;
     }
};
```

















# 小技巧

n为奇数时, n&1为1
n为偶数时, n&1为0
n&1等效于  n%2==1

"n>> 1"===="n/2"

# 排序

```
//int PartSort(vector<int> &arr, int left,int right) {
//	int base = arr[right];
//	int baseIndex = right;
//	--right;
//	while (left < right) {
//		if (arr[left] >= base && arr[right] <=base) {
//			swap(arr,left++,right--);
//		
//		}
//		if (arr[left]< base) {
//			++left;
//		}
//		if (arr[right] > base) {
//			--right;
//		}
//		
//	}
//	swap(arr,left, baseIndex);
//	return left;
//}


//void quickSort(vector<int> &arr, int left, int right)
//{
//	if (left < right)
//	{
//		int pivot = arr[left];
//		int low = left, high = right;
//		while (low < high)
//		{
//			while (arr[high] >= pivot && low < high)
//				high--;
//			arr[low] = arr[high];
//
//			while (arr[low] <= pivot && low < high)
//				low++;
//			arr[high] = arr[low];
//		}
//		arr[low] = pivot;
//
//	}
//}










//////////////////////////////////////////////////////////////////////////////////////////////////////


//
//#include <iostream>
//#include <vector>
//#include <algorithm>
//#include <string>
//using namespace std;

/*

快速排序

1.任意找到序列的一个值作为基准
2.比基准小的数放到前面，比基准大的放到后面
3.递归对左右两个区间进行同样排序
*/

/*
int stPartition(vector<int> &arrI, int left, int right)
{
	int cur = left;
	int prev = left - 1;
	int key = arrI[right];
	while (cur < right)
	{
		if (arrI[cur] < key && ++prev != cur)
		{
			swap(arrI[cur], arrI[prev]);
		}
		++cur;
	}
	swap(arrI[++prev], arrI[right]);
	return prev;
}



void swap(vector<int> &arr, int i, int j) {
	int temp = arr[i];
	arr[i] = arr[j];
	arr[j] = temp;
}


vector<int> QuickSort(vector<int> &arrI, int left, int right) {
	if (left < right) {
		
		int MidIndex = stPartition(arrI, left, right);
		QuickSort(arrI, left, MidIndex-1 );
		QuickSort(arrI, MidIndex + 1,right);
	}
	return arrI;
}

int main() {

	vector<int> a = { 1,10,5,64,10,10,2,6,8,10 };
	vector<int> res;

	res = QuickSort(a,0,a.size()-1);

	for (int i = 0; i < res.size(); ++i) {
		cout << res[i] << " ";
	}
	cout << endl;
	system("pause");
	return 0;
}
*/


/////////////////////////////////////////////////////////////////////////////////////////////////////////

/*
堆排序

创建大根堆
堆排序
*/

/*
#include <iostream>
#include <vector>
#include <algorithm>
#include <string>
using namespace std;

void CreateHeap(int arr[], int root, int len) {
	int left = 2 * root + 1;//左子树的下标
	if (left < len) {
		int flag = left;   //记录一个最大值的下标
		int right = left + 1;
		if (right < len) {
			if (arr[flag]<arr[right]) {
				flag = right;
			}

		}
		if (arr[root]<arr[flag]) {
			swap(arr[root], arr[flag]); //交换父节点和比父节点大
			CreateHeap(arr, flag,len);  //从最大值的位置开始创建堆
		
		}
	}

}

void HeapSort(int arr[],int len) {
	for (int i = len / 2; i >= 0;--i) {     //从最后一个非叶子节点的父节点开始创建堆
		CreateHeap(arr, i, len);
	}

	for (int j = len - 1; j > 0; --j) {
		swap(arr[0], arr[j]);  //交换首尾位置，将最大值保存在位置最后
		CreateHeap(arr, 0, j);
	}
}

int  main() {
	int a[5] = { 34,3,45,7,3 };
	HeapSort(a, 5);
	for (int i = 0; i < 5;i++) {
		cout << a[i]<<" ";
	
	}
	system("pause");
	return 0;
}

*/

///////////////////////////////////////////////////////////////////////////////////////////
/*
归并排序
从中间分开
合并过程（定义一个临时数组用来存放归并后排序的值，定义两个指针，一个i指向前半部的起始位置，一个j指向后半部的起始位置
		num[i] <= num[j] 把小的放到临时数组里面
		num[i] >= num[j] 构成逆序对【mid-i+1】把小的放大临时数组里面
		还要判断前半部分i<mid  num[i] 放到临时数组中
		还要判断前半部分j<end  num[j] 放到临时数组中
		排序好的覆盖原来的数组
		）

*/

/*
#include <iostream>
#include <vector>
#include <algorithm>
#include <string>
using namespace std;
class Solution {
public:
	int count;
	int InversePairs(vector<int> nums) {
		if (nums.size() != 0) {
			//分治   划分整个数组
			divide(nums, 0, nums.size() - 1);
		}
		return count;
	}
	//分治思路
	void divide(vector<int> &nums, int start, int end) {
		if (start >= end) return;
		//取中间值
		int mid = start + (end - start) / 2;
		//递归左右两边数组   
		divide(nums, start, mid);
		divide(nums, mid + 1, end);
		//合并排序
		merge(nums, start, mid, end);
	}


//合并
	void merge(vector<int> &nums, int start, int mid, int end) {
		//定义临时数组
		vector<int> temp;
		int i = start, j = mid + 1, k = 0;
		//比较左右两边间隙，中间存在逆序对 【start....i.....mid】【mid+1.....j.....end】
		while (i <= mid && j <= end) {
			//若果此时i 的值比j的值小，他们之间不构成逆序对，把 最小的值放入临时数组中，并且指向i 的指针向后移动继续比较
			if (nums[i] <= nums[j]) {
				temp.push_back(nums[i++]);
			}
			else {
				//若果发现此时i 的值比j 的值大，他们构成逆序对，并且他们之间有 （mid - i + 1）对
				temp.push_back(nums[j++]);
				count = (count + mid - i + 1) % 1000000007;
			}
		}
		//判断前半部分 
		while (i <= mid) {
			temp.push_back(nums[i++]);
		}
		//判断后半部分
		while (j <= end) {
			temp.push_back(nums[j++]);
		}
		//排序好的覆盖原来的
		for (k; k<temp.size(); ++k) {
			nums[start + k] = temp[k];
			cout << nums[k] << " ";
		}
	}

};

int  main() {
	Solution so;
	vector<int> arr = { 8,4,5,7,1,3,6,2 };
	int res = 0;
	res = so.InversePairs(arr);

	system("pause");
	return 0;
}
*/

//不含重复字符 的最长子字符串
/*
滑动窗口，map 存下标

*/


#include <iostream>
#include <vector>
#include <algorithm>
#include <string>
#include <map>
using namespace std;
class Solution {
public:
	int lengthOfLongestSubstring(string s) {
		map<char, int> m;
		int ret = 0, l = 0, r = 0;
		while (r < s.size()) {
			if (m.find(s[r]) != m.end()) {
				l = max(l, m[s[r]] + 1);
			}
			m[s[r++]] = r;
			ret = max(r - l, ret);
		}
		return ret;
	}
};

/*
最多删除一个是不是回文串
*/
class Solution {
public:
	bool checkPalindrome(const string& s, int low, int high) {
		for (int i = low, j = high; i < j; ++i, --j) {
			if (s[i] != s[j]) {
				return false;
			}
		}
		return true;
	}

	bool validPalindrome(string s) {
		int low = 0, high = s.size() - 1;
		while (low < high) {
			char c1 = s[low], c2 = s[high];
			if (c1 == c2) {
				++low;
				--high;
			}
			else {
				return checkPalindrome(s, low, high - 1) || checkPalindrome(s, low + 1, high);
			}
		}
		return true;
	}
};


```


```
unsigned char* Test(void){
	unsigned char ch =0,i;
	char *str;

	for(i=0;i<=256;i++){
		strcpy(str,"hello");
	}
	return &ch;
}
```

strcpy函数原型
 char* strcpy( char _Dest, char const* _Str)



1. 从str copy 到dest 首先dest必须分配空间

char* str = new char[100];



2. ch 是一个局部变量，在函数结束就释放了，return &ch 会导致野指针。



```
数据类型                                     32                        64            取值范围
char                                        1                         1             -128-127
unsigned char                               1                         1             0-255
short int                                   2                         2
short short                                 2                         2
unsigned short                              2                         2  
int                                         4                         4
unsigned int                                4                         4
unsigned long                               4                         8
long long                                   8                         8
long int                                    4                         8
float                                       4                         4                            
double                                      8                         8
size_t                                      4                         8
```

3. unsigned char ch =0,i;   for(i=0;i<=256;i++)   char 0-255  i=0 i<=255  256导致数据类型溢出



char  str[] = "hello"  sizeof(str)  = 6;        strlen(str)  = 5 字符串的长度

char str[100]   sizeof(str)  = 100;

char str[5] = {'h','e','l','l','o'};          sizeof(str) = 5

char *p = "hello";       sizeof(p) = 4    一个指针

char *p[] = {"hello","world"};      sizeof(p) = 8  长度为2的字符串数组

int arr[100] = {0}     int  arr[100];       sizeof(arr) = 100*4



linux 文件权限



r :可读         4

w: 可写        2

x:可执行      1



```
-rwxr-xr--
```

一共10位  第一位是文件属性（文件、目录、块设备）    后面是3位一组

第一组：**属主权限位**         rwx             rwx  =  4+2+1  =7 

第二组：**属组权限位 **         r-x             4+0+1 = 5

第三组：**其他用户权限位 **     r--           4+0+0 = 4



文件权限为   754





**C和C++的struct的区别**

C++支持成员函数的定义   C只能是一些变量的集合体

C中的struct是没有权限设置的，C++增加了访问权限和class 一样



**memset 可以用来初始化类对象吗？**

memset 在对结构体变量赋值时使用。struct A a;  memset(&a,0,sizeof(a));

不可以。类对象初始化通过构造函数完成，为什么要使用memset? 如果类包含虚函数，则不能用 memset 来初始化类对象。每个包含虚函数的类对象都有一个指针指向虚函数表,该指针是被隐藏的,这个指针也是不可存取的,当进行memset操作时，这个指针的值也要被重写，只要一调用虚函数，程序便崩溃。不知道怎调用哪个函数了。



**加密算法 ** 

分为对称性加密算法和非对称性加密算法

**对称加密**（加解密相同的密匙） AES、DES、3DES

![image-20200924190618326](https://gitee.com/raylee-lilei/cdn/raw/master/image-20200924190618326.png)

**AES**使用128位分组块的分组加密算法，分组块和128、192或256位的密钥一起作为输入，对4×4的字节数组上进行操作

**DES**以64位为分组对数据加密，它的密钥长度是56位，加密解密用同一算法





**非对称加密 **      RSA、DSA、ECC

公开密钥加密算法（公匙和私匙） 

![image-20200924191014098](https://gitee.com/raylee-lilei/cdn/raw/master/image-20200924191014098.png)

![image-20200924191730599](https://gitee.com/raylee-lilei/cdn/raw/master/image-20200924191730599.png)



**RSA**两个大质数（素数）相乘十分容易，但是想要对其乘积进行因式分解却极其困难，因此可以将乘积公开作为加密密钥



**散列算法**

**MD5、SHA1、HMAC**

生成一串不可逆的密文

![image-20200924193226921](https://gitee.com/raylee-lilei/cdn/raw/master/image-20200924193226921.png)

![image-20200924193427101](https://gitee.com/raylee-lilei/cdn/raw/master/image-20200924193427101.png)



**https 加密过程**

![image-20200924194416511](https://gitee.com/raylee-lilei/cdn/raw/master/image-20200924194416511.png)

5和7的步骤是对称加密





