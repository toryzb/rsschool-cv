# Viktoryia Zubovich

## Contact information:

Phone: +375 29 313 75 18  
E-mail: tory.zb@gmail.com  
Telegram: @ToryZB  

## About me:

I worked as a security system design engineer for 5 years. Then for 3 years I worked as a site administrator. Now, I want to change direction and further develop myself. I am interested in areas where I could work with programming languages, mathematics.
Stress resistance, responsibility, time management, attention to detail, empathy.

## Skills:

* Java (basic)
* Python (basic)
* HTML and CSS (basic)
* IntelliJ IDEA
* Adobe Photoshop

## Code example:
Create a function combos, that accepts a single positive integer num (30 > num > 0) and returns an array of arrays of positive integers that sum to num [task link](https://www.codewars.com/kata/555b1890a75b930e63000023/python).

```
def combos(n):
    if n == 0:
        return [[]]
    elif n == 1:
        return [[1]]
    else:
        arr = []
        arr.append([n])
        for i in range(1, n):
            for k in combos(n-i):
                k.append(i)
                j = sorted(k)
                arr.append(j)
    res = []
    for i in arr:
        if i not in res:
            res.append(i)

    return res
```

## Education:
* University: Belarusian State University of Informatics and Radioelectronics
* Java programming course (Institute IBA, 2021)
* Python programming course (udemy, by muself)
* Language application development hackathon Python, IBA Institute, 2021

## Languages:
* Russian - Native
* Belorusian - Native
* English: English Language Course Pre-Intermadiate/strong waystage(A2+) in Institute IBA, B1 Intermediate (according to the online test at EFset Logo www.efset.org). I use application in smartphone (Duolingo) every day and read books in origion.