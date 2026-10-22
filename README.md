# task-13-Numpy-Random-Sampling-
import numpy as np

numbers = np.random.randint(1, 100, size=10)
print(numbers)
random_numbers = np.random.rand(5)
print(random_numbers)
data = np.array([10, 20, 30, 40, 50, 60, 70, 80])
sample = np.random.choice(data, size=3, replace=False)

print("Original Array:", data)
print("Random Sample:", sample)
np.random.seed(42)
numbers1 = np.random.randint(1, 100, size=5)
print(numbers1)

np.random.seed(42)
numbers2 = np.random.randint(1, 100, size=5)
print(numbers2)
np.random.seed(42)
marks = np.random.randint(35, 101, size=10)

print("Student Marks:", marks)
print("Average:", np.mean(marks))
print("Highest:", np.max(marks))
print("Lowest:", np.min(marks))
