

```
Lab Report: Packet Tracer - Configure a Wireless Router and Clients

1.Objectives
My goal for this lab was to help my friend, Natsumi, set up her home network. This involved:

- Connecting all her devices, including the cable modem, wireless router, PCs, and a laptop.
- Configuring the wireless router's settings, like the DHCP server and a secure wireless network.
- Verifying that all her devices could connect to the internet.

---

2.Background
I was asked to help Natsumi set up a home network using a cable modem and a wireless router.  
The task involved connecting the physical cables and then using one of the computers to configure the router's settings.  
The final step was to test all the connections to make sure everything worked properly.

---

Part 1: Connecting the Devices

1. Cable Connections:
   - Used a `coaxial cable` to connect the `Cable Splitter` to the Cable Modem for internet service.
   - Used another coaxial cable to connect the splitter to the TV for video service.
   - Verified TV connection by turning it on and confirming a picture was displayed.

2. Network Connections:
   - Connected a straight-through Ethernet cable from the Cable Modem to the `Internet` port on the Home Wireless Router.
   - Connected:
     - `Office PC` to GigabitEthernet 1 on the router.
     - `Bedroom PC` to GigabitEthernet 2 on the router.



Part 2: Configuring the Wireless Router

Accessing the Router GUI
- Set the `Office PC` to DHCP → received an IP address automatically (confirmed wired connection working).
- Opened the web browser and entered the router's IP address (default gateway).
- Logged in with default credentials:  


`Username: admin`
`Password: admin`



Basic Router Settings
- In the `Setup` tab:
- Changed `Maximum Number of Users` to `10`.
- In the `Administration` tab:
- Changed default password to `MyPassword1!`.

Wireless LAN Configuration
- In the `Wireless` tab:
- Set `Network Name (SSID)` to `MyHome`.
- Configured `WPA2 Personal` security.
- Set passphrase to `MyPassPhrase1!`.



Part 3: Testing Connectivity

Laptop Connectivity
- Connected to `MyHome` wireless network using `MyPassPhrase1!`.
- Opened a browser and navigated to a webpage successfully.

Wired PC Connectivity
- `Office PC`: Verified internet access via browser.
- `Bedroom PC`:
- Set to DHCP → successfully received an IP address.
- Confirmed internet access via browser.



Conclusion
I successfully completed all the tasks. All devices were correctly connected, the wireless router was configured with secure settings, and every device—both wired and wireless—could access the internet.  
Natsumi's new home network is up and running perfectly. i even tried some ping command to confirm whether the devices are alsoconnected on the same internet which was also a success.
```
