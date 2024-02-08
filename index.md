
# Lab Report 3

## Part 1 - Bugs

The `testReverseInPlace2` method in the `ArrayExamples` class is buggy. 
Here is the test I made to create a failure-inducing input. 

```
@Test 
  public void testReverseInPlace2() {
    int[] input = { 2, 4, 5, 7, 8 };
    ArrayExamples.reverseInPlace(input);
    assertArrayEquals(new int[]{ 8, 7, 5, 4, 2 }, input);
  }
```

The `testReverseInPlace` in the `ArrayTests` file does not create a failure-inducing input. 

```
@Test 
  public void testReverseInPlace() {
    int[] input1 = { 3 };
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{ 3 }, input1);
  }
```

Here is the symptom of the `testReverseInPlace2` method. 
`Add some stuff here`

Here is the symptom of the `testReverseInPlace` method. 
`Add some more stuff here`

