
ESP - Email service providers - build your email list and send out emails.

mailchimp - Used for image hosting .

IMGBB.com - Used for image hosting .

Design for all email clients.

-Using HTML Tables & Ghost Tables for Outlook.

-Desining for Mobile Users & 600px max-width.

-Safe fonts for Outlook & Google Fonts for others.

-Using Padding instead of Margin ..& test results with emailonacid.

-Accessibility best practices.

-Review email client market share.
Gives statistics on email opens. This is broken down by different categories like mobile phone,email client,browser and more.

--Notes on preheader text--
-preheader text appears after the title of the email in smaller text. And beneath the title of the email in moile clients.
-It is recommended that preheader text is roughly 85-100 characters in length.However,it can range from 30 - 200.
-preheader text is usually use for promotionals and or sales.
-To ensure preheader text does not appear in the body of our email use the following code.
-------------------------
  <div style="font-size:0px;color:#fafdfe;line-height:1px;
             mso-line-height-rule:exactly;display:none;max-width:0px;
             max-height:0px;opacity:0;overflow:hidden;mso-hide:all;">
             This is our preheader text! SALE SALE 25% OFF!
    </div>
----------------------------
--<table role="presentation"></table>--
The role attribute with presentation value- this attribute should be applied to all table tags used in email templates.It assist with sreen readers and accessibility by having the screen reader focus on the table content instead of the table tags.

<client market share found https://www.litmus.com/email-client-market-share/>

