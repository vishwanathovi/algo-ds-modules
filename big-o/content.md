# Big-O

What exactly is O(log(n)) complexity?

[Log(n) - definition](https://hackernoon.com/what-does-the-time-complexity-o-log-n-actually-mean-45f94bb5bfbf)

[Logarithm - Wiki page](https://en.wikipedia.org/wiki/Logarithm)

<hr/>

- Rule Book for Big(O) calculation -
    Rule 1: Always worst Case

    Rule 2: Remove Constants

    Rule 3: Different inputs should have different variables. O(a+b). A
    and B arrays nested would be O(a*b) + for steps in order * for nested steps

    Rule 4: Drop Non-dominant terms

<hr/>

### Find the BigO of the below codes

#### Problem 1:
```
void function(int n)
{
    int count = 0;
    for (int i=n/2; i<=n; i++)
        for (int j=1; j<=n; j = 2 * j)
            for (int k=1; k<=n; k = k * 2)
                count++;
}
```

#### Problem 2:
```
void function(int n)
{
    int count = 0;
    for (int i=n/2; i<=n; i++)

        // Executes O(Log n) times
        for (int j=1; j<=n; j = 2 * j)

            // Executes O(Log n) times
            for (int k=1; k<=n; k = k * 2)
                count++;
}
```

#### Problem 3:
```
void function(int n)
{
    int count = 0;

    // outer loop executes n/2 times
    for (int i=n/2; i<=n; i++)

        // middle loop executes  n/2 times
        for (int j=1; j+n/2<=n; j = j++)

            // inner loop executes logn times
            for (int k=1; k<=n; k = k * 2)
                count++;
}
```

#### Problem 4:
```
void function(int n)
{
    int count = 0;
    for (int i=0; i<n; i++)
        for (int j=i; j< i*i; j++)
            if (j%i == 0)
            {
                for (int k=0; k<j; k++)
                    printf("*");
            }
}
```

<hr/>
