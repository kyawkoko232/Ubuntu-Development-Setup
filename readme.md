**Install Python**
--

 1. Ctrl + Alt + T နှိပ်ပြီး  Terminal ခေါ်ပါ။

    sudo apt update

 2. အပေါ်ကcommand ပြီးရင်လိုအပ်တဲ့ဆော့ဝဲထည့်ပါမယ်။အရင်ကရိုက်ထည့်ထားဖူးရင်မလိုအပ်ပါ။
  

      sudo apt install software-properties-common

 3. Repository ထည့်ပါမယ်၊ Enter နှိပ်ခိုင်းရင် နှိပ်ပေးပြီး 
 yes or no တောင်းရင် -y ထည့်ပေးပါ။
   

     sudo add-apt-repository ppa:deadsnakes/ppa
    

 4. ကိုယ်လိုချင်တဲ့ Python Version ကို apt ကနေတစ်ဆင့်သွင်းနိုင်ပါပြီခုလောလောဆယ်တော့ Python 3.10 ထိထွက်ထားပါပြီ

    sudo apt install python3.10 -y


    python3 --version
    ဖြင့်ကိုယ့်Python Code ကိုစစ်ဆေးကြည့်နိုင်ပါပြီ။

