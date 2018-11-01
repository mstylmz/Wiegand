# 26 Bit Wiegand Protocol

What is the Wiegand Protocol? 

  Also known as the Wiegand interface, the Wiegand Protocol is a cabling standard for access control systems and card readers.

  Card readers are used to connect fingerprint scanners or other biometric readers to each other and to the rest of the access control       system.

How does the Wiegand Protocol work?

  In Wiegand format there are two data paths, Data0 and Data1. As shown in Figure 1.0, these paths are normally found at high levels and     fall to zero in the presence of information.

![wiegand](https://user-images.githubusercontent.com/10983937/47875633-1a885300-de28-11e8-9f97-8e2a65b8b202.jpg)

Figure 1.1 shows 26 bit wiegand format.There are parity bits in the beginning and the probe.Respectively, the first 13 and the last 13 bits are accompanied. The codes given as Site Code and User Code are special and general codes.For example, while Site Code shows the codes of a company, the User Code may show the personnel specific to that company.

![5b0d4b888362d40b148a658c_26bit-wiegand](https://user-images.githubusercontent.com/10983937/47875561-e876f100-de27-11e8-9954-b6b192cd2ddf.png)



![wiegand control](https://user-images.githubusercontent.com/10983937/47818922-1433a180-dd6a-11e8-847e-92920cf385d7.png)
