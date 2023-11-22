#buat daftar angka
daftar_angka = [222, 333, 666, 999]

#cetak daftar_angka
print("Daftar empat dari tiga digit angka:")
for angka in daftar_angka:
    print(angka)

#input tiga nomor digit
input_user = input("Masukkan tiga nomor digit, pisahkan dengan spasi: ")
nomor_pengguna = [int(n) for n in input_user.split()]

#mengecek nomor ada di daftar atau tidak
for nomor in nomor_pengguna:
    if nomor in daftar_angka:
        posisi = daftar_angka.index(nomor) + 1
        print(f"Nomor {nomor} ditemukan pada posisi {posisi} dalam daftar.")
    else:
        print(f"Nomor {nomor} tidak ada dalam daftar.")
