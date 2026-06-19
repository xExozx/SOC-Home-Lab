# SOC Home Lab

## Objective


Building a home lab to test malware in Windows 10 using linux. This will all be done in Virtual Box using virtual machines.

### Skills Learned


- Virtualization and configuring virtual machines.
- Linux administarion using linux command-line basics.
- Windows administration and configuration, looking at event logs.
- Networking Fundamentals.
- Using Splunk to see event logs on attacks.

### Tools Used


- Security Information and Event Management (SIEM) in Splunk.
- Using MSFVenom for malware attacks on linux.
- VMware.

## Steps
<img width="1106" height="892" alt="Downloaded vm kali linux and iso windows 10" src="https://github.com/user-attachments/assets/8eaa1379-a2d0-4fa9-b11b-4043b48fc57e" />

Ref 1: Downloaded vm kali linux and iso windows 10.

<img width="1072" height="882" alt="changing network to internal network" src="https://github.com/user-attachments/assets/402813dd-4de8-4ca0-a0ca-8a7d7772caca" />

Ref 2: Changing network to internal network.

<img width="1020" height="851" alt="manually changing ipv4 to 192 168 20 10" src="https://github.com/user-attachments/assets/cacd6644-a914-40b0-8698-648af4197b3b" />

Ref 3: Manually changing ipv4 to 192.168.20.10.

<img width="958" height="375" alt="network confirmation" src="https://github.com/user-attachments/assets/8d065078-cf01-4efc-abd5-0abae99e4e71" />

Ref 4: Network confirmation.

<img width="1280" height="878" alt="configuring ipv4 on kali" src="https://github.com/user-attachments/assets/bb6663e0-ef3d-4b11-bbb7-be9ebc6f5430" />

Ref 5: Configuring ipv4 on kali.

<img width="637" height="513" alt="if config to confirm change to ip address" src="https://github.com/user-attachments/assets/a40921b3-0b1f-4f46-9199-358fab405e8b" />

Ref 6: If config to confirm change to ip address.

<img width="1022" height="855" alt="connectivity for both mechines" src="https://github.com/user-attachments/assets/e7371b4a-f6c7-4c2e-88ea-4e6605f8e4e7" />

Ref 7: Connectivity for both machines.

<img width="1016" height="856" alt="taking snapshots for both machines just incase we break something" src="https://github.com/user-attachments/assets/a5fa2be2-e702-4382-9880-4ccf903b5663" />

Ref 8: Taking snapshots for both machines just incase we break something.

<img width="1017" height="855" alt="installed sysmon on windows" src="https://github.com/user-attachments/assets/75bafb97-738e-4e41-96bd-46f2949077cb" />

Ref 9: Installed sysmon on windows.

<img width="1018" height="851" alt="turned off windows defender" src="https://github.com/user-attachments/assets/3b13b496-123e-4bea-85c8-e785081d5702" />

Ref 10: Turned off windows defender.

<img width="1003" height="847" alt="downloading splunk onto windows 10vm" src="https://github.com/user-attachments/assets/278fe699-fc6c-494b-b70d-c11fc9d7c2ba" />

Ref 11: Downloading splunk onto windows 10vm.

<img width="1023" height="852" alt="adding event logs options" src="https://github.com/user-attachments/assets/1dbf3d0e-bf00-421a-bbc0-e9d2204eb215" />

Ref 12: Adding event logs options.

<img width="1015" height="847" alt="the review of data" src="https://github.com/user-attachments/assets/586d6228-7a7f-41e8-b10d-63eb84c3bd36" />

Ref 13: The review of data.

<img width="1018" height="851" alt="seeing events come up" src="https://github.com/user-attachments/assets/5bfadb7a-8329-4b26-85d6-6671c6b33318" />

Ref 14: Seeing events come up.

<img width="640" height="511" alt="seeing all the available options for nmap" src="https://github.com/user-attachments/assets/09477930-2e6b-46f4-9e60-7fb54ec6b1cb" />

Ref 15: Seeing all the available options for nmap.

<img width="645" height="505" alt="-A to scan everything and -pn to skip ping" src="https://github.com/user-attachments/assets/b09bfa3e-3ce1-4e17-beb8-52acf8a27539" />

Ref 16: -A to scan everything and -pn to skip ping.

<img width="640" height="507" alt="port 3389 rdp is open" src="https://github.com/user-attachments/assets/43091466-805e-46f1-8b30-40b2b5ef02f4" />

Ref 17: Port 3389 rdp is open.

<img width="642" height="507" alt="using msfvenom" src="https://github.com/user-attachments/assets/b34c8064-82fd-4227-a0d6-4db017381bf9" />

Ref 18: Using msfvenom.

<img width="646" height="58" alt="building out malware using interperture payload" src="https://github.com/user-attachments/assets/73fdc603-8206-4d05-973e-eacab1bc8c11" />

Ref 19: Building out malware using interperture payload.

<img width="612" height="60" alt="going to use this attack" src="https://github.com/user-attachments/assets/d68e041a-66c7-4e95-845a-725dba88af50" />

Ref 20: Going to use this attack.

<img width="930" height="47" alt="generate malware using meterpeter tcp payload to go to lhost and lport, file will be exe and filename will be resume pdf exe" src="https://github.com/user-attachments/assets/dd7d106a-26a3-4b40-94e6-7b46a8d782d0" />

Ref 21: Generate malware using meterpeter tcp payload to go to lhost and lport, file will be exe and filename will be resume.pdf.exe.

