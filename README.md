# BulkIPOApply
All about how to apply bulk IPO using Android 

# BulkCLI

BulkCLI is a CLI application built on top of python which enables user to apply IPOs in bulk from multiple different accounts Using Android. In order to get started, consider the following steps:

## Step 1: Download and install Termux application from below link:
Download Link: https://github.com/termux/termux-app/releases/download/v0.118.0/termux-app_v0.118.0+github-debug_arm64-v8a.apk

After installation Run below commands:

## Step 2: Give Storage Permission to Application
 ```
termux-setup-storage
```
## Step 3: Update and Upgrade 
```
apt update && upgrade
```
**Note**: Enter `y` if processing stop
## Step 4: Install Git
```
pkg install git
```
**Note**: Enter `y` if processing stop

## Step 5: Install Python
```
pkg install python
```
**Note**: Enter `y` if processing stop

## Step 6: Clone the repo
First clone the repository into your system by using the following command:
```
git clone https://github.com/adars124/BulkCLI.git
```
**Note**: Enter `y` if processing stop

## Step 7: Install the requirements
Then, navigate to the folder where you have cloned this repo and install all the requirements using:
```
pip install -r requirements.txt
```
**Note**: Enter `y` if processing stop

This will install all the required libraries/modules into your system that will make the program work.


## Step 8: Modify the accounts.txt file using below command:
```
nano accounts.txt
```

The **accounts.txt** file contails dummy information in following format:

```
clientId, username, password, crn, pin
clientId, username, password, crn, pin
clientId, username, password, crn, pin
clientId, username, password, crn, pin
```
Change the information according to the respective name. You can follow the following approach:

```
# Should not contain spaces after comma
130,01234458,password@123,XYZ0231412,1234
```
Then press ```ctrl+s``` then ```ctrl+x```

**Note**:You can find the clientId in **capitals.json** file using below command:
```nano capitals.json```

press ```ctrl+x```

## Step 9: Run the **main.py** file
After all the aforementioned steps are successfully completed, you can run the **main.py** file using below commamd :
```
python main.py
```
#done✅
## Regular Process:
1) ```cd BulkCLI```
2) ```python main.py```
3) Enter S.N of share you want to apply
4) Enter Kitta then press `Enter`

And you are good to go. Enjoy using BulkCLI application. 😊
All Credit Goes to Github: https://github.com/adars124
