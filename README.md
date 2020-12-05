Langkah-langkah install Ansible di OS UBUNTU 18:04 AWS EC2
1. Install Ansible di hosts yang akan pusat
2. Install python di hosts yang akan tujuan
3. Ip yang berada di file package.yml 172.31.19.134 ip private master
4. Jika worker node role <none> jalankan perintah di bawah
   kubectl label nodes node1 node-role.kubernetes.io/worker=worker
   Ket: node1 adalah nama worker nodenya



