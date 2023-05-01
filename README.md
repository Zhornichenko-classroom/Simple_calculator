## Simple_calculator

### Getting Started


### Installation

_Below is an example of how you can assemble the simple calculator within PyQt5-tools._

1. Clone the repo
   ```sh
   git clone https://github.com/ZhoRik78/Simple_calculator.git
   ```
2. Install pip packages PyQt5 - tools, pyinstaller to build up an application
   ```sh
   pip install -r requiremenst.txt
   ``` 
   
4. To build up a dependecies between `.ui` files `.py` 
   ```sh
    pyuic5 -x view/simple_calc.ui -o src/simple_calc.py
   ```
5. Build an python application within the following command
   ```sh
    pyinstaller  --onefile src/simple_calc.py
   ```


### Contact

Zhornichenko Ilya 
