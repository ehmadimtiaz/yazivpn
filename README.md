# YaziVPN.
Android VPN app based on openVPN Library.

![Main UI](https://user-images.githubusercontent.com/68849516/129557112-3184e3c5-f92a-43bd-9c7b-be8cce7318a1.png)


## Instructions to update servers:
  **Step 1:** Add/Update your ovpn file in assets directory.
  
  **Step 2:** Go to MainActivity.class file and find method "getServerList()" and update/add your server information. The server information has server icon image,       server ovpn file, server username and password. Add/Update all these.
  
  ![Step 1 (1)](https://user-images.githubusercontent.com/68849516/129557745-6cba44c7-3452-4146-b0df-2d901c77594a.png)

  
  (If you have changed or deleted default Japan sever than follow the step 3 otherwise skip it)
  
  **Step 3:** Go to SharedPreferences.class file and Add information (icon of server, ovpn file name, server username and password) of anyone of your server (which   will be used as default server).
  
  ![Step2](https://user-images.githubusercontent.com/68849516/129558616-fc8d293e-2a6c-425c-85c8-2bac9a3c7343.png)

  Thats all.
