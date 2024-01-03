# 404B Lesson 2 Class Exercise - Nested For Loop

## Instructions

### Split VS Code Window

You can drag `main.py` tab to the right side of the window to split the window into two panes. This will allow you to see the instructions and the code at the same time.

### Answering

You can answer the questions by writing your answers in the `main.py` file.

You can run the code by clicking the `Run` button on the top right corner of the editor.

The output will be shown in the `Terminal` tab at the bottom of the editor.

## Nested For-Loop Example

### Sample Code

```python
for row in range(6):
    print(f'row {row}: ', end='')
    
    for col in range(row):
        print(col, end='')
  
    print()
```

### Sample Output

```py
row 0: 
row 1: 0
row 2: 01
row 3: 012
row 4: 0123
row 5: 01234
```

## Questions

1. Write a program with nested for-loop to produce the following sequences:

    ```py
    0
    0 1
    0 1 2
    0 1 2 3
    0 1 2 3 4
    0 1 2 3 4 5
    0 1 2 3 4 5 6
    ```

2. Write a program with nested for-loop to produce the following sequences:

    ```py
    1
    1 2
    1 2 3
    1 2 3 4
    1 2 3 4 5
    1 2 3 4 5 6
    ```

3. Write a program with nested for-loop to produce the following sequences:

   Five 9s, 8s, 7s, 6s, 5s, 4s, 3s, 2s and 1s.

    ```py
    999998888877777666665555544444333332222211111
    ```

4. Write a program with nested for-loop to produce the following sequences:

   Nine 9s, eight 8s, seven 7s, six 6s, five 5s, four 4s, three 3s, two 2s and one 1.

    ```py
    999999999888888887777777666666555554444333221
    ```

5. Write a program with nested for-loop to produce the following sequences:

    ```py
    -----1
    ----333
    ---55555
    --7777777
    -999999999
    ```

   May replace the `-` with spaces.

6. Write a program with nested for-loop to produce the following sequences:

    ```py
        1
       121
      12321
     1234321
    123454321
    ```
