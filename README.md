# Write-a-Python-program-to-print-all-unique-values-in-a-dictionary.-Sample-Data-


[{"V":"S001"}, {"V": "S002"}, {"VI": "S001"}, {"VI": "S005"}, {"VII":"S005"},
{"V":"S009"},{"VIII":"S007"}]
Expected Output : Unique Values: {'S005', 'S002', 'S007', 'S001', 'S009'}
Ans.
data = [{"V":"S001"}, {"V": "S002"}, {"VI": "S001"}, {"VI": "S005"}, {"VII":"S005"}, 
{"V":"S009"},{"VIII":"S007"}]
unique_values = set()
for d in data:
 for value in d.values():
 unique_values.add(value)
print("Unique Values:", unique_values)
