# Ex11 Convert HashSet to ArrayList in Java
## DATE: 18/11/25
## AIM:
To convert a collection of distinct integers stored in a HashSet into an ArrayList and display its contents.
## Algorithm
1. Start the program.
2. Create a HashSet and add distinct integer elements to it.
3. Use the ArrayList constructor to convert the HashSet into an ArrayList.
4. Display the elements of both the HashSet and the ArrayList.
5. Stop the program.
   

## Program:
```
Developed by: Navinkumar V
RegisterNumber:  212223230141
```
```

import java.util.*;

public class HashSetToArrayList {
    public static void main(String[] args) {
        HashSet<Integer> set = new HashSet<>();
        set.add(10);
        set.add(20);
        set.add(30);
        set.add(40);
        set.add(50);

        System.out.println("HashSet: " + set);

        ArrayList<Integer> list = new ArrayList<>(set);
        System.out.println("ArrayList: " + list);
    }
}
```

## Output:

<img width="489" height="114" alt="image" src="https://github.com/user-attachments/assets/bdb2ea7b-ccd7-4288-adc3-3e928a5ba365" />


## Result:
The program successfully converts a collection of distinct integers stored in a HashSet into an ArrayList
