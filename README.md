# Solve-Me-First
hackerrank-Solve-Me-First




<img width="931" alt="Ekran Resmi 2022-05-19 16 54 12" src="https://user-images.githubusercontent.com/105243448/169310477-6ea06b6c-1cb7-4a80-9330-826fec8b330a.png">








```
using System;
using System.Collections.Generic;
using System.IO;
class Solution {

    static int solveMeFirst(int a, int b) { 
      return a+b;
      
    }

    static void Main(String[] args) {
        int val1 = Convert.ToInt32(Console.ReadLine());
        int val2 = Convert.ToInt32(Console.ReadLine());
        int sum = solveMeFirst(val1,val2);
        Console.WriteLine(sum);
    }
}  

```
