# MCParks Resource Pack Updated & Fixed
**All versions are converted from the original 1.12 pack by me even if an official version exists. If any issues are found, please report them so they can be fixed.**

This is an unofficial<sup> [1](1)</sup> updated version of the current MCParks resource pack including fixes for Minecraft versions after 1.12. 

The original 1.12 version is also included for the sake of consistency.

## Table of Contents
- [What's Fixed?](#whats-fixed)
- [Additional Info](#info)
- [Credits](#credit)
- [Disclaimers](#disclaimer)
## <a name="whats-fixed"></a>What's Fixed? <div style="text-align: right"> <a href="#top">ᴮᵃᶜᵏ ᵗᵒ ᵀᵒᵖ</a> </div>

This is stuff that has been changed or updated in this version of the resource pack compared to what's on the official packs.
**NOTE:** All images were taken in Minecraft 1.21.1.

- #### In 1.14+, item frames used for signs are no longer invisible. That is fixed in this version of the resource pack. 
  - Before ![2024-08-23_19 50 58](https://github.com/user-attachments/assets/d71092da-318b-4d7c-9fc9-336b61e88a0a)
  - After ![2024-08-23_19 51 56](https://github.com/user-attachments/assets/aa557639-69b3-4c53-a950-218e27be42fe)

- #### In 1.19.4+, many models stopped properly rendering their textures. This is fixed in this version of the resource pack.
  - Before ![2024-08-23_19 57 08](https://github.com/user-attachments/assets/bc451204-b18e-44f5-8e6b-bbae2e92ec51)
  - After ![2024-08-23_19 57 38](https://github.com/user-attachments/assets/f33e6702-25b7-4fbf-af90-6c38704a3efc)
  - Before ![2024-08-23_20 56 40](https://github.com/user-attachments/assets/3dd67cf9-a5ca-4de7-9e56-8f11a8de6699)
  - After ![2024-08-23_20 57 05](https://github.com/user-attachments/assets/ace8534a-d151-4bad-bbc8-3c8fd47f8e3f)

## <a name="info"></a>Additional Info <div style="text-align: right"> <a href="#top">ᴮᵃᶜᵏ ᵗᵒ ᵀᵒᵖ</a> </div>

### How are you updating the packs using a script?
On the backend, I'm using a tool called n8n to check if the resource pack has been updated. If it has been updated, it runs a few batch scripts that will:
  - Load the original 1.12 resource pack into a working folder
  - Add the resources to fix the invisible item frames<sup> [2](2)</sup>
  - Run the resource pack converter<sup> [3](3)</sup> to convert to 1.13.
  - Run an additional pass of resource pack conversions to tidy up anything left behind by the converter.
  - Package up the resource pack for deployment on Github
  - Repeat for each version 1.14+.

After this is finished, n8n uploads the updated files to Github.

### How long will it take you to update the packs here?
Generally speaking, if the MCParks official pack updates, it should also be updated here within an hour. Technically speaking, I am checking for a resource pack update every 30 minutes or so. Once an update is found, the scripts can take around 15-20 minutes to fully convert everything and upload it here. That said, errors can and will happen, so take this estimate with a grain of salt.

### Why haven't you provided the actual scripts?
Honestly... the scripts are quite a janky mess that I'm surprised work as well as they do now. They are also tailored to work on my PC and may not work on other PCs due to file directory issues. 

This is definitely fixable, but I don't have the time to really mess with it right now. A good place to start for anyone wanting to try updating a pack on their own is this<sup> [3](3)</sup> resource pack converter.

For the record, if the server operators would like a copy of the scripts I'm using, I can provide them, but for right now, I won't be releasing them otherwise.

### You took the screenshots from 1.21? How?
We all know that the reason MCParks works best on 1.12 is because that's the version of Minecraft the server is actually running. In order to allow newer clients to join the server, a plugin is used server-side. 

Since I am not affiliated with the server, I wouldn't know exactly which plugin is used, but a safe guess would be [ViaVersion](https://github.com/ViaVersion/ViaVersion) as it's popular among many servers.

Well, ViaVersion also has a mod that can be used clientside called [ViaFabric](https://modrinth.com/mod/viafabric). Using this mod on 1.19.1+, one can easily connect to MCParks even though these versions are unsupported.

## <a name="credit"></a>Credits <div style="text-align: right"> <a href="#top">ᴮᵃᶜᵏ ᵗᵒ ᵀᵒᵖ</a> </div>

<sup><a name="1">1</sup> I did not create any of the original resources in this pack - those were created by the staff at [MCParks](https://mcparks.us/).

<sup><a name="2">2</sup> The invisible item frame model was derived from [this resource pack](https://www.curseforge.com/minecraft/texture-packs/invisible-item-frames) made by [Matty Walker](https://www.curseforge.com/members/mattywalker/projects).

<sup><a name="3">3</sup> A large part of the conversion from 1.12 over to other versions was done through a [resource pack converter](https://github.com/agentdid127/ResourcePackConverter) made by [@agentdid127](https://github.com/agentdid127).

## <a name="disclaimer"></a>Disclaimers <div style="text-align: right"> <a href="#top">ᴮᵃᶜᵏ ᵗᵒ ᵀᵒᵖ</a> </div>

All updates are automatically generated by a script when it detects the MCParks pack has updated. This means that something can go wrong at any point within the process and prevent an update from being properly generated.
