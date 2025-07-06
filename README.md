# modbus_tcp_gateway
This project is set to receive the packet from the Cloud (TCP client). After mapping with a table in the SQLite at the TCP server, it is packaged in JSON format and sent to the RTU server through Redis Pub/Sub to get data. Finally, the data is returned back to the TCP client.
