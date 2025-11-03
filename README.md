def fibonacci_sum(N):
    a, b = 0, 1
    total = 0
    for _ in range(n):
        total += a
        a, b = b, a + b
    return total

if __name__ == "__main__":
    count = 10
    print(f"Sum of first {count} Fibonacci numbers: {fibonacci_sum(count)}")

