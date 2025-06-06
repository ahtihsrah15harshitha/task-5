# task-5
wireshark network traffic capture

🔧 Step 1: Install Wireshark
Download it from the official website: https://www.wireshark.org

Follow the installer and allow it to install WinPcap/Npcap (required for packet capture).

🌐 Step 2: Launch Wireshark
Open Wireshark.

You'll see a list of available network interfaces (like Ethernet, Wi-Fi).

▶️ Step 3: Start Capturing Packets
Select the network interface you want to monitor (e.g., Wi-Fi).

Click the blue shark fin icon (top-left) or double-click the interface to start capturing.

🔍 Step 4: Analyze Captured Packets
As packets appear, you can click on each row to view:

Packet Summary

Packet Details

Raw Bytes

🎯 Step 5: Use Filters to Find Specific Traffic
Wireshark captures everything, so filtering helps. Examples:

Filter	Description
http	Show only HTTP traffic
ip.addr == 192.168.1.5	Filter by IP address
tcp.port == 80	Filter by port
dns	Show DNS traffic
icmp	Show ping requests/replies

Type filter in the "Apply a display filter" bar and press Enter.

🧪 Step 6: Inspect Packet Details
Click on a packet to view protocol layers:

Ethernet → IP → TCP/UDP → HTTP (or other protocols)

Expand each section to inspect headers and values.

💾 Step 7: Save or Export Captures
To save: Go to File > Save As

File will be saved with .pcapng or .pcap extension.

🛑 Step 8: Stop Capture
Click the red square button to stop capturing.

HERE I USED LINUX IN BUILT WIRESHAK APPLICATION
