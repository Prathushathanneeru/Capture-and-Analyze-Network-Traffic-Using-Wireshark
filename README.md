# Capture-and-Analyze-Network-Traffic-Using-Wireshark
The Wireshark is a network traffic analyzer.It capture packets and analyze them based on different protocols and networks.
# 1.Install the Wireshark
* Wireshark can be installed in windows/macOS/linux.
* It is free to iinstall.
* Visit the official Wireshark website: "https://www.wireshark.org/download.html" for installation as well as download.
# 2.Start Capturing on Your Active Network Interface
* Firstly,launch the wireshark in your device.
* You'll see a list of network interface like Wifi,ethernet,etc.
* If your device connected to Wifi the **double-click** on it.
* The packets will appears which are in the network.
# 3.Generate Traffic
* We can generate the traffic in wireshark by pinging the website or by web browsing.
* In command prompt we can type:
   - ping google.com
* Or we can browse a website ex:www.example.com
# 4.Stop Capturing After One Minute
* In wireshark tool the live packets are captured continuesly.
* To stop it,a rep square box is displayed on left-top side.
* If we click on it the capturing of packets is stoped.
# 5.Filter Captured Packets by Protocols
* In wireshark the packets are retrieved based on the protocols.
* On top a search bar is displayed in it we can define different protocols one at a time.
* For example: TCP,DNS,ICMP,HTTP, etc..  are searched only one at a time then bunch of packets are displayed which have same protocol.
# 6.Export the Capture as a .pcap File
* Steps:
    - Go to File > Export Specified Packets (or File > Save As).
    - Choose format: Wireshark/tcpdump/... - pcap (*.pcap)
    - Name the file, e.g., network_capture.pcap
    - Click Save
  
