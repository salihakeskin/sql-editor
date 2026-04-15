<h1 style='color: #000000;text-align: left;margin-bottom: 0.21cm;background: transparent;font-family: "Liberation Serif", sans-serif;font-size:32px;font-weight: bold;'><span face="Liberation Serif, serif"><span size="3" style="font-size:16px;"><strong>O&nbsp;</strong></span>
        <font size="3" style="font-size:16px;"><strong>VERİTABANI Y&Ouml;NETİM SİSTEMLERİ: VİZE TAM HAZIRLIK REHBERİ</strong></font>
    </span></h1>
<h2 style='color: #000000;text-align: left;margin-top: 0.35cm;margin-bottom: 0.21cm;background: transparent;font-family: "Liberation Serif", sans-serif;font-size:24px;font-weight: bold;'><span face="Liberation Serif, serif">
        <font size="2" style="font-size:13px;"><strong>1. B&Ouml;L&Uuml;M: TEMEL KAVRAMLAR VE TASARIM</strong></font>
    </span></h2>
<ul>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">Data (Veri) vs. Information (Bilgi): Veri işlenmemiş ham ger&ccedil;ektir; Bilgi ise verinin anlamlı, işlenmiş ve karar vermeye yardımcı şeklidir.</span></span></p>
    </li>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">Database (Veritabanı): Birbiriyle ilişkili verilerin sistematik bir şekilde depolandığı yapıdır.</span></span></p>
    </li>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">Primary Key - PK (Birincil Anahtar): Bir tablodaki her satırı benzersiz (unique) kılan s&uuml;tundur. Asla NULL (boş) olamaz. (&Ouml;rn: &Ouml;ğrenci No, T.C. Kimlik No).</span></span></p>
    </li>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">Foreign Key - FK (Yabancı Anahtar): Bir tablodaki veriyi başka bir tabloyla ilişkilendiren s&uuml;tundur. İlişkisel veritabanının kalbidir.</span></span></p>
    </li>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">NULL Değeri: &quot;Sıfır&quot; veya &quot;Boşluk&quot; değildir; verinin hen&uuml;z bilinmediği veya atanmadığı anlamına gelir.</span></span></p>
    </li>
</ul>
<p style="color: #000000;line-height: 100%;text-align: left;margin-bottom: 0.5cm;background: transparent;font-weight: normal;border-top: none;border-bottom: 1px double #808080;border-left: none;border-right: none;padding: 0cm;"><br>&nbsp;</p>
<h2 style='color: #000000;text-align: left;margin-top: 0.35cm;margin-bottom: 0.21cm;background: transparent;font-family: "Liberation Serif", sans-serif;font-size:24px;font-weight: bold;'><span face="Liberation Serif, serif"><span size="2" style="font-size:13px;"><strong>2.</strong><span style="font-weight: normal;"> </span></span>
        <font size="2" style="font-size:13px;"><strong>B&Ouml;L&Uuml;M: SQL KOMUT GRUPLARI</strong></font>
    </span></h2>
<ol>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">DDL (Data Definition Language - Veri Tanımlama): Yapı ile ilgilenir.</span></span></p>
        <ul>
            <li>
                <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">CREATE</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;">: Tablo/Veritabanı oluşturur.</span></span></p>
                <img width="1198" height="199" alt="image" src="https://github.com/user-attachments/assets/82deb8f4-34b3-40a6-88f7-05b5902f7497" />
            </li>
      </ul>
    </li>
</ol>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;font-weight: normal;margin-left: 2.5cm;text-indent: -0.5cm;'><br>&nbsp;</p>
<ol>
    <ul>
        <li>
            <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">ALTER</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;">: Tablo yapısını g&uuml;nceller (S&uuml;tun ekleme/silme).</span></span></p>
            <img width="991" height="171" alt="image" src="https://github.com/user-attachments/assets/c5de3a1d-f8ec-4ef6-bd14-34068a256007" />
        </li>
    </ul>
</ol>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;font-weight: normal;margin-left: 2.5cm;text-indent: -0.5cm;'><br>&nbsp;</p>
<ol>
    <ul>
        <li>
            <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">DROP</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;">: Tabloyu veya veritabanını tamamen siler. (DROP TABLE table_name)</span></span></p>
        </li>
    </ul>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">DML (Data Manipulation Language - Veri İşleme): Veriyle ilgilenir.</span></span></p>
        <ul>
            <li>
                <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">SELECT</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;">: Veri &ccedil;eker.</span></span></p>
                <img width="1147" height="118" alt="image" src="https://github.com/user-attachments/assets/c5201a5f-5fdb-4d49-895e-86ea48027d4b" />
            </li>
        </ul>
    </li>