<img width="676" height="182" alt="ls to make sure file exist and what type of file we have" src="https://github.com/user-attachments/assets/f10883a9-759f-4dbd-8c62-293ca53950f5" />

Ref 22: ls to make sure file exist and what type of file we have.

<img width="605" height="403" alt="open handler that will listen in to the port in our malware" src="https://github.com/user-attachments/assets/d1f1f809-974e-410b-8489-a47c9bccdd48" />

Ref 23: Open handler that will listen in to the port in our malware.

<img width="302" height="17" alt="using multi handler" src="https://github.com/user-attachments/assets/3bb9e1b0-c316-4ad6-9f23-46989ab77d2c" />

Ref 24: Using multi handler.

<img width="620" height="437" alt="seeing my options in handler" src="https://github.com/user-attachments/assets/47626551-d1ff-4c2a-8717-bea4ae812f77" />

Ref 25: Seeing my options in handler.

<img width="666" height="22" alt="setting payload to msfvenom payload" src="https://github.com/user-attachments/assets/ead6ea5d-34b4-4e5b-b5b4-5b9480d303d1" />

Ref 26: Setting payload to msfvenom payload.

<img width="812" height="427" alt="options has changed to windows" src="https://github.com/user-attachments/assets/466bc727-d60f-4623-acde-b2a0073b788e" />

Ref 27: Options has changed to windows.

<img width="476" height="57" alt="setting lhost to target ip" src="https://github.com/user-attachments/assets/77ced6ba-b6f9-4d27-877e-048ebd6a788c" />

Ref 28: Setting lhost to target ip.

<img width="428" height="47" alt="setting lhost to attacker" src="https://github.com/user-attachments/assets/9e56ab21-5502-45d6-bb08-648689679f41" />

Ref 29: Setting lhost to attacker.

<img width="811" height="140" alt="lhost is now set to attackers ip" src="https://github.com/user-attachments/assets/b90f99fe-da76-4157-a231-4fa59d4866ae" />

Ref 30: Lhost is now set to attacker IP.

<img width="470" height="56" alt="started exploit" src="https://github.com/user-attachments/assets/c8ba32e8-38fa-4431-8792-26984889d386" />

Ref 31: Started exploit.

<img width="563" height="326" alt="setup a quick http server so our test machine can download malware" src="https://github.com/user-attachments/assets/32c17b25-d544-4561-8d17-0b482d45513d" />

Ref 32: Setup a quick http server so our test machine can download malware.

<img width="885" height="736" alt="disabled virus protection on windows and went to port 9999" src="https://github.com/user-attachments/assets/f4851241-2ed7-40da-b559-e5023e91312d" />

Ref 33: Disabled virus protection on windows and went to port 9999.

<img width="780" height="567" alt="exe is the true file extention, detectable by extending file name" src="https://github.com/user-attachments/assets/87a06971-2ddf-4575-8017-bd07849658c9" />

Ref 34: .exe is the true file extention, detectable by extending file name.

<img width="352" height="167" alt="want to see established connection to tlinux" src="https://github.com/user-attachments/assets/6fa6a9c8-f529-4fc6-b821-cf836018ccc7" />

Ref 35: Want to see established connection to linux.

<img width="607" height="42" alt="estableshed connection" src="https://github.com/user-attachments/assets/04f5757b-e546-45bc-a805-b2c54cfa20ee" />

Ref 36: Established connection.

<img width="641" height="18" alt="file virus shows in task manager" src="https://github.com/user-attachments/assets/3d0914d7-1d64-4940-9d41-41760c56ac8c" />

Ref 37: File virus shows in task manager.

<img width="887" height="98" alt="connection" src="https://github.com/user-attachments/assets/8c9e655c-e1ce-4ec0-9bc8-6f5ef021088f" />

Ref 38: Connection.

<img width="878" height="772" alt="restarting splunk with new edit file" src="https://github.com/user-attachments/assets/fd742c73-35f9-48c4-a628-e146556c9d01" />

Ref 39: Restarting splunk with new edit file.

<img width="916" height="815" alt="making new index " src="https://github.com/user-attachments/assets/85b1582c-22e1-4c03-a331-6d0e03253332" />

Ref 40: Making new index.

<img width="845" height="481" alt="index=endpoint showing target machine trying to get into 3389" src="https://github.com/user-attachments/assets/a8327306-894c-47ac-8530-47d07b566d48" />

Ref 41: Index-endpoint showing target machine tring to get into port 3389.

<img width="517" height="302" alt="13 events for resume pdf exe file" src="https://github.com/user-attachments/assets/6ecc88ec-8e7a-4993-8fcb-f2a675fb7123" />

Ref 42: 13 events for resume pdf exe file.

<img width="587" height="345" alt="proccess id and guid shown" src="https://github.com/user-attachments/assets/b4e5c63d-cb1d-4dec-83be-82181f0e2f31" />

Ref 43: Proccess id and guid shown.

<img width="560" height="183" alt="5 events showing through search result on guid" src="https://github.com/user-attachments/assets/e5005ac5-bb07-416e-aac6-d1486d008a1e" />

Ref 44: 5 events showing through seach results on guid.

<img width="905" height="337" alt="shows file, shows we used net user, net localgroup and ipconfig" src="https://github.com/user-attachments/assets/f624ae18-e596-426d-8acd-8703d322915c" />

Ref 45: Shows file, shows we used net user, net localgroup and ipconfig.









