# small-business-setup-in-cloud-azure

Small business expansion (Noit Resources) into cloud
Initial draft
  1. Small engineering company (Noit Resources), recently expanded service and obtained a exclusive disributor license of a well      known engineering equipment system.
  2. Existing departments:
    1. Sales
    2. Engineering
    3. CEO's office
    4. HR
    5. Accounts
  3. Cloud resources (new resources)
    1. Specilized engineering VM (3rd party engineering software license)
    2. File server
    3. virtual network (with VLANS)    
  5. Hardwares (existing hardware, already configured)
    1. Laptops
    2. Printer
    3. File server
    4. Switches
    5. Router
    6. Modem
    7. Firewall 
  7. Subnet (already configured)
    1. VLAN 10 Sales
    2. VLAN 20 Marketing
    3. VLAN 30 Human Resource
    4. VLAN 40 Accounts
    5. VLAN 50 File Server
    6. VLAN 60 CEO's office
    7. VLAN 70 IT
    8. VLAN 80 Engineering  (new department)
    9. VLAN 90 IOT (Printers etc)
  9. Configuration / setup
    1. Office
      1. router
      2. firewall
        1. Reconfigure to allow site to site VPN to Azure
    2. Cloud Azure
      1. VM
        1. Basic setup: network etc
        2. Install 3rd party engineering software
        3. Install printer driver (allow printing at office's printer)
      2. Virtual network setup
      3. Network Security Group / Security Policy

Staff documentation update

Future upgrade
1. CCTV
2. Electronic attendance
3. 
