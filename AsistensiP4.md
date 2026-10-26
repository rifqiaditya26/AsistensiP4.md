
## TUGAS PRAKTIKUM: Tantangan Wajib

### 1. Update Harga Barang 

void updateHarga(Barang *b, int hargaBaru) {
    int hargaLama = b->harga;
    b->harga = hargaBaru;

}

### 2. Update Nama Barang 


#include <string.h>

void updateNama(Barang *b, char namaBaru[]) {
    char namaLama[50];
    strcpy(namaLama, b->nama);
    strcpy(b->nama, namaBaru);
    
}

### 3. Tukar Poin = Diskon 
    TAMBAH BLOK KODE INI SETELAH TOTAL AWAL DITENTUKAN

        if (m != NULL && m->poin >= 1000) {
            int diskon = total * 10 / 100;
            total -= diskon;
            m->poin -= 1000;
        }

