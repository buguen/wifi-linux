# Wifi-linux
Simple python script, which collects RSSI information about wifi access points around you and draws graphics showing RSSI activity.

Adaptation of the code for visualisation with pandas instead of gnuplot        
##Usage
./list_rssi.py 

After start you recieve an output of all access points around you.
After that you will be prompted for a command.
    plot
        draw an RSSI activity graphic for this moment since program start
    bp
        add a small breakpoint to a future graphic here
    stop
        stop the program
    start
        start timer and data processing
    start changer
        start data processing for every event on adapter
    print
        print rssi data

