# Welcome!

This Java template lets you get started quickly with a simple one-page playground.

```java runnable
// { autofold
public class Main {
@Override  
    public void run() {  
        System.out.println("Thread has ended");  
    }  
public static void main(String[] args) {
// }

  Main ex = new Main();  
        Thread t1= new Thread(ex);  
        t1.start();  
        System.out.println("Hi");  
//{ autofold
}

}
//}
```

# Advanced usage

If you want a more complex example (external libraries, viewers...), use the [Advanced Java template](https://tech.io/select-repo/385)
