# Write-a-Python-program-to-count-the-number-of-even-and-odd-numbers-from-a-series-of-numbers.
count_odd = 0
count_even = 0

for i in numbers:
    output = check_even(i)
    if output == "even number":
        count_even += 1
        
    else:
        count_odd += 1
        
print("no. of even numbers", count_even)
print("no. of odd numbers ",count_odd)
