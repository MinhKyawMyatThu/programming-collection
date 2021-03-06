## Introduction to Object Oriented Principles - Part 1
OO Program ေတြေရးတဲ့အခါမွာ Object Orientation အေၾကာင္းကိုနားလည္ဖုိ.လိုပါတယ္။ Good quality ရိွတဲ့ OO program ေတြၿဖစ္ဖုိ.ဆုိရင္ Object Oriented Analysis နဲ. OO Design အေၾကာင္းကိုသိဖုိ.လိုပါတယ္။ OO ေပးထားတဲ့ language ကုိသံုးေနေပမဲ့ ရိွသမွ် အားလံုး method တစ္ခုထဲမွာ စုၿပံဳေရး အဲ့ကေန အကုန္ လွမ္းေခၚဆုိရင္ေတာ့ OO Language ကုိသံုးသာ သံုးေနတယ္ မွားေနတယ္လို.ေၿပာလို.ရပါတယ္။ အဲဒါမ်ိဳးကို writing C program in Java လို.ေခၚၾကပါတယ္။ OO ရတဲ့ Java လို language မ်ိဳးမွာ C style procedural programming ေရးေနသလို ေရးတာလို.ေၿပာခ်င္တာပါ။ Good OO program ေတြၿဖစ္ဖုိ.အတြက္ basic OO term ေတြ concept ေတြကုိ သင့္ေတာ္သလို အသံုးၿပဳတတ္ရပါလိမ့္မယ္။ ဥပမာ encapsulation ကဘာလို.အသံုး၀င္တာလဲ ဘယ္ေနရာမွာသံုးရမွာလဲ ဘယ္လိုဆုိရင္ encapsulation ကို ခ်ိဳးေဖာက္သလဲ။ ဆုိခ်င္တာက Java နဲ. runnable program တစ္ခု C# နဲ. runnable program တစ္ခု ထြက္လာတာနဲ. ဒါကုိ program ေရးႏုိင္ၿပီလို. သတ္မွတ္တာ ေတာ္ေတာ္လြဲတာပါ။ Program ေရးတတ္ၿပီဆုိတာထက္ bad program ေရးတတ္ၿပီလို.ပဲေၿပာရမွာပါ။ OO programming မွာဆုိရင္ေတာ့ နည္းနည္းေလး syntax ေလာက္ကုိ နားလည္သြားရင္ Design Pattern လိုေကာင္မ်ိဳးကုိ ေလ့လာေလ့ရိွပါတယ္။ ဒီေနရာမွာ ဘာၿပ ႆ နာရိွလဲဆုိေတာ့ Design Pattern ေတြကို သာသြားေလ့လာတယ္ OO အေၿခခံ သေဘာတရားေတြ ကုိ နားမလည္ပဲ သြားေလ့လာရင္ အူတူတူနဲ. လုိရင္းမေရာက္ပဲ သူမ်ားက သံုးဆုိလုိ.သာသံုးတယ္ ဘာေကာင္းမွန္းမသိ copy paste ပံုစံနဲ.ကို လြတ္မွာမဟုတ္ပါဘူး။

Design Pattern ေတြကို မေလ့လာခင္ဘာသိသင့္သလဲဆုိေတာ့ OO basic principle ေတြကို သိသင့္ပါတယ္။ Design Principle ဆုိတာဘာလဲဆုိေတာ့ လုိက္နာသင့္တဲ့ ေဆာင္ရန္ ေရွာင္ရန္ နည္းလမ္းေတြ concept ေတြလို.ပဲေၿပာရမွာပါပဲ။ ဒီအေၿခခံ principle ေတြ အေပၚမူတည္ၿပီးေတာ့ design pattern လို more mature design template ေတြ ထုတ္ထားတာပါ။ တကယ္တမ္း basic OO design principle ေတြကုိ နားလည္ရင္ design pattern ေတြ မသံုးလဲ ေကာင္းမြန္တဲ့ OO program တခု ေရးႏုိင္မွာပါ။

OO Principle ဆုိေပမဲ့ တခ်ိဳ. principle ေတြက OO မဟုတ္တဲ့ အၿခား procedural language ေတြမွာ apply လုပ္မယ္ဆုိရင္လဲ အသံုး၀င္တဲ့ principle ေတြလဲရိွပါတယ္။ ဥပမာ DRY (Don’t Repeat Yourself) ဒါဆုိ OO Principle မဟုတ္ပါဘူး။ သူ.သေဘာတရားက code တခုဟာ ေရးၿပီးသား tested လုပ္ၿပီးသားရိွရင္ အခ်ိိန္ကုန္ခံၿပီးေရး မေနနဲ. reuse လုပ္လုိ.ေၿပာတာပါ။ အဲ့လို Principle မ်ိဳးဆုိရင္ OO တင္မကဘူး က်န္တဲ့ programming paradigm ေတြမွာပါ သံုးလုိ.ရပါတယ္။

