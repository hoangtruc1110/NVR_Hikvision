# NVR_Hikvision
Library NVR Hikvision

Hi everyone!
Now, i want to introduce you to my NVR library.

NVR_Hikvision.py : main code
From above library, you can
+ get track id of video channel to dev : get_cam_list()
+ search 'Record log' in NVR : record_video_log()
+ download video in NVR : download_video()
+ search log in MongoDB through isodate : search_log_iso_date()
+ get the lastest 20 event : get_new()
+ get data continuously : run()

Step 1:
- You must have
  + IP Address of NVR Hikvision
  + admin, password
  + port
  + VPN 
 Step 2:
 - Fill data in controller.py
 
 Step 3:
 - Run app.py
 - Search API to controller






