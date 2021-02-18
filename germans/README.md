> ScaredDevWczoraj o 22:06

>  @なるみ For you if you don't know about Packets 

> 

> 8000+ size packets instant kick

> because hardly any packets reach this size at all

> and anything over 1000+ you will make a maximum of 5 packets with the size per second

> 
> The Client didn't sent more (legit) Packets & Size of them

#### Thats why written book(50 pages, max chars per page) in survival on server with 256 compression has ~13k bytes

---


> ScaredDevWczoraj o 22:07

> So now blazingpack obv. sent more packets than Legit why this? oh no Idk Shitty Client :open_mouth:

> @なるみ Look in Spigot.jar and find something about Packets/Network thats better for you :slight_smile: so please stfu.

#### Yeah i fucking looked at server code but i thinking you didn't

---

> ScaredDevWczoraj o 22:12

> Bro

> Packet Size (Bytes) != Book Size

#### Packets with itemstack yeah itemstack has nbt so packet size contains itemstack size and itemstack size contains nbt size

---

> ScaredDevDziś o 01:26

> did you even know what the difference is between readableBytes and bytes toArray ?

> i think no.

#### Using netty in minecraft server XD, i don't know what netty he uses

---

> ScaredDevDziś o 01:22

> oh man

![](https://images-ext-2.discordapp.net/external/FneUtFFPjN6Tcc0j0Hz7JrUiAl_x7RvSJMQkEXvWlxA/https/spielestu.be/s/Discord_Meoq8VoWRD.png)

> Thats not the PacketSize^^

> You didn't know what i'm checking for that so please stfu

#### packet splitter splits the packet before the decoder, so that's why the ByteBuf#readableBytes() method returns the correct value, but you're so retarded and didn't know that
