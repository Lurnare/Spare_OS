<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSIWr4rXAYhnocOWjDcPri-NEpCN6trSnd02A&usqp=CAU">

# SmacKOS
This is SmacKOS, building it for learning purpose.

 Getting Started
---------------

To initialize your local repository, use command:

```bash
repo init -u https://github.com/Lurnare/Spare_OS/tree/SmacK.git -b arrow-13.0
```

Then sync up:

```bash
repo sync
```

Building the System
-------------------
 Initialize the ROM environment with the envsetup.sh script.

```bash
. build/envsetup.sh
```

Lunch your device after cloning all device sources if needed.

```bash
lunch arrow_devicecodename-buildtype
```

Start compilation

```bash
m otapackage
```

OR

```bash
m bacon
```

---------------------------------------------------------------------------------------------------------------------
