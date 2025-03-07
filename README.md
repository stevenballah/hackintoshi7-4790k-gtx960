# hackintoshi7-4790k-gtx960
High Sierra on i7 4790k and GTX 960

Download macOS from [gibMacOS](https://github.com/corpnewt/gibMacOS)
Choose High Sierra Recovery

# Recovery Server could not be contacted fix.
Open Terminal and run this command
`nvram IASUCatalogURL="http://swscan.apple.com/content/catalogs/others/index-10.13-10.12-10.11-10.10-10.9-mountainlion-lion-snowleopard-leopard.merged-1.sucatalog"`
NOTE: We changed the URL from https -> http

Ensure you are connected to the Internet and continue with Installation.



# POST INSTALLATION
Since we just installed macOS High Sierra the build is usually the old version `17G66`. You need to download the High Sierra Security Update from Apple [here](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://support.apple.com/en-us/106508&ved=2ahUKEwjO_qS02_aLAxWmSmwGHfocCcoQFnoECBMQAQ&usg=AOvVaw2cOg48nLk3ZJ28G0rRa85O) and reboot and then you can check the build version here.
![image](https://github.com/user-attachments/assets/5f1e5cc2-f955-4316-ae16-7acb2c92777a)

My build is `17G14033` so I need to go to the nvidia drivers found [here](https://gfe.nvidia.com/mac-update) and CTRL - F to find the nvidia driver I need to download, once you reboot your computer your graphics should be working.
