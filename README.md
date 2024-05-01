# Nework Analyser and Speed Test

This repository contains a network analyzer and speed test application built using Python and Streamlit. The application provides two main functionalities: packet capture for network analysis and speed testing to measure the download and upload speeds of your network connection.

# Features

1. Packet Capture: Analyze network packets flowing through your chosen interface. View source and destination IP addresses, protocol, and packet length.
2. Speed Test: Measure the download and upload speeds of your network connection using Speedtest.net.

# Prerequisites

Before running the application, make sure you have the following dependencies installed:

 - Streamlit: <code> pip install streamlit </code>
 - Psutil: pip install psutil
 - Speedtest-cli: pip install speedtest-cli

# How to Run
  1. Clone this repository to your local machine: <code> git clone </code>       
     <code> https://github.com/deepankarvarma/network-analyzer.git</code> 
  2. Install the required dependencies mentioned above.
  3. Navigate to the project directory: <code> cd network-analyzer</code> 
  4. Run the application: <code> streamlit run app.py</code> 
  5. Access the application in your web browser at <code> http://localhost:8501.</code>

# Usage
Once you launch the application, you will see a web interface with two options:

  1. Packet Capture: Select this option to capture and analyze network packets.

     - Choose an interface from the dropdown menu.
     - Click the "Start Capture" button to begin capturing packets.
     - The captured packet information will be displayed on the screen, including the source IP,       destination IP, protocol, and packet length.

  2. Speed Test: Select this option to measure your network's download and upload speeds.

     - Click the "Run Speed Test" button.
     - The application will perform a speed test using Speedtest.net and display the download          and upload speeds in Mbps.
