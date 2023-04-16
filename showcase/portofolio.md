# 📑 Portofolio

## Gitlab CI/CD Pipeline For React Application

<div>

<figure><img src="../.gitbook/assets/Diagram Mini Project_ Gitlab CI_CD Pipeline For React Application-Pipeline.drawio2.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src="../.gitbook/assets/Diagram Mini Project_ Gitlab CI_CD Pipeline For React Application-Workflow.drawio.png" alt=""><figcaption></figcaption></figure>

</div>

Pada proyek ini, kita akan membagi aplikasi ke dalam dua lingkungan server, yaitu Staging dan Production. Lingkungan Staging digunakan untuk menguji aplikasi sebelum di-deploy ke lingkungan Production. Lingkungan Production digunakan untuk menyediakan aplikasi yang sudah siap digunakan oleh pengguna.

{% hint style="info" %}
Gitlab Repository: [https://gitlab.com/medium-taufiqpsumarna/todo\_react\_apps](https://gitlab.com/medium-taufiqpsumarna/todo\_react\_apps)
{% endhint %}

## Grafana Resource Monitoring, Logging, And Alerting System

<div>

<figure><img src="../.gitbook/assets/Screenshot_20230215_091339.png" alt=""><figcaption><p>Node Exporter</p></figcaption></figure>

 

<figure><img src="../.gitbook/assets/Screenshot_20230215_092421.png" alt=""><figcaption><p>Mattermost Grabot Plugin</p></figcaption></figure>

 

<figure><img src="../.gitbook/assets/Screenshot_20230215_091100.png" alt=""><figcaption><p>Cadvisor</p></figcaption></figure>

</div>

Create Grafana Dashboard Resource and Logging monitoring, Grafana, Cadvisor, Promtail, Loki, Node\_Exporter and Prometheus are all software tools used for monitoring and visualizing system metrics and logs and for alerting system we use mattermost with grabot (Grafana Bot) integration

Tools: AWS, EC2, Grafana, Cadvisor Prometheus, Loki, Promtail, Node\_Exporter, Mattermost

## CI/CD Workflow - Flutter Apps and fastlane deploy

<figure><img src="../.gitbook/assets/Screenshot_20230215_085149.png" alt=""><figcaption><p>CI / CD Pipeline</p></figcaption></figure>

DevOps Engineer works with developers and the IT staff to oversee the code releases. DevOps understands the Software Development Lifecycle and understand automation tools for developing digital pipelines (CI/ CD pipelines), In charge for:

* Design, implementing and discus about CI/CD pipelines with developer team and project lead.
* Implementing mobile development CI/CD pipelines.
* Implementing web development CI/CD pipelines.
* Research and Development Gitlab CI/CD Pipelines.
* Design server architecture and specification.
* Configure Gitlab Repository Server on-premise.
* Configure Gitlab Runner Server on-premise.
* Configure SonarQube Server on-premise.
* Configure Integration Between Gitlab and SonarQube.

Tools: Docker, Gitlab, Gitlab CI/CD, Gitlab Container Registry, Gitlab Runner, SonarQube, Fastlane, Ubuntu 22.04 LTS

## Integrasi Sonarqube Static Code Analyst dengan Github Action

![Sonarqube Project Dashboard](<../.gitbook/assets/image (4).png>)

![Hasil Analisa Sonarqube](<../.gitbook/assets/image (3).png>) ![Hasil Analisa Sonarqube Codesmell](<../.gitbook/assets/image (8).png>)

![Github Workflows](<../.gitbook/assets/image (5).png>) ![Github Build Status](<../.gitbook/assets/image (12).png>)

SonarQube adalah alat peninjauan kode otomatis untuk mendeteksi bug, kerentanan, dan code smells dalam kode yang dibuat. SonarQube bisa terintegrasi dengan alur kerja dalam banyak proyek dalam pemeriksaan kode yang berkelanjutan, sonarqube dapat dijalankan dalam satu server kemudian di integrasikan dengan SCM atau integrasi dengan proses continous integration

## Jenkins Pipeline Continuous Integration

![Jenkins Pipeline](<../.gitbook/assets/image (2).png>)

![Jenkins Pipeline Status](<../.gitbook/assets/image (9).png>)

![Console Output](<../.gitbook/assets/image (13).png>)

Pada pipeline jenkins kali ini kita akan melakukan desain pipeline dengan integrasi github webhook sehingga ketika ada perubahan code secara otomatis jenkins akan melakukan build image, tagging dan kemudian image tersebut akan kita upload kedalam Docker registry setelah itu image terbaru juga akan dijalankan kedalam remote Docker server.

## Lens Kubernetes IDE for GUI Teams !

![Lens Cluster Dashboard](<../.gitbook/assets/Screenshot (68).png>) ![Lens Nodes List](<../.gitbook/assets/Screenshot (69).png>) ![Lens Nodes Workload List](<../.gitbook/assets/Screenshot (70).png>)

Lens adalah salah satu tools yang saya gunakan untuk manage dan monitoring kubernetes cluster, lens memungkinkan kita untuk monitoring container, pod, deployment, service,dsb dalam satu aplikasi atau dashboard yang sangat mudah, dan didalamnya terdapat metrix untuk monitoring penggunaan kluster

## Kong Ingress Controller Kubernetes

![Kong Ingress Controller Diagram](<../.gitbook/assets/image (1) (1).png>) ![Domain Configuration](<../.gitbook/assets/kong ingress domain.png>)

![](<../.gitbook/assets/Screenshot (71).png>) ![](<../.gitbook/assets/Screenshot (72).png>) ![](<../.gitbook/assets/Screenshot (73).png>)

Ingress controller adalah sebuah service pada kubernetes yang berfungsi untuk mengekspos service keluar cluster fungsinya hampir sama dengan tipe service LoadBalancer namun perbedaan yang paling utama adalah service type ingress hanya membutuhkan satu loadbalancer saja dari cloud provider sehingga hal ini dapat mengurangi penggunaan budget pada cloud platform.

## Jenkins CI/CD Dashboard

![Jenkins dengan SSL certificate nginx proxy](<../.gitbook/assets/jenkins with ssl.png>)

![Dashboard Jenkins](../.gitbook/assets/jenkins5.png) ![Console Output](../.gitbook/assets/jenkins4.png) ![Dashoard Jenkins Project](../.gitbook/assets/Jenkins3.png) ![Hasil Build Jenkins](../.gitbook/assets/Jenkins.png)

Jenkins adalah server otomatisasi sumber terbuka. Ini membantu mengotomatiskan bagian-bagian pengembangan perangkat lunak yang terkait dengan pembangunan, pengujian, dan penerapan, memfasilitasi integrasi berkelanjutan dan pengiriman berkelanjutan.

## Netdata Monitoring Dashboard

![Netdata Instance Grouping](../.gitbook/assets/Netdata2.png) ![Netdata Summary Dashboard](../.gitbook/assets/Netdata.png)

Netdata adalah tool monitoring yang mengoleksi data sistem, hardware, aplikasi, maupun container secara realtime. Dan yang membuat Netdata sendiri cukup populer adalah konfigurasinya cukup simple. Sehingga kita tidak perlu ribet di awal untuk mulai menggunakan Netdata.

## KOPS Kubernetes Cluster Provisioning

![Service Deployment Using KOPS Cluster](<../.gitbook/assets/Screenshot (54).png>) ![K9S](<../.gitbook/assets/Screenshot (56).png>) ![K9S Logs](<../.gitbook/assets/Screenshot (60).png>)

Sebelum adanya culture DevOps , kita masih menggunakan metode waterfall dan menggunakan satu server monolith untuk satu aplikasi sehingga hal ini menyebabkan cost, performance degraded dan waktu deployment aplikasi berjalan sangat lama karena kita perlu melakukan instalasi dan pengadaan server, namun saat ini teknologi cloud dan arsitektur software dengan basis _microservice_ sangat membantu bisnis dalam kecepatan deploy apps dan pengembangan, maka dari itu perlu sistem untuk melakukan manajemen kluster salah satunya kita bisa menggunakan tools seperti Lens, K9s, Kube Dashboard, dan Rancher untuk melakukan monitoring dan deployment biasanya tools ini dipadukan juga dengan sistem monitoring lainnya seperti Prometheus, Grafana, ELK Stack, TIG Stack dll.

## Topologi kubernetes cluster AWS menggunakan KOPS

![Topologi Kubernetes Cluster](<../.gitbook/assets/image (11).png>)

Pada desain topologi kali ini kita akan membuat sebuah infrastruktur kubernetes cluster dan untuk provisioning sendiri kita menggunakan KOPS, untuk aplikasi sendiri kita membagi dua namespace pada kubernetes yaitu staging dan production, untuk image registry sendiri kita menggunakan Docker Hub, kemudian untuk mengakses aplikasi disini kita menggunakan servis load balancer aws yang akan membagikan traffic user kedalam pods yang tersebar dalam worker nodes kubernetes.

Disini kita memanfaatkan deployment dan kubernetes services sehingga kubernetes akan membantu kita untuk melakukan monitoring dan auto pods healing bilamana pods (container) yang rusak maka akan otomatis diganti oleh kubernetes sehingga aplikasi yang berjalan bisa lebih stabil dan pastinya meningkatkan SLA dari aplikasi yang kita miliki.

## SSH Bastion / Jumphost teknik koneksi internal resource secara aman.

![Ilustrasi bagaimana Jumphost / Bastion bekerja](<../.gitbook/assets/image (8) (1).png>)

Ketika kita membangun sebuah infrastruktur salah satu aspek yang perlu kita perhitungkan adalah **Keamanan** hal ini sangat penting karena dengan melindungi resource yang tersedia dalam infrastruktur kita sama artinya kita melindungi data yang kita miliki.

Salah satu resource yang paling krusial dan perlu kita lindungi adalah **Database** ketika kita membangun infrastruktur kita sangat disarankan untuk menutup akses database kepada publik, hal ini dilakukan untuk menghindari hal yang tidak kita inginkan seperti kebocoran data yang akhir-akhir ini sering terjadi.

## Topologi AWS High Availability

![Topologi Infrastruktur High Availibilty AWS](<../.gitbook/assets/image (1).png>)

Topologi yang dibangun pada AWS yang memanfaatkan 3 multiple AZ, memanfaatkan layanan S3 Bucket untuk penyimpanan konten, Auto Scalling EC2 Instance, Application Load Balancer dan Amazon RDS untuk penyimpanan databasenya, serta memanfaatkan fitur IAM untuk membagi hak akses terhadap resource yang berada didalam AWS.

Dengan desain topologi diatas diharapkan Aplikasi yang dijalankan dapat berjalan dengan baik serta mengurangi peluang downtime ketika diakses oleh banyak orang.

## Implementasi VPN Server dengan Pritunl / Openvpn pada AWS

![Topologi Untuk mengamankan resource cloud menggunakan VPN Gateway](<../.gitbook/assets/image (1) (1) (1).png>)

Untuk mengakses sistem internal yang berada pada cloud kita membutuhkan sebuah koneksi yang aman yaitu VPN, tujuan utamanya adalah agar kita dapat mengakses resource internal yang kita miliki secara aman.

## Topologi Sederhana AWS

![Topologi Sederhana Software Development pada AWS](<../.gitbook/assets/image (7) (1).png>)

Dalam membangun sebuah environment pada cloud platform kita perlu melakukan desain topologi untuk desain sendiri hampir sama dengan topologi on premise namun perbedeaan yang paling utama adalah infrastruktur yang kita miliki tidak benar-benar ada melainkan berada di provider cloud yang kita gunakan, dan tentunya ada pembagian antara Jaringan private dan publik untuk faktor keamananan.

## Desain Ruangan Khusus Video Conference menggunakan logitech meetup

![First Test koordinasi dengan project site Bali](../.gitbook/assets/IMG\_20200221\_140238.jpg) ![Layout ruangan meeting](../.gitbook/assets/IMG\_20200131\_191258.jpg) ![Testing Konfigurasi bandwidth](../.gitbook/assets/IMG\_20200120\_161726.jpg) ![Pre testing ruangan direksi](../.gitbook/assets/IMG\_20200113\_141958.jpg)

Sebelum terjadinya pandemi direksi menginginkan dibuat sistem video conference untuk menghemat cost perjalanan dinas hanya untuk monitoring pekerjaan di site project, namun tidak ada yang menyangka adanya pandemi yang membuat interaksi menjadi berat karena harus menjaga jarak, namun dengan adanya teknologi video conference yang diimplementasikan dalam perusahaan membuat koordinasi dan pengambilan keputusan menjadi lebih cepat, hal ini tentu saja sangat meningkatkan performa perusahaan dan sampai saat ini sistem video conference berjalan dengan baik.

## Implementasi Fortigate Firewall

![](<../.gitbook/assets/Screenshot (63).png>) ![](<../.gitbook/assets/Screenshot (64).png>) ![](<../.gitbook/assets/Screenshot (65).png>) ![Implementasi fortigate firewall pada perusahaan sebelumnya](<../.gitbook/assets/Screenshot (66).png>)

firewall adalah sistem keamanan jaringan komputer yang mampu melindungi dari serangan virus, malware, spam, dan serangan jenis yang lainnya. Dapat dikatakan juga bahwa, firewall merupakan perangkat lunak untuk mencegah akses yang dianggap ilegal atau tidak sah dari jaringan pribadi (private network). tugas utama dari adanya firewall sendiri adalah untuk melakukan monitoring dan mengontrol semua akses masuk atau keluar koneksi jaringan berdasarkan aturan keamanan yang telah ditetapkan, alasan paling utama dari penggunaan firewall ini adalah untuk melindungi dan membatasi penggunaan jaringan internet yang digunakan oleh user.

## Implementasi jaringan VPN pada perusahaan.

![Topologi VPN](<../.gitbook/assets/image (3) (1).png>)

VPN atau virtual private network merupakan sebuah teknik dalam jaringan komputer yang bertujuan untuk menghubungkan jaringan lokal pada suatu tempat dengan jaringan yang kita miliki, beberapa keuntungan yang bisa kita temui adalah kemudahan dalam melakukan remotting perangkat jaringan lokal, traffic yang terkenkripsi membuat komunikasi lebih aman serta memungkinkan kita sebagai admin dalam manajemen perangkat dari jarak jauh / remote.

## Fail Over Koneksi Internet

![Topologi load balancer](<../.gitbook/assets/image (10) (1).png>)

Failover adalah salah satu metode pada jaringan untuk menghindari down time koneksi. Dan sering digunakan jika memiliki lebih dari 1 sumber internet. Cara kerja dari failover, akan terdapat minimal 2 link atau jalur menuju ke internet. Jalur 1 akan berfungsi sebagai main link atau jalur utama.

## Load Balancer Koneksi Internet

![Topologi load balancer](<../.gitbook/assets/image (6) (1).png>)

Load balancing adalah proses pembagian beban _traffic_ sebuah aplikasi atau server. Dengan load balancer, beban traffic tidak akan dibebankan kepada beberapa jalur koneksi.

Hal ini mempercepat waktu respons internet dalam mengakses resource pada internet dan mencegahnya _overloading traffic_. Dengan begini, kinerja internet akan lebih maksimal tidak peduli berapa banyak traffic yang Anda dapatkan.

## Implementasi VLAN untuk memisahkan jaringan secara virtual

![Topologi jaringan VLAN](<../.gitbook/assets/image (5) (1) (1).png>)

VLAN (Virtual LAN / Virtual Local Area Network) adalah domain broadcast yang dipartisi dan terisolasi dalam jaringan komputer pada lapisan data link. Topologi VLAN adalah bentuk jaringan dengan model LAN sangat bergantung pada letak workstation. VLAN berfungsi untuk menyediakan layanan secara tradisional. pada umumnya VLAN diimplementasikan sebagai faktor keamanan, cost reduce serta membantu Admin untuk memudahkan dalam manajemen jaringan.

## Topologi Jaringan LAN Sederhana

![Topologi sederhana jaringan LAN pada SOHO.](<../.gitbook/assets/image (9) (1).png>)

Untuk jaringan lokal berskala kecil biasanya hanya terdiri dari modem, router, switch, access point dan untuk client dapat berupa PC, Laptop atau Smartphone, pada case kali ini kita menggunakan jaringan LAN dengan network 192.168.50.0/24 dan alamat IP router sebagai gateway menuju jaringan internet 192.168.50.1 untuk mengakses konfigurasi router kita gunakan IP Address 192.168.50.254 dan kita menggunakan IP Publik 182.223.113.242 untuk akses internet sendiri kita akan menggunakan firewall NAT.

## Implementasi Zabbix Sebagai Network Monitoring System

![Implementasi Zabbix Monitoring Pada Perusahaan Sebelumnya](<../.gitbook/assets/image (2) (1).png>)

Untuk memastikan status infrastruktur yang kita miliki berjalan dengan aman kita perlu melakukan monitoring salah satunya adalah kita bisa menggunakan Zabbix network monitoring&#x20;

## Implementasi Quality Of Service Pada Jaringan Komputer

![](<../.gitbook/assets/image (4) (1) (1).png>)

Quality Of Service adalah sebuah teknik dalam jaringan komputer untuk menjamin berjalannya traffic secara lancar dan minim interfrensi meskipun traffic yang berjalan sedang padat, hal ini dapat dicapai dengan melakukan klasifikasi traffic, mengurutkan prioritas traffic, dan bandwidth control.
