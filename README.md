# repiter-server-extcommands
control external relays board though gpio pins

To change the GPIO pin of the relay you need to change it the RELAY_{relay#}_on.sh and the RELAY_{relay#}_off.sh files 

on.sh file
gpio mode {GPIO #} out
gpio write {GPIO #} 0

off.sh file
gpio mode {GPIO #} out
gpio write {GPIO #} 1

change {GPIO #} to which ever gpio you are going to use