### Coupling and Cohesion

Principle ေတြအေၾကာင္းမရွင္းခင္မွာ သူတုိ.ရဲ. basic term ေတြကို သိေအာင္အရင္ေၿပာရပါလိမ့္မယ္။ OO Program သို.မဟုတ္ တၿခား paradigm နဲ.ေရးထားတဲ့ code တိုင္းမွာ coupling နဲ. cohesion ဆုိတာရိွပါတယ္။ Coupling program code တခု သို.မဟုတ္ class တခုဟာ သူ.ရဲ. responsibility လုပ္ဖုိ.အတြက္ တၿခား ဘယ္ class ဘယ္ code ေတြကို မီွခုိရသလဲ။ မရိွမၿဖစ္မီွခုိေနရသလဲဆုိတာကို ေၿပာတာပါ။ Class တခုရဲ. Responsibility ဆုိတာ အဲ့ဒီ class က လုပ္ေဆာင္ေပးႏုိင္တဲ့ public method (behaviour) ကိုေၿပာတာပါ။ ဆုိခ်င္တာက class တခုက သူ.အလုပ္ကုိ သူလုပ္ႏုိင္ဖုိ. အတြက္ တၿခား ဘယ္ class ေတြကို မွီခုိေနရသလဲ။ ဒါကို coupling လို.ေခၚပါတယ္။ အဲ့ေတာ့ အမီွအခုိ နည္းေလ ေကာင္းေလပါပဲ။ ဘာလုိ.လဲဆုိေတာ့ class တခုက သူ. responsibility အတြက္ တၿခား class 3 ခုေလာက္ကုိ မွီခုိရၿပီဆုိပါစုိ. ။ သူ couple ၿဖစ္ေနတဲ့ class 3 ခုတခုခု public interface ေတြသာ change လုပ္ရင္ သူလဲ လုိက္ေၿပာင္းရပါလိမ့္မယ္။ ဒီေတာ့ coupling ဟာ နည္းေလ ေကာင္းေလပါပဲ။ coupling ကုိ လံုး၀မရိွေအာင္ေတာ့ ေလ်ာ့ဖုိ.မလြယ္ပါဘူး။ ဘာလုိ.လဲဆုိေတာ့ software ဆုိတာ individual piece of code ေတြ တခုနဲ.တခု ဆက္ႏြယ္ၿပီး လုပ္ေနရလို.ပါ။ ဒါေပမဲ့တတ္ႏိုင္သမွ် နည္းေအာင္ လုပ္ရမွာပါ။ Coupling ကိုဆက္ခြဲရင္ Strong Coupling နဲ. loose coupling ဆိုၿပီးေတြ.ရပါလိမ့္မယ္။

### Strong Coupling vs loose Coupling

Strong Coupling ဆုိတာ class တခုသည္ တၿခား class တခုရဲ. public interface(public method) မဟုတ္ပဲ သူ.ရဲ. field ေတြ. variable ေတြကို တုိက္ရိုက္ယူသံုးမယ္ဆုိရင္ ဒါ Strong coupling ပဲ။ OO သေဘာတရားအရ encapsulation ကို ခ်ိဳးေဖာက္တာပါ။ သူဟာ သူမ်ား class ရဲ. private variable ဒါမွမဟုတ္ non public variable ေတြကို တုိက္ရုိုက္သံုးေနၿပီဆုိရင္ တကယ္လုိ. သူသံုးတဲ့ class က အဲ့ variable ကိုေၿပာင္းမယ္ဆုိရင္ မီွခုိေနတဲ့ class ပါလိုက္ေၿပာင္းရမွာပါ။ ဒါကုိ strong coupling လို.သံုးပါတယ္။

Loose coupling ဆိုတာက ေတာ့ class တခုဟာ တၿခား class တခုရဲ. public interface(public method)ေတြကို မီွခုိေနရတယ္ ယူသံုးေနရတယ္ဆုိရင္ ဒါ loose coupling ပါ။ loosely couple ၿဖစ္တဲ့ program ေတြဟာ ပိုၿပီးေတာ့ maintainable ၿဖစ္ပါတယ္။ Android မွာဆုိရင္ message passing လို facility သံုးၿပီး broadcast receiver လိုေကာင္ေတြရိွပါတယ္ ။ဥပမာ တခုခု broadcast လုပ္လုိက္ရင္ ဆုိင္ရာ app က အဲ့ ေကာင္ကုိ register လုပ္ထားရင္ android os ကေန ဆုိင္ရာ registered လုပ္ထားတဲ့ activity ကိုေခၚေပးမွာပါ။ ဒါက loose coupling ကိုအသံုးခ်ထားတဲ့ပံုစံတခုပါ။

