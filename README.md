Langkah-langkah install Ansible di OS UBUNTU 18:04 AWS EC2
1. Buat hosts remot dan satu hosts sebagai master dan dua host sebagai worker
2. Install Ansible di hosts yang akan menjadi sebagai hosts remot
3. Install python di hosts yang akan menjadi hosts tujuan
4. Ip yang berada di file package.yml 172.31.19.134 ip private master
5. Jika worker node role <none> jalankan perintah di bawah
   kubectl label nodes node1 node-role.kubernetes.io/worker=worker
   Ket: node1 adalah nama worker nodenya



