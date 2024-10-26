# praktikum
Tugas praktikum bahasa pemrograman pertemuan 5-6 bahasa pemrograman 

"Membuat Kode Python Dari Flowchart Untuk Menentukan Bilangan Terbesar"

        max_value = 0

        while True:
        n = int(input("Enter a number(0 to stop):"))

        if n == 0:
        break 

        if n > max_value:
        max_value = n 

        print("The maximum value is:", max_value)

Penjelasan Mengenai Kode Python Diatas adalah untuk menemukan angka maksimum dari serangkaian angka. Berikut adalah penjelasan lebih lanjut:
1. Kode menginisialisai max_value ke 0
2. Kemudian kode memasuki loop dimana ia berulang kali meminta angka n
3. Jika n lebih besar dari max_value, kode memperbarui max_value
4. Saat memasukkan angka 0, loop akan berhenti beroperasi dan program mencetak nilai maksimum yang di tentukan.

"Membuat Kode Python Dari Flowchart Untuk Menentukan Bilangan Terbesar Dari 3 Bilangan Yang DiInputkan

    angka1 = int(input("Enter a number one:"))
    angka2 = int(input("Enter a number two:"))
    angka3 = int(input("Enter a number three:"))

        if angka1 > angka2 and angka1 > angka3:
            max = angka1
        elif angka2 > angka3:
            max = angka2
        else:
            max = angka3
        print("The Maximum is:", max)
        
Penjelasan Mengenai Kode Python Diatas adalah untuk menentukan nilai terbesar dari 3 bilangan yang di input. Berikut adalah penjelasan lebih lanjut:
1. Memasukkan tiga angka. Angka 1, angka 2, angka 3 dan menyimpannya sebagai bilangan bulat
2. Jika angka1 lebih besar dari angka2 dan angka1 lebih besar dari angka3 maka nilai maksimalnya adalah angka1
3. Jika angka2 yang lebih besar dari angka3 maka nilai maksimalnya adalah angka2
4. Jika tidak maka nilai maksimalnya adalah angka3


