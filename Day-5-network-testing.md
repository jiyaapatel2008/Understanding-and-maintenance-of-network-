Day 5: Network Testing Practical

Task 1: Connect Devices to the Same Wi-Fi Network

Connect my laptop and a friend’s phone to the same Wi-Fi network.

On Windows, open Command Prompt and type:

ping IP_ADDRESS

Replace IP_ADDRESS with the friend’s phone IP address.

If replies are received, the devices can communicate. If the request times out, check the Wi-Fi connection and device settings.

Task 2: Run Traceroute

On Windows, open Command Prompt and type:

tracert www.youtube.com

On Mac or Linux, type:

traceroute www.youtube.com

This command shows the network hops taken to reach the destination.

Task 3: Disconnect One Device

Disconnect the phone from Wi-Fi and run the ping command again.

If the phone is unreachable, the ping may show a request timed out message. However, this can also happen because of firewall settings or network restrictions.

Task 4: List IP Addresses of Connected Devices

On Windows, open Command Prompt and type:

arp -a

This command displays IP addresses and corresponding MAC addresses of devices recently discovered on the local network.

The list may not show every connected device.

Task 5: Network Testing Report

Objective

To connect devices to a network and test connectivity using ping and traceroute.

Procedure

1. Connected the laptop and phone to the same Wi-Fi network.
2. Checked connectivity using the ping command.
3. Used tracert to observe the route to a website.
4. Disconnected the phone and tested connectivity again.
5. Used arp -a to view discovered devices on the local network.

Results

Ping can be used to check whether a device responds to network requests. Traceroute shows the route towards a destination. The ARP table displays locally discovered IP and MAC address mappings.

Conclusion

Network testing commands help identify connectivity problems and understand how devices communicate over a network.

Note: Actual results depend on the network and device settings. Run the commands and add screenshots of your own results before submitting.
