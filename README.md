# Kali-linux-installation in vmware & virtualbox
## There are two type of virtual machine 
### 1. Vmware
### 2. Virtualbox

## Stable iso of kali 
:point_right: [ Kali stable iso ](https://old.kali.org/kali-images/kali-2022.4/kali-linux-2022.4-installer-arm64.iso)

:point_right: [ Kali main page](https://www.kali.org/get-kali/#kali-platforms)

## Let start with the installation of kali-linux in Vmware first :
## Vmware workstation pro 17 download link 
:point_right: [Vmware workstation pro 17 for windows](https://www.vmware.com/go/getworkstation-win)

:point_right: [Main page](https://www.vmware.com/in/products/workstation-pro/workstation-pro-evaluation.html)


## In process of installing it will ask u license key.
### Here is the license key :
```bash   
4A4RR-813DK-M81A9-4U35H-06KND
```
```bash
NZ4RR-FTK5H-H81C1-Q30QH-1V2LA
```
```bash
4C21U-2KK9Q-M8130-4V2QH-CF810
```
```bash
4Y09U-AJK97-089Z0-A3054-83KLA
```
```bash
MC60H-DWHD5-H80U9-6V85M-8280D
```
```bash
JU090-6039P-08409-8J0QH-2YR7F
```
## After installing Vmware and kali iso , let get started :

## Step 1. Open vmware workstation 17. 

![Screenshot 2023-10-19 121511](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/7243278e-7917-4f9f-a093-cc0266630548)

## Step 2. Tap on creat a new Virtual machine 
- select ```Typical``` (recommanded)
-  tap on ```Next```

![Screenshot 2023-10-19 121523](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/3ad07cd6-19d5-430d-83ba-07a0d3f81de5)

## Step 3. Select kali iso :
- Select second options  ```installer disc Imge file (iso)```
- tap on browesr
- Select iso from you local storage
- Then ```Next```

 ![Screenshot 2023-10-19 121537](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/9b6caaa8-9424-4268-b8d2-3e243d198ec8)

## Step 4. OS and Version
- It will auto detect version and os.
- Just tap on ```Next```
  
![Screenshot 2023-10-19 121550](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/b6941e00-d7c9-4ebf-ae05-d69c359ac0e1)

## Step 5. Give Name to your virtual machine / u can change loaction
- change loaction if u want
- write name 
- tap ```Next```
  
![Screenshot 2023-10-19 121626](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/d88386a0-8787-4fa3-9565-e8d0f433c557)

## Step 6. Give Disk size 
- i will reccomand u between 30 gb - 128 gb
- tap on ``Next```
  
![Screenshot 2023-10-19 121707](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/10327b5a-a554-4f89-8dae-c72df49bc9cc)

## Step 7. Finish 
- tap on ```finish```.
  
![Screenshot 2023-10-19 121755](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/fb26fbee-9080-4bf1-a9c0-bc4a5f4ee4b9)

## Your virtual machine is created successfully

![Screenshot 2023-10-19 121814](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/69f98c09-7ab1-4903-8f56-3d564e8702a9)

## Before opening it We need to do some changes.

- Tap on ```Edit virtual machine setting```

![Screenshot 2023-10-19 121825](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/99dcf3a2-b76e-407e-8235-b4e33d2db616)

- Go to ```network adapter```
- enable ```bridge connection```
- select ```Replicate physical network```

![Screenshot 2023-10-19 121833](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/e3ff123f-9239-451d-acd2-6cd98a2c0694)

- U can Increase Processor and Memory according to u .

# Edit virtual Network setting
- Go to Top left corner

![Screenshot 2023-10-19 121850](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/4d570a5f-4699-4f86-8a9a-79b0fbfd42f8)

- Tap on ```edit```
- Tap on ```virtual network editor```

![Screenshot 2023-10-19 121858](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/a34be3d2-3b6f-4e9e-aa3a-cdaa065f61a8)

- Tap on bottom left ```change setting```
- Give permission

![Screenshot 2023-10-19 121913](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/a7fb637e-128d-4961-a12f-eef09b1e4397)

- Tap on ```Restore default```


![Screenshot 2023-10-19 123107](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/9a98abf0-99fc-4a02-83cc-2089a60b561d)

![Screenshot 2023-10-19 123119](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/17c80f91-651b-4eaa-9b00-eb5642d2e836)

## Why im doing this :
### basicaly vmware workstation 17 has a issue with bridge adapter . bridge connection allow u to jump from one network to another (simple way u can't use tool like nmap its required --bridge connection only to scan ports) . At NAT vm work as router for more detail search by your self.





![Screenshot 2023-10-19 122245](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/9befed54-dc08-4b5a-b14c-8b83be80b650)

# Power on ur virtual machine 
- tap on Power On this virtual machine

![Screenshot 2023-10-19 122024](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/5de8261d-100b-4f7f-84b6-1b0e57bf90c0)

# Let install kali linux 
## This process Must be same for both vmware and virtaul box 

## step 1. Graphical install

- tap Enter on screnn Your mouse should be lock.
- to release mouse in Vmware press left ```alt``` + ```ctrl```.
- to release mouse in virtualbox press right ```ctrl```.
- OR use direcectly ```up``` / ```down``` key for next line use ```Tab``` key.
- We going to install it in Gui mode.
- Tap on graphical install.
  
![Screenshot 2023-10-19 122109](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/9e9fe2f3-ebbd-4a68-9f54-6c1ae06857cd)

## step 2. Select Langusage 

![Screenshot 2023-10-19 122147](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/a312e9e1-7190-4740-98af-bf0bbb02662c)

- tap on ```contine``` to go to next page (use tab key )

## step 3. Select country

![Screenshot 2023-10-19 122203](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/24670340-427d-435d-9efb-e08be37baeac)

## step 4. Select keyborad language

![Screenshot 2023-10-19 122231](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/f9df2609-a8ad-4eaf-8702-03bc9967d448)

- it take few seconds.
- 
![Screenshot 2023-10-19 122245](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/d9ac63ce-8646-4475-81a3-2a7ccc5a60e4)

# Note if u face Dhcp issue like this :

![Screenshot 2023-10-19 122914](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/41b59ffe-20cc-4205-a4cb-77c48cb9d2ce)

- To fix it
- poweroff ur machine.
  
![Screenshot 2023-10-19 123042](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/b35623a9-0bf9-40aa-ba3b-81e17167fb46)

- tap right side of two orange bar little trainage.
- it will open there is a option to power off tap on that.
- Repeat step of  ```Editing Virtual Network setting```.
- again restore network adapter.
    
![Screenshot 2023-10-19 123025](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/0d90fba0-ed2d-4eb1-aea3-932ef663e27c)

## step 5. Give Hostame 

![Screenshot 2023-10-19 124331](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/45472fcb-b574-4524-9d9d-f98203c78644)

## step 6. Domain Name (optional)
![Screenshot 2023-10-19 124349](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/3ea1bf74-448b-493d-a76d-fde8e7af418a)

## step 7. full Name 
![Screenshot 2023-10-19 124430](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/19c6cf46-5f1c-4727-8eb6-53a0010d42e7)

## step 8. Username
![Screenshot 2023-10-19 124446](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/7951211c-d406-4b2a-9e39-c68f9fae7b7e)

## step 9. Password 
![Screenshot 2023-10-19 124505](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/fb87040f-8d97-4b60-8bcc-47b77e5ee599)

## step 10. Partition disk
![Screenshot 2023-10-19 124629](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/ea9d8640-a4cc-43c4-a5c5-41dd1e767dfe)

- I am going to do it manually.
  
![Screenshot 2023-10-19 124612](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/cf01e959-a7b7-4c5c-8dd1-7b7a6ff73b8e)
- Tap on SCSI3 / third options.

![Screenshot 2023-10-19 124639](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/fb1cea3a-1408-4a5f-a25c-9fa5ef8597c9)

- ```enter```
- ```yes```
![Screenshot 2023-10-19 124651](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/080cddb3-8250-441b-9bfd-d6e880a9d96a)

- You see another option is pop up.
- ```enter``` in it.
![Screenshot 2023-10-19 124710](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/ad52e2c5-bfce-4080-afd2-1d0bc4f14aed)
- select ```creat a new partition```
![Screenshot 2023-10-19 124720](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/26e87888-fcd1-4758-be44-ad551727b898)
- select ```primary```
![Screenshot 2023-10-19 124754](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/484a3dcc-09bf-4e58-b51f-d59031e4fd37)
- Give according to u
- my recommendation 500 mb to 2 gb.
![Screenshot 2023-10-19 124746](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/48cfe56a-676d-414b-9b9e-35061202eddb)
- select ```beginning```
![Screenshot 2023-10-19 124806](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/beb29372-765a-45aa-b5d5-85e22afae405)

- Select ```use as :```
![Screenshot 2023-10-19 124817](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/22f3fa5e-32ba-4969-9b62-7c4f8856ed93)
- change it to ```Swap area```.
![Screenshot 2023-10-19 124830](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/fb40135d-7150-406c-8f6b-62b83a299caa)
- turn on ```bootable flag```
![Screenshot 2023-10-19 124845](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/60ac72e1-0b15-4c90-8253-e77c1ca0165c)
- select ```done setting up partition```.
- Select ```pri/log```
![Screenshot 2023-10-19 124901](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/b3e73382-75ae-40ed-b1c5-577d87971194)
- Again  select ```creat a new partition```
![Screenshot 2023-10-19 124912](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/e1b7dc9e-5722-4caa-8119-0105f1fc2ad4)

- Select all as default
![Screenshot 2023-10-19 124939](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/a077249e-f135-4749-839c-9b283c83c5fd)

![Screenshot 2023-10-19 124928](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/7641a201-6e16-412e-8718-a9469fe3ed0d)

- Just turn on ```bootable flag```
- select ```done setting up partition```.
![Screenshot 2023-10-19 124951](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/14200e16-3be0-4363-a1db-39f89ed2d56e)
- Select ```Finish partition and write change to disk```
![Screenshot 2023-10-19 125032](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/7390b2f2-4456-4ac1-8627-713ce0a7add1)
- tap ``yes``
![Screenshot 2023-10-19 125041](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/0809c275-0298-4809-bf9d-564f9ede8ab3)
- It going to install it.
![Screenshot 2023-10-19 125054](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/82f22df3-638d-436f-ac39-77f3ff1f1675)
## step 11. Display type
- I am going use ```KDE Plasma``` you can choose ```GNOME``` also.
![Screenshot 2023-10-19 130210](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/949111f5-e51b-4ba3-bfa6-3971e1a613df)
- It going to install software
![Screenshot 2023-10-19 130240](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/47619d27-9434-44a0-a62b-3a03b93d8106)
- for ```KDE plasma``` select ```ssdm```
- for ```GNOME``` select ```Gdm```
![Screenshot 2023-10-19 131636](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/2816b684-7108-4dd3-be08-2df300ea627d)
 - It took to much time to setup
 - After that it ask to install ```GURB``` just install it.
 - tap on ```yes```
![Screenshot 2023-10-19 135153](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/e9145ab0-3169-407d-8d09-d029b8164a4a)
- Select ```dev/sda```
![Screenshot 2023-10-19 135244](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/733a85ea-89d3-4fab-8808-d912be1fbdb5)
- it took few mintute to complete it.
![Screenshot 2023-10-19 135407](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/253e272d-0fb1-4df5-890b-0d9be7598e5e)
- Tap on ```continue``` to reboot system.
![Screenshot 2023-10-19 135913](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/36d1d5e6-ffb3-4bac-896a-528486caebb6)
- Hit ```enter``` 2 times the it going to booting up.
![Screenshot 2023-10-19 171628](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/13dd81e9-0266-4dcc-9a6f-a8524ea3ca07)

- Type your created password
![Screenshot 2023-10-19 140036](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/d4cd75a0-f612-42c4-a660-4590bfc4ef7b)
- You login into kali
![Screenshot 2023-10-19 140135](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/15f984cb-dfcf-4ee9-ad29-629c817a6d85)

#### To shutdown
```bash
init 0
```
# Let start with the installation of kali-linux in Virtualbox:
## Virtualbox download link download both :
:point_right: [Virtualbox](https://download.virtualbox.org/virtualbox/7.0.12/VirtualBox-7.0.12-159484-Win.exe)
:point_right: [virtualbox extention pack](https://download.virtualbox.org/virtualbox/7.0.12/Oracle_VM_VirtualBox_Extension_Pack-7.0.12.vbox-extpack)
👉 [Main page](https://www.virtualbox.org/wiki/Downloads)
## Install Virtualbox First then install extention pack to ypur system 
### Step 1. Open Virtual box

### Steo 2. Tap on ```New```
![Screenshot 2023-10-19 173536](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/5f6de874-c892-458f-8007-d93ca8875cee)
### Step 3. Give Name and Select Iso.
- it auto detect iso
![Screenshot 2023-10-19 173558](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/3cbf9835-f046-463c-8b02-c1a07d90d814)

### Step 4. Give disk space.
- recommended 30gb to 128gb.
![Screenshot 2023-10-19 173623](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/dac1b005-c971-42bd-b3b3-0c72b67d9727)

### step 5. Memory and processor 
- least 4 processor and 2 gb memory.
![Screenshot 2023-10-19 173613](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/5957d26b-d21d-43cc-bc23-dde69862ca94)
### Step 6. Finish
![Screenshot 2023-10-19 173633](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/0a482c8e-d607-4300-a29a-71db7aa8e769)
### Step 7. Setting virtual machine 
- Tap on virtual and tap on ```setting``` on top
![Screenshot 2023-10-19 173637](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/22589268-2fef-4749-a6b3-7d5285331dae)
### Step 8. Debian 11 
![Screenshot 2023-10-19 173647](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/fa781fb6-b2b5-4e63-a03e-b29534912a3e)

- Tap on ```general``` change ubutnu to ````debian 11 bullseye````
![Screenshot 2023-10-19 173657](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/7b4d4450-9b77-47da-a680-703a36c10ed8)
- Tap on ```Advance``` change drag and drop and share clipboard to ```bidirectional```
![Screenshot 2023-10-19 173707](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/1a9fb245-8220-4d46-bde5-243ed98d1c32)

### Step 9. GPU
- Tap on ```Display``` enbale ```3D acceleration```
- It take ur gpu + cpu to make Virtual Machine faster
![Screenshot 2023-10-19 173730](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/53fcb6fd-d567-4314-8436-09e2c66073e5)
### Step 10 . Network Adapter
- Tap on ```Network``` change it to ```Bridged Adapter```
![Screenshot 2023-10-19 173739](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/b97f0daf-3787-48b1-8449-8966a58c90d8)
### Step 11. Start virtual machine
![Screenshot 2023-10-19 173746](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/93248693-2d42-4d21-b3fe-e4fa1e8a3c75)
### Step 12. Tap on Show

![Screenshot 2023-10-19 173820](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/6078d6b4-db74-4b6e-888f-502739641c4b)
### Step 13. Configure it like all :
![Screenshot 2023-10-19 173829](https://github.com/Esther7171/Kali-linunx-installation-in-vmware-virtaulbox/assets/122229257/e7ab903a-0d95-4d59-8039-5991ac402912)
# After installing if u dont get a full screen
[click here ](https://github.com/Esther7171/virtualox-fullscreen/blob/main/README.md)
### Thankyou