</ol>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;margin-left: 2.5cm;text-indent: -0.5cm;'><br></p>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;font-weight: normal;margin-left: 2.5cm;text-indent: -0.5cm;'><br>&nbsp;</p>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;font-weight: normal;margin-left: 2.5cm;text-indent: -0.5cm;'><br>&nbsp;</p>
<ul>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">INSERT</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;">: Yeni veri ekler.</span></span></p>
        <img width="1291" height="232" alt="image" src="https://github.com/user-attachments/assets/0ee42d92-eff6-40c8-a0b7-b3ceb79a5201" />
    </li>
</ul>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;font-weight: normal;margin-left: 3.3cm;text-indent: -1.3cm;'><br>&nbsp;</p>
<ol>
    <ul>
        <li>
            <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">UPDATE</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;">: Mevcut veriyi g&uuml;nceller.</span></span></p>
          <img width="1174" height="113" alt="image" src="https://github.com/user-attachments/assets/77da64a2-522b-4770-a615-11c96f4bd824" />
        </li>
    </ul>
</ol>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;font-weight: normal;'><br>&nbsp;</p>
<ol>
    <ul>
        <li>
            <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">DELETE</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;">: Veriyi siler. (Where ile kullanılması kritiktir. Aksi durumda tablodaki t&uuml;m verileri siler. )</span></span></p>
                  <img width="877" height="84" alt="image" src="https://github.com/user-attachments/assets/282de9dd-6acd-481b-9002-074d6d76591c" />
        </li>
    </ul>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">DCL (Data Control Language - Veri Kontrol): G&uuml;venlik/Yetki ile ilgilenir.</span></span></p>
        <ul>
            <li>
                <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">GRANT</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;">: Yetki verir.</span></span></p>
            </li>
            <li>
                <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">REVOKE</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;">: Yetkiyi geri alır.</span></span></p>
            </li>
        </ul>
    </li>
</ol>
<p style="color: #000000;line-height: 100%;text-align: left;margin-bottom: 0.5cm;background: transparent;font-weight: normal;border-top: none;border-bottom: 1px double #808080;border-left: none;border-right: none;padding: 0cm;"><br>&nbsp;</p>
<h2 style='color: #000000;text-align: left;margin-top: 0.35cm;margin-bottom: 0.21cm;background: transparent;font-family: "Liberation Serif", sans-serif;font-size:24px;font-weight: bold;'><span face="Liberation Serif, serif">
        <font size="2" style="font-size:13px;"><strong>3. B&Ouml;L&Uuml;M: VERİ TİPLERİ VE KISITLAMALAR (CONSTRAINTS)</strong></font>
    </span></h2>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">Tablo oluştururken kullanılan en yaygın tipler:</span></span></p>
<ul>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">INT (INTEGER): Tam sayılar i&ccedil;in kullanılır.&nbsp;</span></span></p>
    </li>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">VARCHAR(n):</span> Değişken uzunluklu metinler i&ccedil;in kullanılır (isim, adres vb.).&nbsp;</span></p>
    </li>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">CHAR(n):</span>Sabit uzunluklu metinler i&ccedil;in kullanılır (T.C. kimlik no, plaka vb.).&nbsp;</span></p>
    </li>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">DECIMAL(p,s):</span>Kesin (precision) gerektiren ondalıklı sayılar i&ccedil;in kullanılır (maaş, fiyat vb.).&nbsp;</span></p>
    </li>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">FLOAT / REAL:</span>Yaklaşık değerli ondalıklı sayılar i&ccedil;in kullanılır.&nbsp;</span></p>
    </li>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">DATE / DATETIME:</span>Tarih ve zaman bilgilerini saklamak i&ccedil;in kullanılır.</span></p>
    </li>
</ul>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">Kısıtlamalar:</span></span></p>
<ul>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">NOT NULL</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;">: S&uuml;tunun boş bırakılmasını engeller.</span></span></p>
    </li>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">UNIQUE</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;">: S&uuml;tundaki t&uuml;m değerlerin farklı olmasını sağlar.</span></span></p>
    </li>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">DEFAULT</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;">: Değer girilmezse atanacak varsayılan değeri belirler.</span></span></p>
    </li>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">CHECK</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;">: Girilen verinin belirli bir şarta uymasını zorunlu kılar (&Ouml;rn: </span></span><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">Yas &gt; 18</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;">).</span></span></p>
    </li>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">AUTOINCREMENT</span><strong>:</strong><span style="font-weight: normal;"> Sayısal alanın otomatik olarak artmasını sağlar (ID s&uuml;tunları i&ccedil;in standarttır).</span></span></p>
    </li>
