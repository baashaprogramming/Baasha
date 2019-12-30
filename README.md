# Baasha
This is the official github repository of the Baasha programming language
Baasha is a general purpose programming language written in c++
Baasha is simple yet dynamic. 
It ws created as an effort to create a simple language for people to learn as their first programming language.
In an experiment conducted by our team, it was found that those who learned Baasha as their first language found it easier to learn python, c, c++ etc.

Baasha has a terminal to basic code. You can also write more complex Baasha code in a text file, save it in the Baasha folder and run:
run("example.txt") 
in the terminal.

Variables:

The format for writing variables is
vr_ variable_name = string/num
ex. vr_ a = 7
or  vr_ b = "hello world"

In baasha, strings are written in double quotations "" and '' is considered and illegal character.

Comments:
Comments are written with #
ex. #hello
    output:
    0

Multiline comments

A simple "hello world" program in baasha:
out_bsh("hello world")
output:
hello world
0
or
out_ret("hello world")
output:
"hello world"
0

Math operations +, -, /, *, ^ are supported in baasha
2+2
output:
4

Another program:
vr_ a = 5
vr_ b = 4
a+b
output:
9

Functions:
For functions we have -> which is a pair of - and >
ex. func add(a, b) -> a + b
    add(1,1)
    output:
    2
ex. vr_ a = 55
    vr_ b = 45
    func add(c, d) -> c + d
    out_bsh(add(a, b))
    output:
    100

For loops:
ex. for i = 0 to 5 then
        out_bsh("hello world")
    end
    output:
    hello world
    hello world
    hello world
    hello world
    hello world
    0
ex. func er(pre) -> prefix + er
    for i = 0 to 5 then
        out_bsh(er(wag))
    end
    output:
    wager
    wager
    wager
    wager
    wager

While statement:
ex. vr_ a = 7
    while true then a = 70
    out_bsh(a)
    output:
    70   

If and Else statements:
ex. vr_ a = 10
    if a >= 5 then 5 else 10
    output:
    5
ex. vr_ a = 2
    if a >= 5 then 5 else 10
    output:
    10

List:
ex. [1, 2, 3]
    output:
    [1, 2, 3]
ex. [1, 2, 3] + 4
    output:
    [1, 2, 3, 4]
ex. [1, 2, 3] * [3, 4, 5]
    output:
    [1, 2, 3, 3, 4, 5]

Pi:
ex. mth_pi
    output:
    3.141592653589793

Input:
ex. vr_ a = input(a:)
    out_bsh(a)
in. a: 7
    output:
    7
ex. vr_a = input(a:)/2
    out_bsh(a)
in. a: 7
    output:
    3.5
ex. vr_ str = input_int()
in. hello world
    output:
    'hello world' must be an integer. Try again!

Clear:
Typing clear() in terminal clears current terminal history

Append:
ex. vr_ list = [1, 2, 3]
    append(list, 4)
    output: 
    [1, 2, 3, 4]

Pop:
ex. vr_ list = [1, 2, 3, 4]
    pop(list, 3)
    out_bsh(list)
    output:
    [1, 2, 3]

Checking if input is string:
ex. is_str("hello")
    output:
    1
ex. is_str("23")
    output:
    0
Checking if input is number:
ex. is_num("23")
    output:
    1
ex. is_num("hello")
    output:
    0
Multi-line statements:
ex. 1+2; 3+4
    output:
    [3, 7]

Continue and Break:
ex. vr_ a = []
    for i = 0 to 10 then
        if i = 4 then continue 
        elif i = 8 then break
    vr_ a = a + 1
    out_bsh(a)
    end
    output:
    [1, 2, 3, 4, 5, 6, 7]

     

    













