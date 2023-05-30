# 7.Object,Method
## Math.java
```
package com.javacode;

public class Math {
    int resutl;
    void add(int a,int b){
        resutl = a+b;
    }

    void getResutl(){
        System.out.println(resutl);
    }
}
```
## Main.java
```
public class Main {
    public static void main(String[] args) {
        Math math = new Math();
//        int res = math.add(1,2);
        math.add(1,2);
        math.getResutl();

    }
}
```
