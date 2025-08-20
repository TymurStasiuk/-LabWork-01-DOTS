# -LabWork-01-DOTS

def main():
    n = int(input())
    arr = list(map(int, input().split()))

    first_half = sorted(arr[:n])
    second_half = sorted(arr[n:], reverse=True)

    result = first_half + second_half
    print(*result)


if __name__ == "__main__":
    main()
