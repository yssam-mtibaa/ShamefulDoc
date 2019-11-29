# ShamefulDoc
This is a construct idea for 2007 Microsofts Office Word.
  ___ _                    __      _   ___          
 / __| |_  __ _ _ __  ___ / _|_  _| | |   \ ___  __ 
 \__ \ ' \/ _` | '  \/ -_)  _| || | | | |) / _ \/ _|
 |___/_||_\__,_|_|_|_\___|_|  \_,_|_| |___/\___/\__|

# Setup
```
git clone https://github.com/Xerox00/ShamefulDoc
```
```
cd ShamefulDoc
```
```
pip install -r requirements.txt
```

# Running ShamefulDoc
```
python ShamefulDoc.py
```
```
{PATH to word document to exploit}
```
```
{Malicous Shellcode}
```
Thats it, once you do that. You will have created your malicous word document. Once your target runs it using microsoft word 2007 your victem will be infected.

# An Explanation
Alright so how does this exploit work? This exploiit takes advantage of how Microsoft Word opens documents. Once your open the word document the word document will run the shellcode thinking "oh look here, just reading a normal document" which leads to shellcode execution. 

# TOS
Don't use this to break the law alright. This is a 100% for educational purposes and any damage you cause with this exploit falls on you. This is for learning purposes ONLY>
