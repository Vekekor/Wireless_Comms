import math

def hamming_bound(n, k, t):

    size = 0

    for i in range(t+1):
        size += math.comb(n, i)
    bound = 2**(n - k)
    if size <= bound:
        print(f"The code satisfies the Hamming bound: {size} <= {bound}")
    else:
        print(f"The code does NOT satisfy the Hamming bound: {size} > {bound}")

    return size, bound

n = 13  
k = 5  
t = 3 
size, bound = hamming_bound(n, k, t)

print(f"Sphere size: {size}")
print(f"2^(n-k) bound: {bound}")
