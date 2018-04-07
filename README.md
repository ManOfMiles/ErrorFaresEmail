# ErrorFaresEmail
Written in Python 3.6

An 'error fare' is a travel term for an airline or hotel fare that was incorrectly published substantially cheaper than normal. There are websites dedicated to posting these time sensitve 'deals' such as www.secretflying.com. Airlines will typically correct these errors within minutes/hours once detected. If you do successfully book an error fare, the departing country has laws that control whether that price must be honored by the airline/hotel. 

This tool will look for website page updates on Secret Flying and send an email if new page data exists. I have this script running as a cron job on my Linux machine. It runs every 5 minutes to detect a newly posted error fare, if detected, an email is sent immediately. 

You can receive push notifications from their FaceBook page but I don't find this as reliable or convenient as these deals are extremely time sensitive. 
