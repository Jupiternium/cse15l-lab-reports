## Lab Report 3 - Bugs and Commands (Week 5)

*Failure inducing input:* 
```@Test
public void secondTestReversed() {
    int[] input1 = {1, 2, 3, 4, 5};
    assertArrayEquals(new int[]{5, 4, 3, 2, 1}, ArrayExamples.reversed(input1));
}```

