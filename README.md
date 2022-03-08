import requests, random
import webbrowser
webbrowser.open('https://t.me/ayqjn')
from colorama import *
import os
os.system('clear')
aa = 0
zz = 0
E = '\x1b[1;31m'
G = '\x1b[1;32m'
Z = '\x1b[1;31m'
X = '\x1b[1;33m'
F = "\033[1;92m"
B = '\x1b[2;32m'
Y= '\x1b[1;34m'
R = "\033[1;91m"
J = '\033[1;94m'
C = '\033[2;35m' 
i = "\033[1;90m"
A = '\033[2;34m'
rt = requests.session()
abas = 'qwertyuiopasdfghjklzxcvbnm1234567890'
cxsxs = ''
print(f"""  
{X}    o             
{F}  m
{B}  a
{Z} r
{X}1
 """)
print(f" {X}[⌯] 𝗧𝗲𝗹𝗲𝗚𝗿𝗮𝗠 : {Z}@{F}a{Y}y{B}{X}q{C}j{X}n ~{B} @ayqjn ")
print(f""" {X}- {Z}- {B}- {X}- {C}- {F}- {A}- {Y}- {Z}- {X}- {Z}- {B}- {X}- {Z}-""")
ID =input(f"{R}({X}-{R}) {X} Enter ID TLEGRAM {R}: "+X)
token =input(f"{R}({X}-{R}) {X} ENTER Token Bot {R} : "+X)
print(f""" {X}- {Z}- {B}- {X}- {C}- {F}- {A}- {Y}- {Z}- {X}- {Z}- {B}- {X}- {Z}-\n""")
start_msg = requests.post(f"https://api.telegram.org/bot{token}/sendMessage?chat_id={ID}&text=👳‍♂️ : ʜɪ ᴘʀᴏ @ayqjn ").json()
id_msg = start_msg['result']['message_id']
hea = {'accept':'text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.9', 
 'accept-encoding':'gzip, deflate, br', 
 'accept-language':'en-US,en;q=0.9,ar;q=0.8', 
 'cache-control':'max-age=0', 
 'sec-ch-ua':'" Not;A Brand";v="99", "Google Chrome";v="91", "Chromium";v="91"', 
 'sec-ch-ua-mobile':'?0', 
 'sec-fetch-dest':'document', 
 'sec-fetch-mode':'navigate', 
 'sec-fetch-site':'same-origin', 
 'sec-fetch-user':'?1', 
 'upgrade-insecure-requests':'1', 
 'user-agent':'Mozilla/5.0(Windows NT 10.0;Win64;x64) AppleWebKit/537.36(KHTML, like Gecko) Chrome/91.0.4472.124 Safari/537.36'}
while True:    
    ii77i = str(''.join((random.choice(abas) for x in range(0))))
    abAs = str(''.join((random.choice(abas) for x in range(4))))
    usernames = ii77i + cxsxs + abAs    
    tiko = f"https://www.tiktok.com/@{usernames}?"
    reqsnd = rt.get(tiko, headers=hea).status_code
    if reqsnd == 404:
        zz += 1
        os.system('cls' if os.name == 'nt' else 'clear')
        print("""
 \033[1;96m ------------------------
 \033[1;32m < COD BY omar - mmr >
 \033[1;96m ------------------------
\033[1;91m    o
\033[1;92m   m
\033[1;91m a
\033[1;92m r
\033[1;91m1
          \033[1;93m o 
         \033[1;92m m
         \033[1;91m   a
         \033[1;92m r
         \033[1;91m   1
\033[1;32m--------------------------------------------------
\033[1;95m
 Telegram   : https://t.me/qyqjn
 YOUTUBE    : OMAR - mmr 
 Insta      : 
\033[1;32m
--------------------------------------------------
""" )            
        print(f" {R}({X}-{R}) {J}{X}User   {R}: ({F}{usernames}{R}) ")
        print(R+"-----------------------------------")
        print(f""" ({F}-{R}) {F}Don  {R}  : {F}{zz} 
 {R}({J}-{R}) {J}Bad  {R}  : {J}{aa}
 {R}({i}-{R}) {i}Tele   {R}: {i}@ayqjn """)
        print(R+"-----------------------------------")
        i7bots = f"""
⌯ جار الفحص.
. - - - - - - - - - - - .
⌯ 𝗨𝘀𝗲𝗿𝗻𝗮𝗺𝗲 : {usernames} 
. - - - - - - - - - - - - .
⌯ 𝗜𝗺𝗽𝗼𝗿𝘁𝗮𝗻𝘁 : @ayqjn """              
        tlg = f"https://api.telegram.org/bot{token}/sendMessage?chat_id={ID}&text={i7bots}"
        i = requests.post(tlg) 
    else:
        requests.post(f"https://api.telegram.org/bot{token}/editmessagetext?chat_id={ID}&message_id={id_msg}&text=⌯ 𝗧𝗶𝗸 𝗧𝗼𝗸 𝗨𝘀𝗲𝗿 \n .- - - - - - - - - - - - .\n⌯ 𝗕𝗮𝗱 : {aa} \n⌯ 𝗛𝘂𝗻𝘁 : {zz}\n⌯ 𝗜𝗻 𝗨𝘀𝗲𝗿 : {usernames}\n. - - - - - - - - - - - - - .\n⌯ 𝗜𝗺𝗽𝗼𝗿𝘁𝗮𝗻𝘁 : @ayqjn ")          
        os.system('cls' if os.name == 'nt' else 'clear')
        print("""
 \033[1;96m ------------------------
 \033[1;32m < COD BY OMAR - MMR >
 \033[1;96m ------------------------
\033[1;91m    o
\033[1;92m   m
\033[1;91m  a
\033[1;92m r
\033[1;91m1
          \033[1;93m _____ ___   ___  _     ____    
         \033[1;92m |_   _/ _ \ / _ \| |   / ___|   
         \033[1;91m   | || | | | | | | |   \___ \   
         \033[1;92m   | || |_| | |_| | |___ ___) |  
         \033[1;91m   |_| \___/ \___/|_____|____/   
\033[1;32m--------------------------------------------------
\033[1;95m
 Telegram   : https://t.me/ayqjn
 YOUTUBE    : OMAR - MMR
 Insta      :
\033[1;32m
--------------------------------------------------
""" )                    
        print(f" {R}({X}-{R}) {J}{X}User   {R}: ({F}{usernames}{R}) ")
        print(R+"-----------------------------------")
        print(f""" ({F}-{R}) {F}Don  {R}  : {F}{zz} 
 {R}({J}-{R}) {J}Bad  {R}  : {J}{aa}
 {R}({i}-{R}) {i}Tele   {R}: {i}@ayqjn """)
        print(R+"-----------------------------------")
        aa += 1
