```tefcha

# Write pseudo code here

if morning
  hello
end

```
```mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
```
```tefcha
sm1 = dice_sum()
if (sm1 == 7 or sm1 == 11) 
    return "win"
elif (sm1 == 2 or sm1 == 3 or sm1 == 12)
    return "loss"
else  
    sm2 = dice_sum()
    while (sm2 != 7 or sm2 !=sm1)
        if sm2 == sm1
            return "win"
        elif sm2 == 7
            return "loss"
        else
            sm2 = dice_sum()
end
```
```tefcha
# This is a example.
# NOTE:
#   The line starts with "#" is comment.
#   "\n" is newline.

Start\nFizzBuzz!
i = 1

while i <= 100
  if i % 15 == 0
    print("FizzBuzz")
  elif i % 3 == 0
    print("Fizz")
  elif i % 5 == 0
    print("Buzz")
  else
    print(i)
  i = i + 1
End
```