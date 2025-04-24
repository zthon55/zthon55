
try:
	import requests,os,names,random,time,mechanize,sys
	from user_agent import generate_user_agent
	from uuid import uuid4
except:
	os.system("pip install requsets")
	os.system("pip install names")
	os.system("pip install user_agent")
	os.system("pip install uid")
	os.system("pip install uuid")
	os.system("clear")
import requests,os,names,json,random
import requests,os,names,random,time
from user_agent import generate_user_agent
from uuid import uuid4
uid = uuid4()
import requests,random,mechanize,time
import requests,random,mechanize,datetime

now = datetime.datetime.today()

now = datetime.datetime.today()
mm = str(now.month)
dd = str(now.day)
yyyy = str(now.year)
hour = str(now.hour)
mi = str(now.minute)
ss = str(now.second)
t=(mm + "/" + dd + "/" + yyyy + " " + hour + ":" + mi + ":" + ss)


hours = (now.hour)
x = datetime.datetime.now()
g= datetime.datetime(2025, 5, 30, 1, 00 ,0)

if (x.strftime("%x"))>(g.strftime("%x")):
 print( \n\n )
 print("     "+ راجع المطور \n\n       @CC8CD\n\n    @M_A_M_ll @llxxxe/🚬 وقفت الاداه دخن لاضوج )
 print( \n\n )
 print(x)
 
 sys.exit(0)
 

if (x.strftime("%x"))==(g.strftime("%x")):
   print(  )
   if(x.strftime("%X"))>(g.strftime("%X")):
    print( \n\n )
    print("     "+ راجع المطور \n\n       @CC8CD\n\n    t.me/M_A_M_ll @llxxxe  خلص التفعيل روح اشترك وجه صطل😂 )
    print( \n\n )
    print(x)
    
    sys.exit(0)
   else:
    print(  )  
else:
    print(  )
print(  )


os.system( clear )
#------------------------------[الالوان]------------------------------
Z =  \033[1;31m  #احمر
X =  \033[1;33m  #اصفر
F =  \033[2;32m  #اخضر
C = "\033[1;97m" #ابيض
B =  \033[2;36m #سمائي
Y =  \033[1;34m  #ازرق فاتح.
C = "\033[1;97m" #ابيض
E =  \033[1;31m 
B =  \033[2;36m 
G =  \033[1;32m 
S =  \033[1;33m 
#------------------------------[saeim]------------------------------
try:
 from cfonts import render, say
except:
 os.system( pip install python-cfonts )
output = render( A , colors=[ red ,  yellow ], align= center )
print(output)
Op = "ALRAES"
print(F+ ▬ *60)
azooz=f" {F}Tool Hunting Instagram ALRAES ✔ ️ • "
print(azooz)
print(Z+ ▬ *60)
def cls():
	os.system("clear")

def pas():
	 J = input(f"{Y}اكتب باسورد الاداه   ")
	 if J ==Op:
	 	print(F+"\n 🟢 تم الباسورد صح ")
	 	time.sleep(1)
	 	cls()
	 else:
	 	print(Z+   الباسورد خطأ🔴  )
	 	pas()
pas()
import webbrowser
webbrowser.open( https://t.me/M_A_M_ll )
import requests
from bs4 import BeautifulSoup
class BigTakipClient:
    def __init__(self):
        self.username2 = input(Z+"Enter Username ~> ")
        self.password2 = input(B+"Enter Password ~> ")        
        self.headers = {
            "Accept": "application/json, text/javascript, */*; q=0.01",
            "Accept-Language": "ar-IQ,ar;q=0.9,en-US;q=0.8,en;q=0.7",
            "Content-Type": "application/x-www-form-urlencoded; charset=UTF-8",
            "Origin": "https://bigtakip.com",
            "Referer": "https://bigtakip.com/member",
            "Sec-Ch-Ua": "\"Not-A.Brand\";v=\"99\", \"Chromium\";v=\"124\"",
            "Sec-Ch-Ua-Mobile": "?1",
            "Sec-Ch-Ua-Platform": "\"Android\"",
            "Sec-Fetch-Dest": "empty",
            "Sec-Fetch-Mode": "cors",
            "Sec-Fetch-Site": "same-origin",
            "User-Agent": "Mozilla/5.0 (Linux; Android 10; K) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/124.0.0.0 Mobile Safari/537.36",
            "X-Requested-With": "XMLHttpRequest"
        }
        self.data = {
            "username": self.username2,
            "password": self.password2,
            "userid": "",
            "antiForgeryToken": "c58b820abfe0648118e30b8af2f5b04f"
        }
        self.session = requests.Session()
        self.cookies = {}

    def login(self):
        response = self.session.post("https://bigtakip.com/member",headers=self.headers, data=self.data)
        try:
            response_json = response.json()
            if response_json.get( status ) ==  success :
                print(X+ Done Login ☠ ️تم تسجيل الدخول )
            elif response_json.get( status ) ==  0 :
                print(S+ Bad Login ☠ ️فشل تسجيل الدخول )
                exit()
            else:
                print( Bad Login )
                exit()
            self.cookies = self.session.cookies.get_dict()
        except:
        	pass
        print(60*  ━ )

    def get_instagram_user_id(self, username):
        url2 = f https://www.instagram.com/api/v1/users/web_profile_info/?username={username} 
        headers2 = { x-ig-app-id :  936619743392459 }
        res = requests.get(url2, headers=headers2)
        try:
            res_json = res.json()
            user_id = res_json[ data ][ user ][ id ]
            return user_id
        except:          
            print( Bad username )


    def send_followers(self, username, user_id):
        if not user_id:
            print( Invalid user ID )
            return        
        url = f https://bigtakip.com/tools/send-follower/{user_id}?formType=send 
        headers = self.headers.copy()
        headers[ Referer ] = f https://bigtakip.com/tools/send-follower/{user_id} 
        headers[ Cookie ] =  ;  .join([f {key}={value}  for key, value in self.cookies.items()])
        data = {
            "formType": "send",
            "adet":  100 ,  
            "userID": user_id,
            "userName": username,
        }
        response = self.session.post(url, headers=headers, data=data)
        try:
            response_json = response.json()
            print(response_json)
        except:
        	pass
        print(60* ━ )
        if  status  in response_json and response_json[ status ] ==  success :
            print( Done send : تم الارسال )
        elif response_json.get( status ) ==  error :
            print(G+ Error~>☠ ️عذرأ لديك طلبات حاليا قيد التنفيد او نفذت نقاطك حاول فيما بعد او حاول ثاني يوم )
        else:
            print(G+ Error ~>☠ ️عذرأ لديك طلبات حاليا قيد التنفيد او نفذت نقاطك حاول فيما بعد او حاول ثاني يوم )

client = BigTakipClient()
client.login()
username = input("☠ ️User_insta ~> ")
user_id = client.get_instagram_user_id(username)
if user_id:
	client.send_followers(username, user_id)
