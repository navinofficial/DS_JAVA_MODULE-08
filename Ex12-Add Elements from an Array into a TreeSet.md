# Ex12 Add Elements from an Array into a TreeSet
## DATE: 18/11/25
## AIM:
To write a Java program that adds elements from an array into a TreeSet and displays the elements in sorted order.
## Algorithm

1. Start the program.

2. Initialize an array with integer elements.

3. Create an empty TreeSet.

4. Add all elements from the array into the TreeSet.

5. Display the elements of the TreeSet (which are automatically sorted).

6. Stop the program.
   

## Program:
```
Developed by: Navinkumar V
RegisterNumber:  212223230141
```
```
import java.util.*;

public class ArrayToTreeSet {
    public static void main(String[] args) {
        Integer[] arr = {50, 20, 40, 10, 30};

        TreeSet<Integer> set = new TreeSet<>(Arrays.asList(arr));

        System.out.println("Array elements: " + Arrays.toString(arr));
        System.out.println("TreeSet elements (sorted): " + set);
    }
}
```

## Output:

<img width="673" height="96" alt="image" src="https://github.com/user-attachments/assets/98543356-53ce-44ba-b146-a6452c9a0263" />


## Result:
The program successfully adds elements from an array into a TreeSet.
