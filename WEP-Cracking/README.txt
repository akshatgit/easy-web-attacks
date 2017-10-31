When Wi-Fi was first developed and popularized in the late '90s, security was not a major concern. Unlike wired connections, anyone could simply connect to a Wi-Fi access point (AP) and steal bandwidth, or worse—sniff the traffic.

The first attempt at securing these access points was termed Wired Equivalent Privacy, or simply WEP. This encryption method has been around for quite awhile and a number of weaknesses have been discovered. It has been largely replaced by WPA and WPA2.

The flaws in WEP make it susceptible to various statistical cracking techniques. WEP uses RC4 for encryption, and RC4 requires that the initialization vectors (IVs) be random. The implementation of RC4 in WEP repeats that IV about every 6,000 frames. If we can capture enough of the IVs, we can decipher the key!

You can use aircrack to crack WEP password.
