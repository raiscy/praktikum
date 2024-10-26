# praktikum
tugas praktikum bahasa pemrograman pertemuan 6 bahasa pemrograman 

"Membuat Kode Python Dari Flowchart"

max_value = 0

while True:
    n = int(input("Enter a number(0 to stop):"))

    if n == 0:
        break 

    if n > max_value:
        max_value = n 

print("The maximum value is:", max_value)
