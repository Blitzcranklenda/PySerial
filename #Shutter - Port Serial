import serial

ser = serial.Serial(port='/dev/ttyS0',baudrate=9600,parity=serial.PARITY_ODD,stopbits=serial.STOPBITS_TWO,bytesize=serial.SEVENBITS)

if ser.isOpen():
    print('Opened!')
else:
    print('Closed!')
ser.close()

command = input('Enter with a command\n 1 - Open Shutter\n 2 - Close Shutter\n 3 - Get out\n')

if command == '1':
    print("Shutter Opened!")
if command == '2':
    print('Shutter Closed!')
if command == '3':
    exit()

