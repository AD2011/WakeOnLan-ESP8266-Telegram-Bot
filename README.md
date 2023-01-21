# WakeOnLan-ESP8266-Telegram
Turn ON a Computer remotely from anyone in the world using Telegram and ESP8266 without being on the same network.

# Change the following values:  
  1. ssid[] =                                                      Wi-Fi Name
  
  2. password[] =                                                  Wi-Fi Password (Avoid using special characters)
  
  3. TELEGRAM_BOT_TOKEN =                                          Get from @botfater on Telegram
  
  4. targetDevice devices[] =                                      Replace MAC Address in this format (Get from typing ipconfig /all in cmd)
      {                                                            Device Name : MAC Address
      {{ 0xBC, 0x5F, 0xF4, 0xFF, 0xFF, 0xFF }, "Device 1"},        Device 1 : BC-5F-F4-FF-FF-FF
      {{ 0x04, 0xD9, 0xF5, 0xFF, 0xFF, 0xFF }, "Device 2"}         Device 2 : 04-D9-F5-FF-FF-FF
      };
      
  5. int numDevices = 2                                            No of devices connected above
