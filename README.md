pyever
======

Python command line tools to upload folders (contains text files) to evernote notebooks.

Usage
======

    %pyever your_local_folder

It creates a notebook in your evernote note store has the identical name with folder if not existing. All text file under your folder will be uploaded then and set to read-only. If you added new file locally, run this command again will
 
* add new notes 
* update old one if already uploaded


You should have a configuration file called ".pyever" under your home directory. 
Here is an example:


    [General]
    Mode=Product
    [Development]
    Token=S=s9:U=2db26:E=11aac8b87:C=1c2ff88:P=1cd:A=en-devtoken:V=2:H=b65fd57b3dfbd6287f0ae66af4d581
    [Product]
    Token=S=s7:U=3b4eb:E=11a938cf4:C=14c2e260f:P=1cd:A=en-devtoken:V=2:H=72d4d832d388732991d2c9acdf163f