class A 
{ B b; 
void method() 
{ b.privateData = “”; } 
}

class B 
{ String privateData; 
public void doSomething() 
{ //Do something on privateData privateData = “Do something as example”; } 
}

အေပၚက ၿပထားတဲ့ code မွာ class A သည္ class B ရဲ. privateData ဆုိတာကို method မွာေခၚသံုးပါတယ္ public interface ကေနသံုးတာမဟုတ္တဲ့အတြက္ ဒါကို strong coupling လို.ေခၚပါတယ္။ ဘယ္ေလာက္ couple ၿဖစ္သလဲဆုိရင္ေတာ့ 1 လုိ.ေၿပာရမွာပါ။ field တခုတည္းကိုသံုးလို.ပါ။. A သည္ B အေပၚမွာ couple ၿဖစ္ေနပါတယ္ ။ တကယ္လုိ.မ်ား အေၾကာင္းတခုခုေၾကာင့္ class B ရဲ. privateData သည္ type သုိ.မဟုတ္ variable name ေၿပာင္းသြားရင္ A မွာ လုိက္ေၿပာင္းရမွာပါ။ class တခုကို change လိုက္လုိ. ေနာက္ class တခုကုိပါလိုက္ေၿပာင္းေနရတယ္ဆုိရင္ ဒါ coupling မ်ားလို. maintainable code မဟုတ္လုိ.ပါ။ JavaScript လို dynamic language မ်ိဳးမွာဆုိ ဒီလို coupling ဟာ ဒုကၡေကာင္းေကာင္းေပးပါတယ္ ။ တေယာက္ေယက္က မ်ား B ရဲ. privateData ကို နာမည္ေၿပာင္းလုိက္မယ္ဆုိရင္ JS ဆုိရင္ A မွာယူသံုးထားတဲ့ privateData ကုိအသစ္ေနအနဲ. အစားထုိးေပးမွာပါ။ ဒါဆုိ bug ေတြၿဖစ္လာပါၿပီ။

### Cohesion

Cohesion ဆုိတာ class တခုဟာ သူ. public interface (public method )ေတြထဲမွာ သူ.ရဲ. data ကုိ ဘယ္ေလာက္ယူသံုးလဲ ။သူ.ဟာသူ က်စ္က်စ္လစ္လစ္ (သူမ်ား class ေတြကို ယူူမသံုးပဲနဲ.) သူ.အထဲမွာပဲ သူ.method ေတြကို ဘယ္ေလာက္ use လဲဆုိတာကို တုိင္းတာပါ။ ဆုိလိုခ်င္တာကေတာ့ သူမ်ား class ကိုမသံုးပဲနဲ. သူ.ရဲ. responsibility ေတြကို သူ.ကုိယ္ပုိင္ method ေတြသံုးၿပီး ေၿဖရွင္းထားသလဲ။ အၿပန္အလွန္အသံုးၿပဳသလဲပါ။ သူ. method တခုဟာ သူ.class ရဲ. တၿခား method ေတြ private data ေတြကုိေခၚေလ ၿပင္ပ ကေကာင္ကိုမသံုးေလ cohesive ၿဖစ္ေလပါပဲ။ဘာလုိ.လဲဆုိေတာ့ highly cohesive ၿဖစ္ၿပီဆုိရင္ သူမ်ားကို မမီွခုိေတာ့ဘူး အဲ့ေတာ့ maintainable,reusable ၿဖစ္ပါတယ္။ Cohesion က မ်ားေလေကာင္းေလပါ။ တုိင္းမယ္ဆုိရင္ Class တခုရဲ. method တခုၿခင္းစီဟာ သူ.ရဲ. method body ထဲမွာ သူ.ကုိယ္ပုိင္ method ေတြ data ေတြကို ေခၚသံုးေလ cohesive ၿဖစ္ေလပါပဲ။ Class တခုရဲ. method ဟာ သူ.ရဲ. ကုိယ္ပုိင္ method ,data ေတြကိုမသံုးဘူးဆုိရင္ဒါဟာ cohesion နည္းတာကိုၿပတာပါ။ အေပၚက class မွာ class B သည္ cohesive ၿဖစ္ပါတယ္ ဘာလို.လဲဆုိေတာ့ သူ. public interface (doSomethingလို.နာမည္ေပးထားတဲ့ method)မွာ သူ. privateData ကုိပဲသံုးၿပီး ေၿဖရွင္းလို.ပါ သူမ်ား class ကုိလံုး၀ မမွီခုိလုိ.ပါ။ ဒီလုိ class မ်ိဳးဆုိ highly cohesive class ပါပဲ

OO Principle ေတြထဲမွာ အထင္ရွားဆံုးကေတာ့ SOLID ပါ။ ေနာက္ KISS, GRASP,အၿပင္တၿခား ေသာ Principle ေတြလဲရိွပါေသးတယ္။
