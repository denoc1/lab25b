# lab25b


```markdown
# Method Descriptions

Write the following methods. Include documentation of preconditions and postconditions.
I will write the tester code for the driver class, so be sure to name your methods exactly as described
in the instructions below. You will not be provided the tester code. You must be sure to test all cases yourself.

 1. public static void printReverse(ArrayList<Boolean> arrList)
        /*
        * Prints an ArrayList of Booleans in reverse order, one item per line. 
        * So, if the original ArrayList passed to your method as an argument contains: 
        * "true, false, false", the method would print:
        *
        * false
        * false
        * true
        */


  2. public static Double findLargestNum(ArrayList<Double> arrList)
       
        /*
        * Search an ArrayList of Double and return the largest element found in the ArrayList.
        */
    

 3. public static int findLargestIndex(ArrayList<Double> arrList)

        /*
        * Search an ArrayList of Double and return the index of the largest element found in the ArrayList.
        */


 4. public static int searchForNum(ArrayList<Integer> arrList, int num)

        /*
        * Take an ArrayList of Integers and a value as two arguments (parameters) to your method. 
        * Return the index of the first location of the value inside the ArrayList. 
        * If the ArrayList does not contain the value, return -1.
        *
        * Example: If the ArrayList contains {3, 4, 5, 6, 5}, and the value being searched for is 5, 
        * your method would return 2. If the value being searched for is 7, your method would return -1 
        * because 7 is not present in this ArrayList.
        */

 5. public static boolean compareLists(ArrayList<Integer> arrList1, ArrayList<Integer> arrList2)

        /*
        * Compare two ArrayLists of Integers that are known to be of the same length (precondition). 
        * Return true if they have the same contents in the same order, return false otherwise.
        */


 6. `public static boolean sorted(ArrayList<Integer> arrList)

        /*
        * Look at the elements of an ArrayList of integers. Return true if the ArrayList is sorted from 
        * smallest to largest. Return false if not sorted.
        */


 7. public static void removeOdds(ArrayList<Integer> arrList)

          /*
          * Create a method that removes all the odd integers from an ArrayList of Integers.
          *
          * For example: if the array list was [4, 5, 6, 7, 10], the result in the ArrayList after 
          * this method should be [4, 6, 10].
          * Example: [3, 5, 6, 7, 10] -> [6, 10]
          */


 8. public static void swap(ArrayList<Integer> arrList)

          /*
          * Swap the first and last elements of an ArrayList of Integer.
          */


 9. public static void removeConsecutiveDups(ArrayList<Integer> arrList)

          /*
          * If two or more consecutive elements of an ArrayList are the same Integer, 
          * remove all but the one occurrence. Do not disturb the relative positioning of the other elements.
          *
          * Example: [5, 4, 4, 4, 3, 3, 2] -> [5, 4, 3, 2]
          * Example: [5, 4, 5, 3, 3] -> [5, 4, 5, 3]
          * Note that in the latter example, the second 5 was not removed because the 5s were not consecutive.
          */

### 10. public static void removeLargeSmall(ArrayList<Double> arrList)

          /*
          * In an ArrayList of Doubles, remove the largest and smallest elements. 
          * (You can assume the elements in the ArrayList will all be unique.)
          */


## Bonus Methods

### Bonus 1: `public static void moveNegsBack(ArrayList<Integer> arrList)`
```java
/*
* Move all the negative numbers in an ArrayList of integers to the back of the ArrayList, 
* preserving the original order.
* Example: [3, 4, -2, -9, 5, -3, 7, 1] -> [3, 4, 5, 7, 1, -2, -9, -3]
*/
```

### Bonus 2: `public static void shuffle(ArrayList<Integer> arrList)`
```java
/*
* Use the Collections class in Java to shuffle an ArrayList of integers.
*/
```
