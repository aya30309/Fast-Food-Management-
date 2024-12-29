## Overview
A simple fast food management system built using Flask and SQL Server.

## Features
- Manage products, carts, and orders.
- Integrated with a SQL Server database.
- Dynamic web interface.

## Requirements
- Python 3.8+
- Flask
- SQL Server
- install pyodbc

## Connection With Database 
- change Server name and Driver in connection string 
- conn = pyodbc.connect('Driver={YourDriverName};'
                    'Server=YourServerName;'
                    'Database=DatabaseName;'
                    'Trusted_Connection=yes;')
  
