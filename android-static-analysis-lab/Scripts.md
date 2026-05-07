def byte_array_to_text(byte_list):
    result = ''
    for num in byte_list:
        if 0 <= num <= 255:
            result += chr(num)
        elif -128 <= num < 0:
            result += chr(num + 256)  # handle signed bytes
    return result


# Example
data = [116, 99, 112, 58, 47, 47, 49, 57, 50]
print(byte_array_to_text(data))