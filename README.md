**RESPONSI TCCL**
by *Rochmad Adhi Y NIM 165410167*

**Aplikasi yang dibuat:** Halaman profile menggunakan html seperti gambar berikut uji coba diserver local:
![Local Preview](https://github.com/rochmadadhiyunianto/responsitccl/blob/master/responsi.png?raw=true)

**Dockerfile:**
berikut config Dockerfile yang digunakan:

    FROM httpd:2.4
    COPY ./public-html/ /usr/local/apache2/htdocs/

**Penjelasannya:** 

 1. menggunakan images *httpd:2.4*
 2. COPY: untuk memindahkan file local public_html ke dalam docker
 

**Perintah Build Image:**   *docker build -t apache2 .*
memberikan nama images: apache2


**Perintah menjalankannya:** *sudo docker run  -p 8080:8080 --name apache2-1  apache2*


**Hasil jika dijalankan:**
![Local Preview](https://github.com/rochmadadhiyunianto/responsitccl/blob/master/terminal.png?raw=true)


pada output ini url/ip *http://172.17.0.2/* merupakan ip docker-machine yang digunakan sebagai host Docker

**Prestasi:**
 1. Github Star Project 17 star: https://github.com/rochmadadhiyunianto/googlemap-stars-to-addresses
 2. Github Contribution: https://github.com/pulls?q=is%3Apr+author%3Arochmadadhiyunianto+is%3Aclosed

