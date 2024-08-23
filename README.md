# simple-line-notification
simple line notification that connect with google sheet and use App script as timer I make for mom

I boiled down a lot and make it really simple by using google sheet.

![image](https://github.com/user-attachments/assets/d3f09749-ac4d-4921-a1be-3089bea18bdf)

Step 1 : go to line notify and login to grab token for chat you want to use.
Name you write here will also be putting on notification too 

![Pasted image 20240824020805](https://github.com/user-attachments/assets/57e99f0d-2dfb-4877-ae68-05d724b0c794)

![Pasted image 20240824021314](https://github.com/user-attachments/assets/b1e63e9b-7285-4ef0-85ed-b2c1e9088c44)

Save token somewhere since you can't recopy and need to make new one if you forgot (but it easy to do)

Step 2 : Make new google sheet and open script, this will automatically create new script page that link to google sheet 

![Pasted image 20240824021144](https://github.com/user-attachments/assets/727b34b3-bff3-45f2-940d-0a124189aa60)

Step 3 : copy code from this repo and place to google script, you need to change token to your own token

Step 4 : as you can see from code, this code just look up only A and B column which also simple made too.

now write on you own google sheet on what notify you want

![Pasted image 20240824021236](https://github.com/user-attachments/assets/8082df00-28e6-4a23-8d64-3f9c9d5a22cc)

Step 5 : when you finish write notify on script look at left side and open tricker, this will got you trigger setting, create now one will bring you to something like this, making it as you wish, for me I set it to notify at 10:00 to 11:00 

Remember to select first option as "setContent()" function 

![image](https://github.com/user-attachments/assets/588c1273-6e3d-4caf-b5ef-2bfc572a8889)

This should work.

Ref :

https://medium.com/@js_network/การทำ-line-notify-สำหรับแจ้งเตือนงานจาก-google-sheets-อย่างง่าย-334069ac3e5c

https://developers.google.com/apps-script/guides/sheets

https://spreadsheet.dev/learn-coding-google-sheets-apps-script

https://notify-bot.line.me/doc/en/
