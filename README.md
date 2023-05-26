# SEI-120G - (Tozed-based) - Network Unlock

## Payments:

<details>
<summary>Donations and Payments to Philippine-based EWallet</summary>
<p>
  <code>EWallet - Send Money</code>
  <br/>
  <br/>
  <code>Send Money: 09225205353 (GCash)</code>
  <br/>
  <code>Send Money: 09225205353 (Coins PH)</code>
  <br/>
  <code>Remittance: 09225205353 (7/11)</code>
</p>
<br/>
<p>
  <code>QR Code (EWallet / GCash, soon - Coins PH):</code>
</p>
<p>
  <img src="https://cdn.snowkel.us/cdn/images/gcash"></img>
</p>
</details>

## Releases Page:

* https://github.com/binarykorra/SEI-120G/releases/

## Basic Steps (Openline and Frequency Settings):

* Step (1): Advance Settings URL Addon - "mcc_mnc_locking/frequency" from "router_settings".
* Step (2): Input your Telecom PLMN Pin and Disable the MCC / MNC Unlocking Toggle.

## Advance Setups (Update Config):

* Step (1): Go to Router Settings Page, then click "DHCP" (1x) and edit "router_settings" to "backup_data"
* Step (2): Upload your Config from Releases Page download, then click Update.
* Step (3): Wait for Device / Router Restart or Reboot, then all the Settings should be Updated accordingly.

## Network Codes:

PLMNs:
* 51503 (Smart)
* 51505 (SUN / Digitel)
* 51502 (Globe)
* 51501 (Globe)
* 51566 (DITO)

## Accounts:

Default Account:
* Username:user
* Password:@l03e1t3

Admin (Black) Account:
* Username:admin
* Password:CP45HhBP

Admin (White) Account:
* Username:admin
* Password:EfkXhRHD

SuperAdmin (Black) Account:
* Username:sztozed
* Password:83583000

## Precautions (DIY)
A must do precautionary measure if your IMEI doesnt change by using the Firmware.
* Do an AT Command first via #send_at from your Mobile Browser by clicking DHCP (x1) from #router_settings
* Afterwards type this Command: AT^MODIMEI="new_imei" then Upload the Universal Firmware
* I just tested this earlier by Uploading the Firmware without AT+ Commands first

SuperAdmin (White:Universal_Firmware) Account:
* https://github.com/binarykorra/SEI-120G/releases/tag/LT90T_1.01.1_v02
* Username:sztozed
* Password:44433618

## For Future Preference:

* IMEI (860702049866890):

user > sztozed

pass > 44433618

* IMEI (860702048619878):

user > sztozed

pass> 43158149

* IMEI (860702043105386):

user > sztozed

pass > 48143168

## TZ_NVShow (DIY):
* imei=new_imei
* tz_sn_code=SEIT + new_imei

## Networking:

OpenPorts:
* 8357 (SSH)
* 4719 (Telnet)

## Notice:

How to get Admin Password via 192.168.254.254:
* http://192.168.254.254/goform/goform_get_cmd_process?isTest=false&cmd=admin_Password

## Copyright (2020)

( C ) - [BinaryKorra](https://github.com/binarykorra), 09225205353
