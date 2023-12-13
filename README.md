# brute_rpc
A bash script to compliment rpcclient to help brute force msrpc.
Thsi tools is to be used against authorized systems only, or for educational purposes!
I am not responsible for you breaking the law... Please know and understand the laws in your country!

Note: You must have rpcclient installed to use this tool.

Download:
git clone https://github.com/UbuntuStrike/brute_rpc.git

cd brute_rpc

Grant permissions:
chmod +x brute_rpc.sh

Usage: 
./brute_rpc.sh -t <target_ip> [-U <username> | -u <usernames_wordlist>] [-P <password> | -p <passwords_wordlist>] | -d <domain> | -c <rpcclient_command>

