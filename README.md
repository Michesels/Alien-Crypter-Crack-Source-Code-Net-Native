# Ailen Crypter
A crypter constitutes a variant of software adept at encrypting, obscuring, and manipulating malicious software, thus heightening its resistance against identification by security applications. Cyber malefactors employ this tool to fabricate malware capable of eluding security applications by assuming the guise of an innocuous program until its installation is accomplished. Diverse categories of crypters find existence.      


## How to Use

- Download the project to your computer as zip
- Extract Project to Folder.
- Make Sure You Have Visual Studio Installed on Your Computer
- [Click if Visual Studio is Not Installed](https://visualstudio.microsoft.com/en/thank-you-downloading-visual-studio/?sku=Community&channel=Release&version=VS2022&source=VSLandingPage&passive=false&cid=2030)

### Compiling :
1. Open the solution file (.sln).
2. Select **Build Solution** from the **Build** menu or press `Ctrl+Shift+B` to compile the project.
3. When the build is complete, select **Start Without Debugging** from the **Debug** menu or press `Ctrl+F5` to run the project.

## Operational Mechanism

### Constructor
The constructor serves as the tool that empowers you to personalize and forge the Crypter Ransomware. Several of the configurations you can define incorporate:

- Icon for the Executable Binary File
- Title/Heading for the Graphical User Interface (GUI)
- Font and Background Color for the GUI
- Bitcoin Wallet Address
- Ransom Fee
- Ransom Message
- Stipulated Time for Payment
- Eradication of File Shadow Copies
- File Types to Undergo Encryption

and an array of additional facets. Once these parameters are established, a mere press of the <b>BUILD</b> button suffices to engender the executable.


### Ransom Operation
Upon activation, Crypter shall undergo the ensuing sequence:

- Production of an AES-256 bit encryption/decryption key and its inscription into key.txt within the prevailing directory
- Quest for pertinent destinations (comprising network drives, user repositories, etc.) in pursuit of files that align
- Encryption of all located congruent files
- Presentation of the Crypter Graphical User Interface (GUI) to the afflicted party

##Legal Notice

<p>
Crypter is designed exclusively for educational and investigative intentions. Its utility should be confined to systems or networks where you possess legitimate authorization. It must unequivocally not be employed for any unlawful or illicit endeavors. The author relinquishes any accountability for potential harm that might ensue from the utilization of the software found within this repository.
</p>