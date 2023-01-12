# REI
python malware based on rei ayanami from NGE 

# What does it do?
Once downloaded onto a victim's computer (if it hasn't been intercepted already)
it encrypts it self using fernet and then tries *3* (and **ONLY** 3) times to connect back to the host (*i.e your pc, maybe a server idk and frankly idc*)
Then it takes a OS fingerprint (OS, OS build, IP, current user, etc) and sends it back to the host.
After, it sorts to the Downloads folder and downloads the latest 10 things from there and then moves to the Documents folder but downloads 20 items.
Once done, it dencrypts it self and then promptly deletes it self.

# Cool! What the roadmap?
Just this for now. Possibly plan on keylogging (maybe?) or a crypto-miner. Please make a pull request with ideas!

# OK! But why is this inspired by Rei Aayanami? what does REI stand for?
Because it kind of reminds me of her. 
It stands for **R**andom **E**ncrypted **I**nternal
![Alt Text](https://i.pinimg.com/originals/e2/9d/91/e29d916cf40ade4cf03af70266555939.gif)
