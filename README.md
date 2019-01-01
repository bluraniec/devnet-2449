# devnet-2449
    This is a Git repository for the Cisco Live DevNet 2449 - Python for Enterprise Network Elements

About the session: 

Please Note: Seating for sessions in the DevNet Zone is available on a first come first seated basis. This session is designed to be small and hands-on. Laptops will be provided. Join us to get an overview of the Network Automation for Enterprise - one of the recent hottest topics. We will see NETCONF, YANG Data modeling and RESTCONF in action interacting with IOS-XE using Python scripting language. Attendees will learn how to gather network information and change configuration on devices in an automated way using netmiko, ncclient and requests libraries. Come and get your hands dirty! Takes place in DevNet Zone. 

- If you just want to read this executed Lab - go to the [DEVNET-2449 Lab Guide](https://github.com/bluraniec/devnet-2449/blob/master/DEVNET-2449.ipynb) and follow the notebook.

- If you want to do it in your own environment, make sure that you have done following steps:
  1. Run IOS-XE device (this Lab has been done on CSR running IOS 16.7.1). Please be advised that RESTCONF is oficially supported since version 16.6.1.
  2. Setup IP connectivity between the IOS-XE device and your local computer.
  3. Enable NETCONF (`#netconf-yang` command) and RESTCONF (`#restconf` command) on this IOS device.
  4. Download the repository.
  5. Download following Python modules (for example using `pip` command):
      - netmiko
      - ncclient
      - requests
      - pprint
      - pandas
  6. Download Jupyter Notebook to be able to open the .ipynb file locally - [Download](https://jupyter.org/install)
  7. Run Jupyter Notebook in Terminal using command: `jupyter notebook`
  8. Upload all files from respository to opened Jupyter Notebook (remember to keep the folder structure).
  9. From locally running Jupyter Notebook - click on (`DEVNET-2449.ipynb`) and play with the lab!
