# Download-MacOS


Tải các phiên bản MacOS, các bạn copy dòng lệnh dưới rồi dán vào Terminal

- mkdir -p ~/macOS-installer &amp;&amp; cd ~/macOS-installer &amp;&amp; curl https://raw.githubusercontent.com/munki/macadmin-scripts/main/installinstallmacos.py > installinstallmacos.py &amp;&amp; sudo python installinstallmacos.py

Sau khi tải xong, copy đường dẫn thư mục bên dưới, mở Finder, nhấn Command + Shift + G, dán vào cửa sổ

- ~/macOS-Installer/

*Lưu ý: Bắt đầu từ macOS Monterey 12.3, Apple đã loại bỏ hỗ trợ cho python 2.7 nên các bạn sẽ phải thêm bước này
Mở Terminal gõ lần lượt 3 lệnh này:

- xcode-select --install

- pip3 install xattr

- mkdir -p ~/macOS-installer && cd ~/macOS-installer && curl https://raw.githubusercontent.com/munki/macadmin-scripts/main/installinstallmacos.py > installinstallmacos.py && sudo python3 installinstallmacos.py
