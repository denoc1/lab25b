# Working with ArrayLists

Write the following methods.  The documentation is included below.  
I will write the tester code for the driver class to test your methods, so be sure to name your methods exactly as described in the instructions below.  Be sure to test your code thoroughly, including edge cases.

## Method: `printReverse`
```java
public static void printReverse(ArrayList<Boolean> arrList)
```
**Description**: Prints an ArrayList of Booleans in reverse order, one item per line.
- **Precondition**: `arrList` is not `null`.
- **Postcondition**: The elements of `arrList` are printed in reverse order, one per line.

For example: if the original ArrayList *passed to your method as an argument containing: “true, false, false”, the method would print 

       false
       false
       true


## Method: `findLargestNum`
```java
public static Double findLargestNum(ArrayList<Double> arrList)
```
**Description**: Searches an ArrayList of Double and returns the largest element.
- **Precondition**: `arrList` is not `null` and contains at least one element.
- **Postcondition**: Returns the largest Double in `arrList`.

## Method: `findLargestIndex`
```java
public static int findLargestIndex(ArrayList<Double> arrList)
```
**Description**: Searches an ArrayList of Double and returns the first index of the largest element.
- **Precondition**: `arrList` is not `null` and contains at least one element.
- **Postcondition**: Returns the index of the largest Double in `arrList`.  If there is more than one occurrence, the index of the first occurrence is returned.

## Method: `findSmallestNum`
```java
public static Double findSmallestNum(ArrayList<Double> arrList)
```
**Description**: Searches an ArrayList of Double and returns the smallest element.
- **Precondition**: `arrList` is not `null` and contains at least one element.
- **Postcondition**: Returns the smallest Double in `arrList`.

## Method: `searchForNum`
```java
public static int searchForNum(ArrayList<Integer> arrList, int num)
```
**Description**: Returns the index of the first occurrence of `num` in an ArrayList of Integers.
- **Precondition**: `arrList` is not `null`.
- **Postcondition**: Returns the index of `num` or `-1` if `num` is not found.

    Example:  If the ArrayList contains {3, 4, 5, 6, 5}, and the value being          searced for is 5, your method would return 2.  If the value being searched        for is 7, your method would return a -1 because 7 is not present in this          ArrayList.
## Method: `compareLists`
```java
public static boolean compareLists(ArrayList<Integer> arrList1, ArrayList<Integer> arrList2)
```
**Description**: Compares two ArrayLists of Integers for equality in content and order.
- **Precondition**: `arrList1` and `arrList2` are not `null` and are of the same length.
- **Postcondition**: Returns `true` if both lists are identical; otherwise, `false`.

## Method: `sorted`
```java
public static boolean sorted(ArrayList<Integer> arrList)
```
**Description**: Checks if an ArrayList of Integers is sorted in ascending order.
- **Precondition**: `arrList` is not `null`.
- **Postcondition**: Returns `true` if `arrList` is sorted; otherwise, `false`.

## Method: `removeOdds`
```java
public static void removeOdds(ArrayList<Integer> arrList)
```
**Description**: Removes all odd integers from an ArrayList of Integers.
- **Precondition**: `arrList` is not `null`.
- **Postcondition**: `arrList` contains only even integers.

     For example:  if the array list was [4, 5, 6, 7, 10], the result in the            ArrayLIst after this method should be [4, 6, 10].
     Another example [3, 5, 6, 7, 10] woud be changed to  [6, 10}


## Method: `swap`
```java
public static void swap(ArrayList<Integer> arrList)
```
**Description**: Swaps the first and last elements of an ArrayList of Integer.
- **Precondition**: `arrList` is not `null` and contains at least two elements.
- **Postcondition**: The first and last elements of `arrList` are swapped.

## Method: `removeConsecutiveDups`
```java
public static void removeConsecutiveDups(ArrayList<Integer> arrList)
```
**Description**: Removes consecutive duplicate elements in an ArrayList of Integers.
- **Precondition**: `arrList` is not `null`.
- **Postcondition**: Consecutive duplicates in `arrList` are removed, leaving only one occurrence.

    Example:  Example:  [5, 4, 4, 4, 3, 3, 2] ->  [5, 4, 3, 2]
    Example:  [5, 4, 5, 3, 3] ->  [5, 4, 5, 3]
     Note that in the latter example, the second 5 was not removed because the 5s      were not consecutive.


## Method: `removeLargeSmall`
```java
public static void removeLargeSmall(ArrayList<Double> arrList)
```
**Description**: Removes all occurrences of the largest and smallest elements from an ArrayList of Doubles.
- **Precondition**: `arrList` is not `null`
- **Postcondition**: All occurrences of the largest and smallest elements are removed from `arrList`.

## Bonus Method 1: `moveNegsBack`
```java
public static void moveNegsBack(ArrayList<Integer> arrList)
```
**Description**: Moves all negative numbers to the back of an ArrayList of Integers, preserving order.
- **Precondition**: `arrList` is not `null`.
- **Postcondition**: All negative numbers are moved to the end of `arrList`.

## Bonus Method 2: `shuffle`
```java
public static void shuffle(ArrayList<Integer> arrList)
```
**Description**: Shuffles an ArrayList of Integers using the `Collections` class.  
- **Precondition**: `arrList` is not `null`.
- **Postcondition**: `arrList` is shuffled randomly.
Note: This is easy, just requires some research.
