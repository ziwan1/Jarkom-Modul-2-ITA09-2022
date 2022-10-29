Rayhan Kurnia Alunantara Wijaya 5027201030

1.  WISE akan dijadikan sebagai DNS Master, Berlint akan dijadikan DNS Slave, dan Eden akan digunakan sebagai Web Server. Terdapat 2 Client yaitu SSS, dan Garden. Semua node terhubung pada router Ostania, sehingga dapat mengakses internet

Jawaban

Cara untuk menyelesaikan nomor ini cukup hanya dengan melakukan konfig yang diajarkan di modul gns3. Uncomment line eth3 agar dapat mengakses internet. Lakukan hal yang sama untuk eth0 di WISE.

![](https://lh4.googleusercontent.com/aH-YMqqtNEmfO6n9SrxK3SdrQWB4_lMJ3dQnUgIY3r967UELFxI4Vb5FLVP3xiLNhiSWhWtsXiElcj5bwnG5aCKPaQ_IUSs5cnZOjlto3OnG9yb7uuqf4hJN7V9lnJV9KtcQw_yBcWIeFJ1JqdZfbnZxE5kcj-gmFcki-BLrnQCu7jOWoiunphpYwg)

![](https://lh3.googleusercontent.com/0wAyV8DGCj1mGY8tIVwqLDtCqj2167WVSgGOuWfREbmm7X33eFxmxjaTXvta3S15pC4kB3V0MxxbmTPMRZU8DmSpdlCL6ceIb4tJ5aQuBFhfKGdih2oNRY0SneCmxI-3gdFTPcp_Ybow1yFGY1k1Mreyf1ap-65bn3CaJ8DiuNtibjFQflpba3wIqQ)

![](https://lh5.googleusercontent.com/91ooq6sDfs_JaU0254WIClD-jIULhp9ANNLI4gWAW3jV6_L08D5VyFLxNZBhhs3xfxFBGJllLdw-_dcbl66bm4NcSD5B74h5jP_IoON7bTpw8YLGYkd_R9VvPnCeJl4A7GOFOShOW-PwSztXVJb65NtJ93yjp9202UeJkJCck4c6ho73NFS5qg_W6Q)

1.  Untuk mempermudah mendapatkan informasi mengenai misi dari Handler, bantulah Loid membuat website utama dengan akses wise.yyy.com dengan alias www.wise.yyy.com pada folder wise

Jawaban

![](https://lh5.googleusercontent.com/kUIAhu71_DSLdnr1ZjoTBk8h3KKD6TtrkZ_8fIkDQQG-Yskh1PRjGInOKXO2QVLQLFDokK0al_ZUTQxL2sNRnaA-8_iqps8tPjGGxybAA2YSEUD3kROQT47pH4RP3156xykGZKXvWm3rlf8vC_Sb_Kqs6h2sdy5Gui1g8DSZGpsiEPsWUwPTBEMVCQ)

![](https://lh3.googleusercontent.com/TaftU-TXUkJbqJ9SIn8EXhnFO7SxOBtAYrsHOLEBo01w5LQdrYDCyzNwOmju91wmaeVc--04aqaMGr7fjNDD7tpMwEmqiVJMmVvT8AeHg4JgGMlcJrcvDACdrr1SeB2vrxrrwltA3aDSGxg8YfX3Dnagg9x6BWOtd4eLGxKUe50U1B_PTVhY6Wv_EA)

PERCOBAAN PING

![](https://lh3.googleusercontent.com/EapkZ_gO8qWWSRMgDInwbvtome_QASV5jRrFi7Jif7_OeMIIp26_1iD4fwdlYlhphZMoIYFD--0tZsoVcnRHHKwukQQhPk56XYhNt_2vxOfLALsIrQdvhaon2Cd4v92eFWAc8TlEbIhDaxRey-uZo3QjboWPcfq_MyYOZ4L8O9W9fnAb7ytun7hNfw)

1.  Setelah itu ia juga ingin membuat subdomain eden.wise.yyy.com dengan alias www.eden.wise.yyy.com yang diatur DNS-nya di WISE dan mengarah ke Eden 

![](https://lh6.googleusercontent.com/pIbvF74RSZTUspkz3HjnxrMvKe9yEw_DwvC-vFtHD3a5_8JBSkklhw6sv-qiwvCb5Q6qcAwwoNny-zoSs4nWHEbun7kNKwhJnLb8uVcEFslHHd7pY52vOVJlLvBGj3WQk9YnKQS15ibejGOruojX8esu8RpIV0DBNJa68l-Sd1pPqxmJNsb_e58udA)

![](https://lh5.googleusercontent.com/RleI3sYHAG30ewtrFa9-zXHI4uUFSevo3MCsDGqXJZIvZ-BYm0du13uTcchz6qFpsMEhyBeP4IpuQ02Hg4yLJ2kDyb6o3TDssdrdVEuGb7wlVs5-4KdGHISeY9WGIDPYzWb8Q5U9pA3QIB2zpG4wfdsak_KKJT3kOnpuENN7gCHaqlMI0jxSZS_G3Q)

1.  Buat juga reverse domain untuk domain utama

![](https://lh3.googleusercontent.com/nm0ek5MJiYEOyNy0u0B-k4fWsoqFXRWVlcfETR1PJVxvHym2qTK-qNVWQHGV2geI1AyK2zMrJZixINvxTN7rTwkGP7CKHxPy0oYwX68v03LdgCaidDvpXWqomVRePUOi8nZU8eIiL65vToTr0EIZb0yNKjTGRQROYMtgzXCJ9cFjJBqIa-Vy8ynbRg)

![](https://lh3.googleusercontent.com/_K8Y_n3Qwp5lUjl-_ydsQfFrGupDQy8zeLuLMBaUTBPCvCELa5Os2LuMcerTzktNdWWWakoXAxiqQDrPjZEh7sJUqnzfS9NN7exp89RSw-yHL8Lew1wQjlIQYFloZyet90N-Yet5T9JVb1ZVB-sHW9QDaTQppRFOEy6uml95DRqyrvosSbErtfxkdg)

1.  Agar dapat tetap dihubungi jika server WISE bermasalah, buatlah juga Berlint sebagai DNS Slave untuk domain utama

-   Buka /etc/bind/named.conf.local pada WISE kemudian isi sesuai gambar

![](https://lh5.googleusercontent.com/5cht6McADbaXK5SNVAl4uDsX9x7FkkgIQUTwNTVf2ofFtak8AROtedWysJ7gUgyVUEQT-UMRtaIhJac4-oAB3uy2RAnCSXysJgbXDp7ZlpEj4FdvLSeo52_z_Nzk74bqbmQUR4gHHcJTvEtdiyLLa93SR_ufqz-DY0KlEEBiyiMi_ZsH2vnFj2CZhQ)

-   Buka berlint untuk mengset berlint sebagai slave. Kemudian restart WISE

![](https://lh3.googleusercontent.com/7UeeEnBn2BqWcU5Ybw0a_cN3KpUSs0h46RuQBv_rnKKJmCH4s7YceIyzxc62ckJG5NAbl_4Pm2Lrjwin0YojvwHsyvJTooxC1q1WqVi1ImjQyFZmtfQMUOaKhO9aZFBY5cDODdWW3_v7gzow7pxdyNnXwlow1too9hC1MHiWum9by7O0rXv0HriiOw)

-   Ping dari SSS

![](https://lh3.googleusercontent.com/4nFXNIRpZybSn5Hy_iFeN7cDSKCbEbh-WYOxSO1D-LPVkVWsAp1og9BjImNSA587SjAICOsvi-H6cBp_RJVMr9TIvZKnNtm2NtLffxJeZ9LK_2E_nWlgvdXBQdZdNEqE32RM2Hre3gwW1H9lkqrQx2WIrboHjx8oE3hdlMDMWc3e0tTq7rrbfmcfxQ)

1.  Karena banyak informasi dari Handler, buatlah subdomain yang khusus untuk operation yaitu operation.wise.ita09.com dengan alias www.operation.wise.ita09.com yang didelegasikan dari WISE ke Berlint dengan IP menuju ke Eden dalam folder operation

-   Edit /etc/bind/wise/wise.it09.com

![](https://lh3.googleusercontent.com/uTHrS84xZ2bQHxlyxRO9cxKkuLCAZngJEbIlQci8OEbPSH5x6g-TUfPJ2FiGZqIfm-Hdv68m0DWuy25wZCIvtfxhdns5KzFDDwHljWvQFEO1L1K8UrHu4WDHrtxjQbWyQ-jmPLANSVXw3HQlIqSIREM9j6okIUD-fMI655ohOD8vL6CLrDWlMGwYYw)

-   Edit /etc/bind/named.conf.options

![](https://lh4.googleusercontent.com/DBtkJFVvyFoqVEWC-ZXgT0QLcWnR9t1Zw7Y16Zrcl8pflxX-Cq2G_YYCgDhSMZ7oowvZ6TcmoiIi1pT9FX6sQZR8jGtP8ZhMK8fT9VMjdElVpH5bHxSQ047ko2S8uw2ezD-VeQcNIg-7_NNKQHj3FwdMvQZhZPoGIlOkhQSacD-yraBQ-4MUCxg_SQ)

-   Edit file /etc/bind/named.conf.local

-   ![](https://lh3.googleusercontent.com/MSU0gygZqj6GDP_xwkvh-cq9wu7z5hBldiviBWehSIFSzNlCwd4HAiVvNucnFVMy1ZnTwczYRfPXXA4h86FygOn10UFCt3qegUcaboOCEd4Xs5rCUSnGp1S7dBzpNk3aFbzMI02nrxyVMTvnNG7y5dbb7cLXEXVRsNAk7-GmpIsqrQBBx7OW4u9SUQ)

-   Edit file  /etc/bind/named.conf.local

-   ![](https://lh6.googleusercontent.com/fOykgPddD1E6FlNNFsGPb5RWX5caLL7ywaqy_5b4SdDhkxRZxRkVNRp-Rx0hpfYZpcpKSW5Vldk4cNmsAlr5snkNEzFhAMlrNwemMZzp9c_HzokVyizWL9PyE1-VPm52We-L7ZgW_CeO8Ay04LpwKbuLEOx6NeclVg6ow5JpvUKEpuF5BIa6xKEIvw)

-   Edit file /etc/bind/named.conf.options

-   ![](https://lh3.googleusercontent.com/flzqEofRUyje7zR3QwIdmatczisXjpm75N6JEZRsI91dOVoUla9tTmrykM6aMRGNKuNfW3WKor4ACqUhUa3Ybyuw29raB0OT9v1_kS0XnmS4Wcu7RKT0mGTEG-6N-CNExrTjYO6L70MTM1RiXR6nDXGlhY1v1KW5KlvROff9I_HN1KplTA7jLwfJOg)

-   Edit file /etc/bind/operation/wise.ita09.com

-   ![](https://lh4.googleusercontent.com/PCnLZPHpSQZCA2o2G2SFclyoOk1jOc1HtuW9g06jEEsPRAdD6MEFEsuW_oezy1_iayL63e67C_6B4jYKMg0ezy63t2BmpZfWXJrVpIJFwDmLSMXG3KwgIabrbLrFkdg4_CSLFc7vIzppmZDzNpv4bkZS6xPdge2m3j_2C4dJCbMFb6rqMlG_BBTPmQ)

1.  Untuk informasi yang lebih spesifik mengenai Operation Strix, buatlah subdomain melalui Berlint dengan akses strix.operation.wise.yyy.com dengan alias www.strix.operation.wise.yyy.com yang mengarah ke Eden

1.  Setelah melakukan konfigurasi server, maka dilakukan konfigurasi Webserver. Pertama dengan webserver[  www.wise.yyy.com](http://www.franky.com). Pertama, Loid membutuhkan webserver dengan DocumentRoot pada /var/www/wise.yyy.com

-   Instalasi lynx

-   ![](https://lh4.googleusercontent.com/Tdyt3C16NSDy6OQSYeFyNw1RjVLUmh8xOk3suSCaHj8IoL87sdNkwIGSkuTId4hdwKTaT0RTzta57MCQKRsrHHftcBAgoHXbINr9EhRcWOeRqY9QPWUWfzFwQ9LyOowvreTc1KJq45NhyOIZ8euXxXllpzpe9j7w3ZUeKJXjoek0GI6aAsZHII5Vng)

-   Gunakan lynx

-   ![](https://lh6.googleusercontent.com/E3wwCC4274-L62UnL6Z0oZkggFCcMmunVE_LBapmqVXnjgYUwJ9ONoRnW04k4NQyyIcPDKPyF6rK4z4HRElzdP_ytU_WLPgdbkW9iz51Xg6Pn6DOqbAA5Fys50N6BfkLBQLg0eryQbevtSuXw8xgXZF1haAejM1BrUTHPkTacD1h7Q3GF2T4qDHxTw)

-   Install apache2

-   ![](https://lh4.googleusercontent.com/L97alQsYsc94BBcTVCOWTEvfDTyEKrJvagx_1sl-ezYe2qk73WHGV19PR4pj9aba7NrkkM_9tYOxvFBMckiJ7b8lm7xpiYlp-gOAeWMVqn7iQONeIbdx1uBy5Q0eo1Jd4W6KoLS7W6eHSMgkYxgVhDizQmjHiL1OdyI_hHGV58wgU21iw_DHQNIECQ)

-   Dengan wget kita ambil file wise dari source lalu kita masukkan ke directory /var/www

![](https://lh3.googleusercontent.com/WMP0ovOPTYYDFKFXAPWEhO6sl7wdFWoZ5SgomGZhxLOWAlacD_r7aqDKZJvMIEsUDchb0AMgk4pqUC1sb3HD5PO0QyfohxkgmkrroWzuNRNRtHY4qgZPVb9ZLsmx20nb5nhVIOfCLeUyCA6YzVV5jYpftzh2G5yFVn5zzpDs1FyPlWmrf-ouW7VOCQ)

-   Kita ubah DocumentRoot pada /etc/apache2/sites-available/default.conf menjadi /var/www/wise.ita09.com

![](https://lh4.googleusercontent.com/moNaFj0I5kmnLvmDWXPrYGobdPZgQaRg_AxfXXXXnBVtzJl_3v_oOZebEczOIG9woYgnTPZ4VxzSVze896I1_Oco1UdrnKldxKL2WOfHXZmN2ty9X0lZVzJjqkycNGC7Z3qYBuBHm9FABAurwwokRIxKA1C8YEkjjw4TvR6fKqC0pxvXZTt46z1uTw)

1.  Setelah itu, Loid juga membutuhkan agar url[  www.wise.yyy.com/index.php/home](http://www.franky.com/index.php/home) dapat menjadi menjadi[  ](http://www.franky.com/home)[www.wise.yyy.com/home](http://www.franky.yyy.com/home)

1.  Setelah itu, pada subdomain[  www.eden.wise.yyy.com](http://www.super.franky.com), Loid membutuhkan penyimpanan aset yang memiliki DocumentRoot pada /var/www/eden.wise.yyy.com

-   Kita download dahulu resource eden.wise dengan wget lalau kita unzip dan pindahkan ke directory /var/www/

![](https://lh3.googleusercontent.com/aLMIk2dBCBGjnjDl9HCrSIWTKNAxpVWCA1EDP28KBM2fvFXaBaAoVHX_Mgi_55r4zQbfRQjCOMAmOzGfSz9BMIj9et5hN5aIbrpIjVUmo01DHoZqZ-PZHfDTNg_eYhqft9Q68s_DP3TNkmMNVKBoct-gnA62csmct1i5WgJS3lculjJsNeON07RaTQ)

-   Pertama kita copy file default.conf ke file eden.wise.ita09.com.conf. Lalu, kita edit file eden.wise.ita09.com.conf menjadi seperti gambar dibawah 

![](https://lh4.googleusercontent.com/sS04bVDsGSGWvWr9nAEDpqCeIA7Kc4d8uNdJRQzDPE7jNPq2S2z5NfNaxMM4gaQX63-azDYshWfYAjHAZ6jaGnK6X3eNRpIE8hpcAr9MuVOaBGJMo8CWJK_Zmq8Qh267AtVSymGwwmzJSP95OiUL8zWerplhoXX8gY5embWSk9FbBIA_pfKvSySErQ)

-   Lalu kita aktifkan konfigurasi dengan "a2ensite eden.wise.ita09.com dan kita restart apache2

-   Kita coba buka dengan lynx

![](https://lh4.googleusercontent.com/qdnWzc8xNn6yVo1LlOWgaPc4a59a6Hyrjws1WNVsLPht80g32S9h0EVXMs5hjPJOvqFMu7_H7hdmTCw6kwwrOBGg4qIcH_djn4nFee8y8HNZ1cvYQ-WC7tBPoDaGxVrzB0G4f32OtHB-lZfMa4MjKFgz_hPC1N6vxGY11Yx96cUr6EtTG4BLrJiX6A)

1.  Akan tetapi, pada folder /public, Loid ingin hanya dapat melakukan directory listing saja

-   Untuk melakukan directory listing. Edit file /etc/apache2/sites-available/eden.wise.ita09.com.conf menjadi seperti gambar dibawah

![](https://lh3.googleusercontent.com/gpnt4D7-8L9NtCRxarb9XnyiWo1GKTqY8zuTP-nKz2C6M3dPp1HF7-Nz2o9ULIYv-8cgS_tKXtHHOssssFEWFsmW3jyPdEaJ53CaLDtUbDu-CkaJnEi5c1ZHVuv8P_BxANgouk_oyENw6JhK8TnDUdQ9RbfiVppPH_FbKF9kHEILQYK53t9iF0sgvg)
