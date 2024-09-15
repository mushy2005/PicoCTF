## Table of Contents
- [Challenge Description](#challenge-description)
- [Approach](#approach)
- [Step-by-Step Solution](#step-by-step-solution)

---

## Challenge Description
![](https://github.com/mushy2005/picoCTF/blob/main/Challenges/The%20Beginner's%20Guide%20to%20the%20picoGym/Section%202%20(CyberChef)/Mod%2026/images/Mod%2026.png)
---

## Approach
This challenge could easily be solved by using a tool known as CyberChef, which helps with decoding cryptographic strings.

---

## Step-by-Step Solution
1. ROT13 is a letter substitution cipher that replaces a letter with the 13th letter after it. For example, using ROT13, the string ``apples`` would turn into ``nccyrf``.
2. Now that we know how it works, it's best to CyberChef to decode the given string, which is, ``cvpbPGS{arkg_gvzr_V'yy_gel_2_ebhaqf_bs_ebg13_GYpXOHqX}``
3. Once we paste that into the site and select the proper operation, we would get the flag: ``picoCTF{next_time_I'll_try_2_rounds_of_rot13_TLcKBUdK}``


