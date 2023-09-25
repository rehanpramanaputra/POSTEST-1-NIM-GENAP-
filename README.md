```

#input nama,kelas,nim,dll.
nama = input("masukan nama:")
nim = input("masukan nim:")
kelas = input("masukan kelas:")
gender = input("masukan gender:")

#def untuk fungsi
def konversi_kg(berat_kg, satuan):
    if satuan == "gram":
        return berat_kg * 1000
    elif satuan == "ons":
        return berat_kg * 35.274
    elif satuan == "pound":
        return berat_kg * 2.20462
    else:
        return None

# input satuan
berat_kg = float(input("Masukkan berat dalam kilogram: "))
print("Pilih satuan konversi (gram/ons/pound): ")
satuan = input()

hasil_konversi = konversi_kg(berat_kg, satuan)

if hasil_konversi is not None:
    print(f"{berat_kg} kg sama dengan {hasil_konversi} {satuan}.")
else:
    print(f"Satuan {satuan} tidak dikenal.")
```
![flowchart massa drawio](https://github.com/rehanpramanaputra/POSTEST-1-NIM-GENAP-/assets/144860056/d65469f8-bcad-426c-b292-139ddeeb17cd)




![WhatsApp Image 2023-09-08 at 07 14 41-fotor-bg-remover-2023091313018](https://github.com/rehanpramanaputra/POSTEST-1-NIM-GENAP-/assets/144860056/76c1144e-cf16-4b09-820e-b2cb8e5be3ac)
