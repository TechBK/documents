=========================
Install Hamachi for Linux
=========================


- Install the dependancies

    sudo apt-get install lsb

- Go to http://secure.logmein.com/us/labs
- Click Show More for Linux Command Line Version
- Select the correct download for your OS (for 64 bit Ubuntu it is the 64 bit .deb file)
https://secure.logmein.com/labs/logmein-hamachi_2.1.0.139-1_amd64.deb
- Double click the downloaded file to install Hamachi (follow the prompts in the window that opens)



- Khởi động dịch vụ
::

    sudo service logmein-hamachi start
    sudo hamachi login

- Tạo vpn server:
::

    sudo hamachi create <id> <pass>

- Kết nối vào vpn server:
::

    sudo hamachi join <id>

- Đặt nick name
::

    sudo hamachi set-nick <nick-name>

- Kiểm tra list hamachi list --> xem ip -> ssh <id>@<ip>


$ hamachi set-nick bob
$ hamachi login
$ hamachi create my-net secretpassword
$ hamachi go-online my-net
$ hamachi list
$ hamachi go-offline my-net