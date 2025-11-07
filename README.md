# daily_update.py
import datetime
import statistics
import random

print("Daily GitHub activity - Day 23")

today = datetime.date.today()
data = [random.randint(10, 100) for _ in range(8)]
mean_value = round(statistics.mean(data), 2)
median_value = statistics.median(data)

print(f"Today's date: {today}")
print(f"Generated data: {data}")
print(f"Average value: {mean_value}")
print(f"Median value: {median_value}")
