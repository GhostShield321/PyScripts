#Author: Othmane Ait Bouftass
import os
Interface = input("-Interface: ")
Mac = input("-New MAC Address : ")
os.system("ifconfig " + Interface + "down")
os.system("ifconfig " + Interface + "hw ether " + Mac)
os.system("ifconfig " + Interface + "up")
print("[+] Your MAC Address Has Successfully Changed To => %s" % (Mac))
