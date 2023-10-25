# GreenPAK_BinClock
_A hopeless attempt to make a binary clock using Renesas' GreenPAK processor and GreenPAK Designer_

The main idea of this project is to create a binary clock using a GreenPAK processor. Its main goal is to help students comprehend the binary counting system with a real-life example.
For demonstration purposes, we will utilise the **GreenPAK SLG46620G**, and the "script" of the processor will be organised via **GreenPAK Designer** — a special software designed by "Renesas". The script is stored in the `NBitCounter_GreenPAK.gp4` file.

![GreenPAK - SLG46620G](https://github.com/EugeneBewz/GreenPAK_BinClock/assets/116636070/ea9df54c-2891-4cca-a009-cd6aa72247b7)

Current project status: **How the f*ck does it work?! Where to start?!**

---

# How it should work
Although I have no idea how it works inside the processor, the theoretical part is simple (as expected).
Every time we send a signal to the processor, after some actions (which I still have to find out), the LED-s are activated in some specific order, representing digits in binary format:

0 - 0
1 - 1
2 - 10
3 - 11
4 - 100
5 - 101, and so on

Below, you can see the expected outcome. (all LEDs were activated by hand; the "code" still doesn't work.)

![binary 5](https://github.com/EugeneBewz/GreenPAK_BinClock/assets/116636070/687975bd-875f-4106-a119-596c89f70621)
![binary 4](https://github.com/EugeneBewz/GreenPAK_BinClock/assets/116636070/008604f5-1e3f-4b8d-9740-d5406eedafc3)
![binary 3](https://github.com/EugeneBewz/GreenPAK_BinClock/assets/116636070/a2b67122-8e0c-4ec1-9ad5-8a2bc32da774)
![binary 2](https://github.com/EugeneBewz/GreenPAK_BinClock/assets/116636070/a3f93ae4-ce45-48d1-a43a-df501475b102)
![binary 1](https://github.com/EugeneBewz/GreenPAK_BinClock/assets/116636070/5ae5f0fb-0d06-40a7-939d-a36a61b8a21c)
