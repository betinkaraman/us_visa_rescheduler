# visa_rescheduler
The visa_rescheduler is a bot for US VISA (usvisa-info.com) appointment rescheduling. This bot can help you reschedule your appointment to your desired time period.

## Prerequisites
- Having a US VISA appointment scheduled already.
- [Optional] API token from Pushover

## Attention
- Türkiye Ankara and İstanbul embassy added in the embbasy.py file.
- To add a new embassy (using English), you should find the embassy's "facility id." To do this, using google chrome, on the booking page of your account, right-click on the location section, then click "inspect." Then the right-hand window will be opened, highlighting the "select" item. You can find the "facility id" here and add this facility id in the 'embassy.py' file. There might be several facility ids for several different embassies. They can be added too. Please use the picture below as an illustration of the process.
![Finding Facility id](https://github.com/Soroosh-N/us_visa_scheduler/blob/main/_img.png?raw=true)

## Initial Setup
- Install Google Chrome [for install goto: https://www.google.com/chrome/]
- Install Python v3 [for install goto: https://www.python.org/downloads/]
- Install the required python packages: Just run the bat file in the Microsoft Windows. Or run the below commands:
```
pip install requests==2.27.1
pip install selenium==4.2.0
pip install webdriver-manager==3.7.0
pip install sendgrid==6.9.7
```

## How to use
- Initial setup!
- Edit information [config.ini.example file]. Then remove the ".example" from file name.
- If webdriver can't find chrome driver, you can download it from [https://developer.chrome.com/docs/chromedriver/downloads] and extract it to repo folder. Just add driver path to config.json file (Chage to full path).
- [Optional] Edit your push notification accounts information [config.ini.example file].
- Run visa.py file, using `py visa.py` or `python3 visa.py`

## TODO
- Adding a GUI 
- Multi-account support (switching between accounts in Resting times)

