# Tugas-Pertemuan-ke-9
###

    list_a = [10, 20, 30, 40, 50]
    print(list_a)

# Akses
    print(list_a[2], "Adalah nilai elemen ketiga")

    print(list_a[2:5])

    print(list_a[-1], "elemen pertama dari sebelah kanan")

# Ubah
    list_a[3] = list_a[1]
    print(list_a[3])

    print(list_a[3:5])

# Tambah
    list_b = list_a[1:3]
    print(list_b)

    list_b.append("Hello")
    print(list_b)

    list_b += 30, 20
    print(list_b)

    list_b += list_a
    print(list_b)
