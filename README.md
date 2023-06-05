    Втора лабораториска вежба по Софтверско инженерство
    Ангела Величковска, 213097


![image](https://github.com/angelavelichkovska/SI_2023_lab2_213097/assets/129554338/1d7b3de2-68da-430d-a53b-26c7a63a6109)


 



3. Цикломатската комплексност е 11. Може да ја пресметаме на 3 начини и тоа:

   а)Да ги изброиме регионите

   б)(Бројот на ребра-бројот на јазли)+2  

   в)Предикатни јазли+1 
   
   
   
   
4. Every Branch, потребни се 5 случаја

    1.Со Корисник null
    
    2.no username valid&existing email, втор корисник, валиден пасворд со карактер што не се наоѓа на прва позиција
    
    3.email нема @,  има username, пасворд <8
    
    4.имаме совпаѓање на username, нема совпаѓање на email и пасвордот има празно место
  
    5.пасвордот нема specialcharacter, username/email не е важно
    


5.Според Multiple Condition критериумот за условот

if (user==null || user.getPassword()==null || user.getEmail()==null) постојат 4 случаја

   1.user=null T
   
   2.userот не е null, но пасвордот е null F T
   
   3.useрот и пасвордот не се null, но emailот е F F T
   
   4.ниту еден не е null F F F
   
