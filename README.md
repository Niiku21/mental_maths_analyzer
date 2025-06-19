# mental_maths_analyzer
import numpy as np
user_input=input('23,10,41,12,53,23')
numbers=[float(num.strip()) for num in user_input.split(",")]
data=np.array(numbers)
mean=np.mean
median=np.median
maximum=np.maximum
minimum=np.minimum
std_dev=np.std
print(f'Mental maths analysis results')
print(f'mean')
print(f'median')
print(f'maximum')
print(f'minimum')
print(f'Standard deviation:{std_dev}')
