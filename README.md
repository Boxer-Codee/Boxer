# What is Hound?
<p>Boxer is a tool that can remotely capture the exact GPS coordinates of a target device using a PHP server, and can also grab basic information about the system and ISP. This tool can be very helpful in information gathering. you can get following information of the target device</p>
<ul>
  <li>Longitude</li>
  <li>Latitude</li>
  <li>Device Model</li>
  <li>Operating System</li>
  <li>Number of CPU Cores</li>
  <li>Screen Resolution</li>
  <li>User agent</li>
  <li>Public IP Address</li>
  <li>Browser Name</li>
  <li>ISP Information</li>
</ul>

## Features
  <p>The tool offers a wide range of features and functionality, including:</p>
    <ul>
  <li>Capture Exact GPS Location</li>
  <li>Automated Data Collection</li>
   <li>User-friendly Interface</li>
</ul>

## This Tool Tested On :
<ul>
  <li>Kali Linux</li>
  <li>Windows(WSL)</li>
  <li>Termux</li>
  <li>MacOS</li>
  <li>Ubuntu</li>
  <li>Parrot Sec OS</li>
</ul>

## Installing and requirements
<p>This tool require PHP for webserver, wget & unzip for download and extract cloudflare. First run following command on your terminal</p>

```
apt-get -y install php unzip git wget
```

## Installing (Kali Linux/Termux):

```
git clone https://github.com/Boxer-codee/Boxer
cd Boxer
bash Boxer.sh
```
## Change log:
Version: 0.2: Remove Ngrok and update cloudflared tunnel


