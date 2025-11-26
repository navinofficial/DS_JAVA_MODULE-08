# Ex15 Value Existence Check in a TreeMap
## DATE: 18/11/25
## AIM:
To write a Java program that checks whether a given value exists in a TreeMap.

## Algorithm
1. Start the program.
2. Create a TreeMap and insert key–value pairs.
3. Use the containsValue() method to check if a specific value exists in the map.
4. Display whether the value is found or not.
5. Stop the program.
   

## Program:
```
Developed by: Navinkumar V
RegisterNumber:  212223230141
```
```

import java.util.*;

public class TreeMapValueCheck {
    public static void main(String[] args) {
        TreeMap<Integer, String> map = new TreeMap<>();
        map.put(1, "Apple");
        map.put(2, "Banana");
        map.put(3, "Cherry");
        map.put(4, "Mango");

        System.out.println("TreeMap: " + map);
        String valueToCheck = "Banana";

        if (map.containsValue(valueToCheck))
            System.out.println("The value '" + valueToCheck + "' exists in the TreeMap.");
        else
            System.out.println("The value '" + valueToCheck + "' does not exist in the TreeMap.");
    }
}
```
## Output:

<img width="852" height="108" alt="image" src="https://github.com/user-attachments/assets/fa3dd6c0-d8cb-4513-9bac-f386c55a2611" />


## Result:
Thus, the program successfully checks whether a specified value exists in a TreeMap using the containsValue() method.
