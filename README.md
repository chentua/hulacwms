# hulacwms

Scope of influence

V2.0.6

Repair scheme

Method is set to private and cannot be called externally

Environment construction method

(1) : download from the official website and unzip it to the WWW directory, phpstudy, but the PHP version should be more than 5.6

Vulnerability recurrence method

Payload
/admin.php/update/update_exe?upath=route

![image](https://user-images.githubusercontent.com/27337983/139574198-8a72c855-30ee-41e7-882e-8924753b40e4.png)

After execution, the C: \ perflogs directory will be downloaded to 1 directory, and the directory will be automatically copied to the root directory of the website

![image](https://user-images.githubusercontent.com/27337983/139574204-0114147e-8adb-44db-9448-cbcf3f07bee3.png)

After execution, you will arrive at the root directory of the website

![image](https://user-images.githubusercontent.com/27337983/139574226-cb221bc7-a738-4dce-a923-89f4d38c981a.png)

visit

![image](https://user-images.githubusercontent.com/27337983/139574234-71528d75-e8d8-469c-8e85-1dbbf381be4e.png)
