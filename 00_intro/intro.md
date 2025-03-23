<!-- javascript ke baad hum backend ki traf jaa skte the lekin hum react ku seekh re hai -->

<!-- react 1 library hai javascript ki -->

Why we are learning react?

-> hype , job , trend, building UI
-> makes easy to manage and build complex frontend

<!-- jo humari react hoti hai vo end of the day html, css, js mai hi compile hoti hai-->
toh hume kab use karni chahiye react -> agar hume koi simple sa frontend bnana hai toh hum html css aur js ki help se bhi bna sakte hai lekin react hume tabhi use karni chahiye jab hum ksi  complex website ke frontend ko bna rahe ho

<!-- most projects dont even need react in initial stage -->





<!-- why react was created -->
originally facebook is having an issue -> phantom message problem (ghost message problem)

toh dikkat kya aati thi fb mai ki manlo chat ka count kaara hai 5 
lekin jab humne msg khol lia hai hai tab bhi count decrease nahi hota tha aur kaafi baar toh count 2 2 baar aajata tha

actual mai kya hota hai (state) jo hoti hai vo [js] manage karta hai aur (ui) jo hota hai [dom] manage karta hai

toh ye aapas mai communicate nahi kar paate the jiski vajah se ye problem aayi thi -> toh is issue ko resolve karne ke liye hi fb ke internal members ne js ki 1 nayi library hi bana di jise react naam diya gaya -> but initially it was hated and dicared by many people outside the organisation, but after many modifications ye ab bhot popular hai

khan academy and unsplash adopted the react first and is also appreciated by their team.

<!-- framework or library -->
react is a library not a framework

framework jo hti hai unme naming cnvention vgrh pe bhot dhyan diya jaata hai but not in case of libraray
library ami freedom jyada milti hai kaam karne ki jabi framwork mai predefined rules or naming convention ka use karna padta hai


<!-- topics to learn****************************************************************************************************** -->
<!-- state or ui manipulation,JSX -->
<!-- component reusability  --> button ko baar baar use karna , header footer ko baar baar use karna
<!-- reusing of component(props) --> components ke andar kya properties pass kar skte hai
like object ki properties (key:value) pairs are known as props
<!-- how to propogate change(hooks) --> jaise humne koi state ko change kara ya variable ko change kara toh vo ui mai reflect nahi hote toh hum unhe ui mai reflect karane ki litye hi hooks ka use karte hain 
kaafi hooks hote hai lekin hume sare padhne ki jrurat ahi hai 5-7 hooks padh lo fer kpi dikkat nahi hai


<!-- react jo bnata hai vo single page application bnata hai matlab jo page hota hai vo reload hi nahi hota -->




<!-- additional addon to react -->
to make react multi page appliaction
<!-- kaafi alag cheeze seekhni padti hai jo react ka part nahi hai -->
-> router (react dont have router)
naya package install karna padta hai react-router-dom

-> state management (kaafi sare variables, buttons declare kar dete hai hum toh konsa kab change hora hai kab update hora hai e manage nahi ho pata thats why state management is necessary) react dont have state management -> by default 
for state management the addons are -> Redux, Redux Toolkit, zustand, context api
state management initial state mai kaam ka nahi hai jab tak uska actual use nahi ota hume -> uska actual use tab hota hai jab kahi door se data aara hai aur use manage karne mai dikkat htoi hai


react previously functions ke upar based tha but now it is completely class based -> hooks are also based on class


-> class based component

->BAAS apps (backend as an service)
social media clone, e commerce
---------app write, fire base 






<!-- after react -->

we can switch to backend directly after react

->react is not a complete solution in most cases
          ->no seo, browser render of js, no routing        
->framework
        ->nextjs,gustby,remix


        nextjs ke andar hum backend,frontend dono likh sakte hai