</ul>
<p style="color: #000000;line-height: 100%;text-align: left;margin-bottom: 0.5cm;background: transparent;font-weight: normal;border-top: none;border-bottom: 1px double #808080;border-left: none;border-right: none;padding: 0cm;"><br>&nbsp;</p>
<h2 style='color: #000000;text-align: left;margin-top: 0.35cm;margin-bottom: 0.21cm;background: transparent;font-family: "Liberation Serif", sans-serif;font-size:24px;font-weight: bold;'><span face="Liberation Serif, serif">
        <font size="2" style="font-size:13px;"><strong>4. B&Ouml;L&Uuml;M: SQL SORGULAMA TEKNİKLERİ</strong></font>
    </span></h2>
<h3 style='color: #000000;text-align: left;margin-top: 0.25cm;margin-bottom: 0.21cm;background: transparent;font-family: "Liberation Serif", sans-serif;font-size:19px;font-weight: bold;'><span face="Liberation Serif, serif">
        <font size="2" style="font-size:13px;"><span style="font-weight: normal;">A. Filtreleme ve Operat&ouml;rler</span></font>
    </span></h3>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">WHERE</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;"> yan t&uuml;mcesinde kullanılan operat&ouml;rler:</span></span></p>
<ul>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">BETWEEN: Belirli bir aralıktaki verileri getirir. (</span></span><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">WHERE Fiyat BETWEEN 100 AND 500</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;">)</span></span></p>
    </li>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">IN: Bir liste i&ccedil;indeki değerleri kontrol eder. (</span></span><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">WHERE Sehir IN (&apos;Ankara&apos;, &apos;İzmir&apos;)</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;">)</span></span></p>
    </li>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">LIKE: Metin i&ccedil;inde arama yapar. (</span></span><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">%</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;"> joker karakterdir).</span></span></p>
        <ul>
            <li>
                <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">LIKE &apos;A%&apos;</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;">: A ile başlayanlar.</span></span></p>
            </li>
            <li>
                <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">LIKE &apos;%a&apos;</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;">: a ile bitenler.</span></span></p>
            </li>
            <li>
                <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">LIKE &apos;%ali%&apos;</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;">: İ&ccedil;inde &quot;ali&quot; ge&ccedil;enler.</span></span></p>
<img width="1135" height="441" alt="image" src="https://github.com/user-attachments/assets/8c888397-cd69-4a49-bf99-3d889d79b25b" />
            </li>
        </ul>
    </li>
</ul>
<h3 style='color: #000000;text-align: left;margin-top: 0.25cm;margin-bottom: 0.21cm;background: transparent;font-family: "Liberation Serif", sans-serif;font-size:19px;font-weight: bold;'><br>&nbsp;</h3>
<h3 style='color: #000000;text-align: left;margin-top: 0.25cm;margin-bottom: 0.21cm;background: transparent;font-family: "Liberation Serif", sans-serif;font-size:19px;font-weight: bold;'><span face="Liberation Serif, serif">
        <font size="2" style="font-size:13px;"><span style="font-weight: normal;">B. Sıralama ve Tekrarları &Ouml;nleme</span></font>
    </span></h3>
<ul>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">ORDER BY: Verileri sıralar. </span></span><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">ASC</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;"> (A&apos;dan Z&apos;ye ya da k&uuml;&ccedil;&uuml;kten b&uuml;y&uuml;ğe - Varsayılan), </span></span><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">DESC</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;"> (Z&apos;den A&apos;ya ya da b&uuml;y&uuml;kten k&uuml;&ccedil;&uuml;ğe).</span></span></p>
      <img width="746" height="180" alt="image" src="https://github.com/user-attachments/assets/308d4cfd-5e34-408d-b1c4-02c382151593" />
    </li>
</ul>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;font-weight: normal;'><br>&nbsp;</p>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;font-weight: normal;margin-left: 1.25cm;text-indent: -0.5cm;'><br>&nbsp;</p>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;font-weight: normal;'><br>&nbsp;</p>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;font-weight: normal;margin-left: 1.25cm;text-indent: -0.5cm;'><br>&nbsp;</p>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;font-weight: normal;margin-left: 1.25cm;text-indent: -0.5cm;'><br>&nbsp;</p>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;margin-left: 1.25cm;'><br>&nbsp;</p>
<ul>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">DISTINCT: Tekrar eden kayıtların sadece birer kez g&ouml;sterilmesini sağlar.&nbsp;</span></span></p>
      <img width="838" height="138" alt="image" src="https://github.com/user-attachments/assets/2166e6b1-5664-4a2d-a47e-9bdbf0e4eae8" />
    </li>
