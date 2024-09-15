## Table of Contents
- [Challenge Description](#challenge-description)
- [Approach](#approach)
- [Step-by-Step Solution](#step-by-step-solution)

---

## Challenge Description
![](https://github.com/mushy2005/picoCTF/blob/main/Challenges/The%20Beginner's%20Guide%20to%20the%20picoGym/Section%201%20(Sanity)/Super%20SSH/images/Updtd.png)
---

## Approach
This is an easy challenge so there's no need for a complicated approach. We just need to SSH into the mentioned hostname.

---

## Step-by-Step Solution
1. After logging into the Webshell, we are able to SSH.
2. The credentials will be different, but for me, the username is ``ctf-player`` and the hostname is ``titan.picoctf.net``. It also provides with the port number, which is ``64497``
3. We can simply by running the following command: ``ssh ctf-player@titan.picoctf.net -p 64497``.
4. Once that's done, it'll ask us, ``"Are you sure you want to continue connecting (yes/no/[fingerprint])?"`` After entering yes, it'll ask us for the password, which for me, is ``1ad5be0d``.
5. Once we log in, it'll give us the flag: ``picoCTF{s3cur3_c0nn3ct10n_8306c99d}``
   


