# datasets-Wi-SUNChannelModel-energies2022

All Raw Data are received packet datas in each alias at the experimental area.
 
1. Table 2. The studied data rates and frequency bands of 2FSK PHY layer in Thailand

|Frequency (MHz)|Data Rate (kbps)|Channel Spacing (kHz)|   Alias     |Transmit power (dBm)|
|:---: |:---: |:---: |:---: |:---: |
|    433.92     |    50	        |   200 	              |2FSK-433-50  |	    10             |
|    433.92     |    100	       |   400 	              |2FSK-433-100 |	    10             |
|    433.92     |    200	       |   400 	              |2FSK-433-200 |	    10             |
|     443	      |    50	        |   200 	              |2FSK-443-50  |	    10             |
|     443	      |    100	       |   400 	              |2FSK-443-100 |	    10             |
|     443	      |    200	       |   400 	              |2FSK-443-200 |	    10             |  
|     448	      |    50	        |   200 	              |2FSK-448-50  |	    10             |
|     448	      |    100	       |   400 	              |2FSK-448-100 |	    10             |
|     448	      |    200	       |   400 	              |2FSK-448-200 |	    10             | 
|     923	      |    50	        |   200 	              |2FSK-923-50  |	    20             |
|     923	      |    100	       |   400 	              |2FSK-923-100 |	    20             | 
|     923	      |    150		      |   400 	              |2FSK-923-150 |	    20             |
|     923	      |    200	       |   400 	              |2FSK-923-200 |	    20             |  
|    2440	      |    50	        |   200 	              |2FSK-2440-50 |	    5              |
|    2440	      |    150	       |   400 	              |2FSK-2440-150|	    5              | 
|    2440	      |    200	       |   400 	              |2FSK-2440-200|	    5              | 
    
2. The Structure of received packet

|Time         | Length |Preamble Bytes | Packet Data                      | RSSI  | CRC result |
|:---: |:---: |:---: | :---: |:---: |:---: |
|11:23:31.284 | fa     | 0000          | c6 7e 81 6b 4b fb e2 .... 63 44  |  -76  |            |
|11:23:31.799 | fa     | 0000          | c6 7e 81 6b 4b fb e2 .... 63 44  |  -77  |            |
|11:23:32.315 | fa     | 0000          | c6 7e 81 6b 4b fb e2 .... 62 e2  |  -81  |  CRC error |
