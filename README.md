# 6.if.while,switch,for

```
int x=8;
        int y=18;
        int z=11;

        if(x>y && x>z){
            System.out.println(x);
        } else if (y>x && y>z) {
            System.out.println(y);
        }else {
            System.out.println(z);
        }

        if(true || false){
            System.out.println(true);
        }

        int n =7;

        switch (n){
            case 7:
                System.out.println("seven");
            case 8:
                System.out.println("eight");
        }

        while (n <= 10){
            System.out.println(n);
            n++;
        }
        n=11;
        do{
            System.out.println(n);
            n++;
        }while (n <= 10);

        for(int i=0;i<5;i++){
            System.out.println(i);
        }
```
