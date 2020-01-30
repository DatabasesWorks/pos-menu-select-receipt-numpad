
# Menu Select

- Software Used: Qt (Core, GUI, Widgets, SQL, PrintSupport)
- Language Used: C++, Android (In-progress)

![screenshot](./screenshot.png)

Menu Select uses the <b>Qt 5.11.1</b> framework.<br>
I am in no way affiliated with Qt and am using their software under the <i>GNU LGPLv3</i> license.<br>

#### Description/Purpose
- Provide a desktop software able to search menu items by id number.
- Ability to use receipt printer to print menu items in Chinese, to promote efficiency and improve customer wait times.
- Meant to be used on a touchscreen monitor using Windows x86/64 bit.

#### C++ App Features
- <b>Remote:</b> SQLite database stores static information containing an <i>item id, Chinese name, English name,</i> and <i>price</i>.
- <b>Printer Functionality:</b> Able to hook up (~80mm width) receipt printer (USB/Ethernet) that prints item names in Chinese.
- <b>Colour Coded:</b> Menu items are colour coded by the quantity as well as section of the kitchen they will be administered.
- <b>Responsive Dashboard:</b> Calls the database as the user enters/deletes a new entry.
- <b>Interactive List:</b> The list widget allows options to <i>view, add one, delete one, or delete all</i> items freely.

#### Download
- Download files in windows_cpp_v1.0 and compile using Qt Creator.
<br>
:whale: Thanks for checking out the project! :whale:
