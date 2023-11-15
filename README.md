# Distributed-Data-Management

## Labs:
Data:
 10k_view_data.csv contains data about ‘viewing events’ - tuning a TV to a station:
• mso_code – unique 5-digit ID number for each MSO 
 • device_id – unique ID number for each device or set-top-box 
• event_date– date the viewing event occurred in the format “YYYYMMDD” 
• event_time – time the viewing event occurred in the format “HHMMSS” 
• station_num – ID of each TV station
 • prog_code – ID of each program broadcasted in each event

For both exercises below, we defined "Prime – Time" as the time between 20:00 and 23:00.
Map- Reduce Exercise:
1.	Find the most viewed program during Prime-Time hours, only from stations with even ID codes.
2.	Return the number of viewers (viewing events) that that program had, along with its program code.

Spark Exercise:
1.	Find the number of viewing events for each device in each day during Prime-Time.
2.	Use the number of viewing events of each device during Prime-Time to calculate the average amount of viewing events of each device during Prime-Time across all dates in the data.
3.	Return the devices and the average amount of viewing events during PrimeTime across all the dates in the data, of the 5 devices with the highest averages.