</ul>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;font-weight: normal;'><br>&nbsp;</p>
<h2 style='color: #000000;text-align: left;margin-top: 0.35cm;margin-bottom: 0.21cm;background: transparent;font-family: "Liberation Serif", sans-serif;font-size:24px;font-weight: bold;'><span face="Liberation Serif, serif">
        <font size="2" style="font-size:13px;"><strong>5. B&Ouml;L&Uuml;M: TABLO BİRLEŞTİRMELERİ (JOINS)</strong></font>
    </span></h2>
    <img width="820" height="367" alt="image" src="https://github.com/user-attachments/assets/2eedd192-b506-47e9-bc96-618ce2c64566" />
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><br>&nbsp;</p>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;margin-left: 1.25cm;text-indent: -0.5cm;'><br>&nbsp;</p>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;margin-left: 1.25cm;text-indent: -0.5cm;'><br>&nbsp;</p>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;margin-left: 1.25cm;text-indent: -0.5cm;'><br>&nbsp;</p>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;margin-left: 1.25cm;text-indent: -0.5cm;'><br>&nbsp;</p>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;margin-left: 1.25cm;text-indent: -0.5cm;'><br>&nbsp;</p>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;margin-left: 1.25cm;text-indent: -0.5cm;'><br>&nbsp;</p>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;margin-left: 1.25cm;text-indent: -0.5cm;'><br>&nbsp;</p>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;margin-left: 1.25cm;text-indent: -0.5cm;'><br>&nbsp;</p>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><br>&nbsp;</p>
<ul>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">INNER JOIN: Sadece her iki tabloda da karşılığı olan (eşleşen) kayıtları getirir.</span></span></p>
  <img width="1102" height="448" alt="image" src="https://github.com/user-attachments/assets/1820fa02-817a-4eb8-a2f8-2055a17e83a7" />
    </li>
</ul>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;font-weight: normal;'><br>&nbsp;</p>
<ul>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">LEFT JOIN: Soldaki tablonun tamamını, sağdaki tablodan ise sadece eşleşenleri getirir. (Eşleşmeyen sağ taraf NULL g&ouml;r&uuml;n&uuml;r).</span></span></p>
      <img width="1187" height="492" alt="image" src="https://github.com/user-attachments/assets/94295654-094a-4e85-a4c0-80eb41151bf5" />
    </li>
</ul>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;font-weight: normal;'><br>&nbsp;</p>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;font-weight: normal;'><br>&nbsp;</p>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;font-weight: normal;'><br>&nbsp;</p>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;margin-left: 0.75cm;'><br>&nbsp;</p>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;margin-left: 0.75cm;'><br>&nbsp;</p>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;margin-left: 0.75cm;'><br>&nbsp;</p>
<ul>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">RIGHT JOIN: Sağdaki tablonun tamamını, soldaki tablodan ise eşleşenleri getirir.</span></span></p>
      <img width="1058" height="492" alt="image" src="https://github.com/user-attachments/assets/40f26364-2582-4ceb-8f9f-fbf2c9fd9e19" />
    </li>
</ul>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;font-weight: normal;'><br>&nbsp;</p>
<h2 style='color: #000000;text-align: left;margin-top: 0.35cm;margin-bottom: 0.21cm;background: transparent;font-family: "Liberation Serif", sans-serif;font-size:24px;font-weight: bold;'><br>&nbsp;</h2>
<h2 style='color: #000000;text-align: left;margin-top: 0.35cm;margin-bottom: 0.21cm;background: transparent;font-family: "Liberation Serif", sans-serif;font-size:24px;font-weight: bold;'><span face="Liberation Serif, serif">
        <font size="2" style="font-size:13px;"><strong>6. B&Ouml;L&Uuml;M: AGGREGATE (K&Uuml;MELEME) FONKSİYONLARI</strong></font>
    </span></h2>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">Sayısal veriler &uuml;zerinde hesaplama yapmak i&ccedil;in kullanılır:</span></span></p>
<ul>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">COUNT()</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;">: Satır sayısı.</span></span></p>
    </li>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">SUM()</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;">: Toplam değer.</span></span></p>
    </li>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">AVG()</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;">: Ortalama değer.</span></span></p>
    </li>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">MAX() / MIN()</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;">: En b&uuml;y&uuml;k / En k&uuml;&ccedil;&uuml;k değer.</span></span></p>
    </li>
