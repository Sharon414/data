# data
import csv
file_path = '/Users/sharonchoi/Desktop/tourism_resource_dataset.csv'
with open(file_path, mode='r') as file:
    reader = csv.reader(file)
    for row in reader:
        print(row)
import sys
print(sys.executable)
/Library/Frameworks/Python.framework/Versions/3.12/bin/python3.12
