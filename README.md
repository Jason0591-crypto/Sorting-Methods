# Sorting-Methods
Different sorting methods

# Bubble Sort
# Create the variables
j = 0
k = 99

# Create the list of numbers going to be sorted
list1 = r.sample(range(0, 1001), 100)
print(list1)

# Sort the numbers using two while loops
while k > 0:
    j = 0
    while j < k:
        if list1[j] >= list1[j + 1]:
            temp = list1[j]
            list1[j] = list1[j + 1]
            list1[j + 1] = temp
        j = j + 1
    k = k - 1

# Print out the sorted numbers
print(list1)
