def rearrange_array(nums, n):
    x_elements = nums[:n]  # Elements from index 0 to n-1
    y_elements = nums[n:]  # Elements from index n to 2n-1
    
    # Interleave the elements from x_elements and y_elements
    result = [x for pair in zip(x_elements, y_elements) for x in pair]
    
    return result

# Example usage
nums = [2, 5, 1, 3, 4, 7]
n = 3
output = rearrange_array(nums, n)
print(output)  # Output: [2, 3, 5, 4, 1, 7]
