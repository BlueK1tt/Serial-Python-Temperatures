# Serial-Python-Temperatures

Send just temperature data through serial comms.
 
> Example "raw" data coming through serial: ```22.75 ``` 

Need to edit the COM port identifier and serial baudrate based on the situation.

After that you can just run the python file in command line to read temperature.
When run, you can see couple reoccuring things in the terminal where file runs: ID, Time, Temperature

ID: The number of the read
Time: Time difference between current and last read
Temperature: Just the read temperature

Also when run the python code, it will show the port and the time when the code is run.

The more important is JSON file.

There is only two things "printed" in the JSON file, time and packet.
Time: the time when run
Packet: The packet contains two different information, Time difference and Temperature.

In the json file has example data of hours of reading temperature
