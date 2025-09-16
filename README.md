# Form Survey Perokok dengan Emmet

Project ini menjelaskan bagaimana membuat sebuah form survey menggunakan **Emmet Abbreviation** agar lebih cepat dibanding menuliskan kode HTML secara manual.

---

## 📑 Struktur Form & Emmet

### 1. Input Nama

**Emmet:**

```emmet
div>label[for="name"]{Siapa nama anda?}+br+input[type="text" id="name" name="name"]
```

### 2. Input Umur

**Emmet:**

```emmet
ddiv>label[for="umur"]{Berapa umur anda?}+br+input[type="number" id="umur" name="umur"]
```

### 3. Pilih Jenis Kelamin

**Emmet:**

```emmet
div>label{Apa jenis kelamin anda?}+br+(label[for="laki_laki"]>input[type="radio" id="laki_laki" name="gender" value="laki_laki"]{Laki-laki})+label[for="perempuan"]>input[type="radio" id="perempuan" name="gender" value="perempuan"]{Perempuan}
```

### 4. Status Perokok

**Emmet:**

```emmet
div>label+br+(label[for="yesPerokok"]>input[type="radio" id="yesPerokok" name="isPerokok" value="ya"])+label[for="notPerokok"]>input[type="radio" id="notPerokok" name="isPerokok" value="tidak"]
```

### 5. Jenis Rokok

**Emmet:**

```emmet
div>label{Jika anda perokok, rokok apa yang anda pernah coba?}+br+((label>input[type="checkbox" name="jenisRokok"])+br)*4
```
