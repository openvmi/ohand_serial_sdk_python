# ROH Serial API Example

Example for ROH simple control.

## 1. Install PCAN Driver

Download from [PCAN Drivers](https://peak-system.com.cn/driver/) according to your system.

## 2. Preparation

```BASH
pip install -r requirements.txt
```

## 3. Run

* Open the `simple_control.py` file and modify the communication interface and device address as needed, for example:

```python
PORT_TYPE = PORT_UART
ADDRESS_HAND = 2
```

* Run the program:

Windows:

```python
python simple_control.py
```

Linux:

``` BASH
sudo chmod o+rw /dev/ttyUSB0
python3 simple_control.py
```

* Press 'ctrl-c' to exit the program.
