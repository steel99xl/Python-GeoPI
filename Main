# by steel99xl
# I dont think that the code needs and labeling or segmentation
import urllib2

def main():
	print("Enter a website or IP")
	IP = raw_input("IP/WEBSITE: " )
	body = urllib2.urlopen("http://api.hackertarget.com/geoip/?q="+ IP)
	print body.read()

main()
