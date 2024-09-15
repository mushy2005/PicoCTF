## Table of Contents
- [Challenge Description](#challenge-description)
- [Approach](#approach)
- [Step-by-Step Solution](#step-by-step-solution)

---

## Challenge Description
Can you invoke help flags for a tool or binary? [This program](https://mercury.picoctf.net/static/a00f554b16385d9970dae424f66ee1ab/warm) has extraordinarily helpful information...


## Approach
This is a fairly simple challenge as we only need to run a few simple commands to get the flag.



## Step-by-Step Solution
1. Firstly, we'll need to log in to our webshell. After logging in, we'll need to download the actual file into the webshell. We can do this by running `wget (link of the file)`, which will look something like this:
![WAF1]()
2. Now, we need to check exactly what kind of file it actually is, and we can do so by running `file warm`, which will give us:
![WAF2]()
3. As we can see, it looks like we might be able to execute it. But before that, we need to actually make it executable, which we can achieve by running `chmod +x warm`.
![WAF3]()
5. Notice how the color of the file name changes, indicating that we've successfully turned it into an actual executable. Finally, we can execute the file by running `./warm`
![WAF4]()
6. The `-h` is used if you want to learn the usage of a certain command. In this case, once we run `./warm -h`, we should be able to get the flag, which we do get: `picoCTF{b1scu1ts_4nd_gr4vy_18788aaa}`
![WAF5]()


