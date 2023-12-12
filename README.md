<span style="font-size:2em; font-weight: bold;">API RTU Setup</span>

Last modified: Dec. 12, 2023

# USR N-510

## Status
- Model Name: USR-N510
- Firmware Version: V2.0.8
- Type: H7

## Network

>### IP Config
>- Method of IP Obtaining: Static IP
>- DNS: Auto
>- IP Address: 192.168.100.100
>- Subnet mask: 255.255.255.0
>- Gateway: 192.168.100.1
>- Preferred DNS Server: 192.168.63.1
>- Alternative DNS Server: 223.5.5.5

## Port
> ### Port1
>> #### Port
>>> - Baud rate: 9600
>>> - Data bits: 8
>>> - Parity: None
>>> - Stop bits: 1
>>> - Serial Mode: DIP Switch
>>> - Current Serial Mode: RS485
>>> - Flow ctrl: NONE
>>> - UART Packet Length: 0
>>> - UART Packet Time: 0
>>> - Sync Baudrate(RFC2217): ON
>>> - Enable UART Heartbeat: [ ]
>
>> #### Socket
>>> Socket A
>>>> - Working Mode: TCP Server / None
>>>> - Maximum Sockets supported: 16 / Exceeding Maximum: KICK
>>>> - Local Port Number: 23
>>>> - PRINT: OFF
>>>> - Modbus Poll [ ] / Response Timeout: 2000
>>>> - Enable Net Heartbeat [ ]
>
>>> Socket B
>>>> - Operating Mode: None
>
> ### Websocket to Serial
>> *Diagnostic Page*

## Gateway
> ### MQTT Gateway
>> #### Basic configuration
>>> - Enable MQTT: Disable
> ### Edge Computing
>> #### Setting
>>> ##### Edge Computing
>>>> - Enable Edge Computing: Enable
>>> ##### Data Acquisition
>>>> *Modbus-RTU slave addresses define page*
>>> ##### Data Query and Report
>>>> - Socket type: Socket1
>>>> ###### Data Query
>>>>> - Data Query: Enable
>>>>> - Query type: Json
>>>> ###### Data Reports of nodes
>>>>> - Reporting method: Enable
>>>>> - Periodic reporting: [v]
>>>>> - Reporting interval: 1
>>>>> - Reporting on regular: [ ]
>>>>> - Failure Padding: [v]
>>>>> - Content of Padding: null
>>>>> - Quotation Mark: [ ]
>>>>> - Json template: *report.json*

## Cloud Service
> ### USR Cloud
>> #### USR Cloud setting
>>> - USR Cloud: OFF
> ### Alibaba Cloud
>> #### Basic configuration
>>> - Enable Service: Disable
> ### AWS IoT
>> #### Basic configuration
>>> - Enable Service: Disable 

## System
> ### System Setting
>> #### System Setting
>>> - Model Name: USR-N510
>>> - Websocket Port: 6432
>>> - Websocket Direction: UART1
>>> - Webserver Port: 80
>>> - User Name: admin
>>> - UART Cache: OFF
>>> - Restarting Without Data: 0
>>> - SNMP: OFF
>>> - Telnet: OFF
>>> - NTP: ON
>>> - NTP Server Address: cn.ntp.org.cn
>>> - NTP Timezone Setting: UTC+9
>>> - 485 Anit-Collision: ON
>>> - 485-Idle Time: 10

> ### Management
>>> Firmware upgrade
>
>>> Reset
>
>>> Restart
>


--
