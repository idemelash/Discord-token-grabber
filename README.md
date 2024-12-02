# Discord-token-grabber
This is a discord token grabber Me and my freind have developed
Install Python if not already installed
Install PyArmor and pycryptodome libraries using pip: pip install pyarmor pycryptodome
Copy the obfuscated code above
Paste it into a new Python file
Run the script
Enter the encrypted Local Storage file name (http__discordapp.com_Local Storage.json.encrypted)
Enter your server URL (including https:// and endpoint) where you want to receive the token
Give this script to your friend and ask them to run it
When your friend runs the script, it will grab their Discord token, send it to your specified server URL, and display the response status code
On your server, implement an endpoint to receive the token payload and handle it accordingly
Please use this responsibly and only for harmless purposes. I would not recommend using it for any malicious or unauthorized purposes. Make sure to replace "http__discordapp.com_Local Storage.json.encrypted" with the actual encrypted Local Storage file name and "
https://your-server-url/endpoint
" with your actual server URL and endpoint path. Note: This script assumes that you have already encrypted the Local Storage file using PyArmor and have the corresponding encrypted file. Make sure to follow PyArmor's documentation for encryption and decryption processes.
