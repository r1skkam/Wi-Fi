# To find a Wi-Fi Password using the command prompt

**"All intellectual property, including but not limited to ideas, code, and other content contained in this repository, is the property of its respective owners and is acknowledged and credited accordingly."**

## Profiles on interface Wi-Fi:

```
netsh wlan show profiles
```

<img width="202" alt="image" src="https://github.com/user-attachments/assets/9e2fae4b-617c-4338-9bc9-54071830b51b" />

## To view the *Wi-Fi Password* for a specific profile

```
netsh wlan show profile name="Wi-Fi_profile-name" key=clear
```

![image](https://github.com/user-attachments/assets/2ceae826-72c8-4aee-8371-776921137d66)

## To remove the stored credentials/Wi-Fi Password on Windows using the command prompt

```
netsh wlan delete profile name="Wi-Fi_profile-name"
```

![image](https://github.com/user-attachments/assets/daee5497-a082-4071-a969-5a162278f410)
