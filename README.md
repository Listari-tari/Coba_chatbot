# Coba_chatbot
Chatbot interactive menggunakan simple web socket server

- Chatbot_train.py: untuk melatih data yang tersedia di folder data, setelah dilatih, hasilnya akan disimpan sebagai database SQLite. 
- Chatbot.py: untuk menghasilkan respons untuk permintaan pengguna menggunakan database SQLite yang diperoleh dari hasil training. 
- server.py: untuk mengirim kembali pesan ke klien dan menghubungkan chatbot agar bisa dibuka melalui web browser. 

Cara menjalan file agar bisa dijalankan adalah memastikan telah menginstal paket Python ChatterBot dan simplewebsocket-server
