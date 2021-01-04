# jinganteng123
195410033

Petunjuk : 
1. git clone pada terminal anda : 

                           git clone https://github.com/fauzi195410033/jinganteng123
                           
2. pull image dari dockerhub ke terminal anda : 

                            docker pull fauzi195410033/jinganteng123


3. masuk kedalam direktori file yang diambil dari github : 

                            cd jinganteng123


4. setelah masuk kedalam direktori jinganteng123 jalankan perintah berikut :

                            docker-compose up -d


5. setelah selesai buka web browser anda lalu masuk ke localhost : 

                            localhost --> masuk ke menu web
                            
                            localhost:8080 --> masuk database
 
 6. untuk membuat web bisa melakukan CRUD lakukan setting pada database, Log in ke database : 
 
                            Username : root
                            password : example
                            Database : (kosongkan, jangan di isi)
                            
                            
    lalu create database dengan nama : data                    
    
    buat tabel dengan nama : tb_blog
    
    lalu buat colom : 
    
                    id  | int | length (kosongkan) |  options (koosngkan) | NULL (kosongkan)  | AI (conteng, ini primary key) | sisanya kosongkan
                    
                    nama  | varchar | lenght (25) | options (default) | sisanya kosongkan
                    
                    nim | int | length (9)  | sisanya kosongkan
                    
                    Default values (conteng), Comment (conteng)
                    
                    lalu save.
                    
7. buka lagi localhost, lalu masuk ke menu CRUD. sekarang telah bisa melakukan proses CRUD pada web ini.

8. untuk mematikan docker ketikkan syntax berikut pada terminal : 

                    docker-compose stop
