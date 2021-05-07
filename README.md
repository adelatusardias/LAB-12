# LAB-12
SET
print("=" * 5, "CONTOH 1", "=" * 5)
Barang = set()

Barang.add("Soto")
Barang.add("Opor")
Barang.add("Gule")
Barang.add("Sate")
Barang.add("nasi")
Barang.add(12345)

print(Barang)
# print(sorted(Barang)) # Akan terjadi runtime Error di baris ini Karena data set Barang ada yang berisi interger (12345)
# print(Barang[2]) # Akan error karena tipedata set tidak meiikiki list
print("\n")
