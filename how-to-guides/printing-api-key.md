---
description: >-
  How to setup your API key.  This is used to connect your online printing
  configuration to your PushPrinter application and receipt printer.
---

# Printing - API Key

1. Login to your O-In account at admin.o-in.co and go to Settings>System>Receipt Printing>Create Printer.

![](../.gitbook/assets/1-create-printer.png)

1. Name the printer, ideally use the same name as the settings in PushPrinter to avoid confusion. We also recommend turning on 'Auto Print Orders' and 'Auto Print Bookings'.

![](<../.gitbook/assets/untitled (2).png>)

1. Now select 'Printer Settings' and make sure that;

* 'Printing Method' - is set to ESCPOS
* 'ESCPOS Printing Type' - is set to 'ESCPOS Image'.

{% hint style="warning" %}
**NOTE** - In the case that your printer doesn't support image printer (not printing correctly or printing very slowly) Please change this to 'ESCPOS Text Only'.
{% endhint %}

![](<../.gitbook/assets/untitled-1 (2).png>)

1. Scroll to the bottom on the screen and press the 'Save' button.
2. Then highlight the API key > right click > copy to clipboard.

![](<../.gitbook/assets/untitled-2 (3).png>)

1. Paste the API key into the relevant API field in PushPrinter.