</ul>
<img width="1115" height="376" alt="image" src="https://github.com/user-attachments/assets/84ddc547-d6d8-4380-9c2d-1e6266d73fff" />
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;font-weight: normal;'><br>&nbsp;</p>
<h2 style='color: #000000;text-align: left;margin-top: 0.35cm;margin-bottom: 0.21cm;background: transparent;font-family: "Liberation Serif", sans-serif;font-size:24px;font-weight: bold;'><br>&nbsp;</h2>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><br>&nbsp;</p>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><br>&nbsp;</p>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><br>&nbsp;</p>
<h2 style='color: #000000;text-align: left;margin-top: 0.35cm;margin-bottom: 0.21cm;background: transparent;font-family: "Liberation Serif", sans-serif;font-size:24px;font-weight: bold;'><span face="Liberation Serif, serif">
        <font size="2" style="font-size:13px;"><strong>7. B&Ouml;L&Uuml;M: GROUP BY VE HAVING FARKI</strong></font>
    </span></h2>
<ul>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">GROUP BY: Verileri belirli bir s&uuml;tuna g&ouml;re gruplar (&Ouml;rn: B&ouml;l&uuml;mlere g&ouml;re &ouml;ğrenci sayısı).</span></span></p>
    </li>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">WHERE vs HAVING:</span></span></p>
        <ul>
            <li>
                <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">WHERE: Tablodaki ham veriyi gruplamadan &ouml;nce s&uuml;zmek i&ccedil;in kullanılır.</span></span></p>
            </li>
            <li>
                <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">HAVING: Gruplanmış veriyi (Aggregate sonu&ccedil;larını) s&uuml;zmek i&ccedil;in kullanılır.</span></span></p>
            </li>
            <li>
                <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><em><span style="font-weight: normal;">&Ouml;rnek:</span></em><span style="font-weight: normal;"> &quot;Maaşı 10.000&apos;den fazla olanları getir&quot; derken </span></span><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">WHERE</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;">, &quot;Ortalama maaşı 15.000&apos;den fazla olan departmanları getir&quot; derken </span></span><span face="Liberation Mono, serif"><span size="2" style="font-size:13px;"><span style="font-weight: normal;">HAVING</span></span></span><span size="2" style="font-size:13px;"><span style="font-weight: normal;"> kullanılır.</span></span></p>
              <img width="943" height="497" alt="image" src="https://github.com/user-attachments/assets/efa8feda-fdd2-4a08-bcff-ddbc38909c5b" />
            </li>
        </ul>
    </li>
</ul>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;font-weight: normal;'><br>&nbsp;</p>
<p style="color: #000000;line-height: 100%;text-align: left;margin-bottom: 0.5cm;background: transparent;font-weight: normal;border-top: none;border-bottom: 1px double #808080;border-left: none;border-right: none;padding: 0cm;"><br>&nbsp;</p>
<h2 style='color: #000000;text-align: left;margin-top: 0.35cm;margin-bottom: 0.21cm;background: transparent;font-family: "Liberation Serif", sans-serif;font-size:24px;font-weight: bold;'><span face="Liberation Serif, serif">
        <font size="2" style="font-size:13px;"><strong>8. B&Ouml;L&Uuml;M: SQL SORGU SIRALAMASI (EXECUTION ORDER)</strong></font>
    </span></h2>
<p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">Bir sorgu yazarken komutların diziliş sırasını bozarsanız hata alırsınız. Form&uuml;l şudur:</span></span></p>
<ol>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">SELECT (Hangi s&uuml;tunlar?)</span></span></p>
    </li>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">FROM (Hangi tablo?)</span></span></p>
    </li>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">INNER JOIN / ON (Tablo birleştirme)</span></span></p>
    </li>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">WHERE (Ham veri şartı)</span></span></p>
    </li>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">GROUP BY (Gruplama s&uuml;tunu)</span></span></p>
    </li>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">HAVING (Grup şartı)</span></span></p>
    </li>
    <li>
        <p style='color: #000000;line-height: 115%;text-align: left;margin-bottom: 0.25cm;background: transparent;font-family: "Liberation Serif", serif;font-size:16px;'><span size="2" style="font-size:13px;"><span style="font-weight: normal;">ORDER BY (Sıralama)</span></span></p>
    </li>
</ol>
<p style="color: #000000;line-height: 100%;text-align: left;margin-bottom: 0.5cm;background: transparent;font-weight: normal;border-top: none;border-bottom: 1px double #808080;border-left: none;border-right: none;padding: 0cm;"><br>&nbsp;</p>
