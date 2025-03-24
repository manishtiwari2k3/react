react ki koi bhi chize learn karne ke liye ya koi bhi chiz ko smjhne ke lie hum react ki documentation ko use kar sakte hai which is -> react.dev

react ki documentaion begnner friendly nahi hai
agar hume framework ka use nahi karna toh hum bundler ka use kar sakte hai
like -> varcel, vite
bundler ka actual kaam ye hota hai ki ye bhot sari js files ko leta hai aur 1 file mai execute kark de deta hai

react -> 1. react-dom  2. react-native

agar hume web pe focus karna hai toh react+react-dom
agar mobile app vgrh pe karna hai toh react+react-native


<!-- bhot saare tarike hai react ke projects ko bnane ke  -->
1 -> npx

npm = node package manager jo node ke saath aate hai aur uski help se bna sakte hai hum lekin kayi baar hum use install nahi karna chahte aur directly execute karvana chahte hai toh tab hum use kar sakte hai npx -> node package executer

npx create-react-app

npx -> executer
create-react-app -> utility hai jikse through hum apna project bna sakte hai

<!-- npx create-react-app 01basicReact -->


<!-- yeh jo  npx create-react-app hai ye actual mai bhot bulky utility hai aur bhot hi useful utility hai lekin size bada hone ki vajah se ye recommended nahi hai aur aajakal bhi bhot kam hi use hoti hai-->
vite and parcel are used nowadays

package.json ke andar jao sabse pehle aur usme sari dependencies vgrh check karo

<!-- cd 01basicreact -->

cd is used to move to a particular file location


<!-- ************************* -->

sabse pehle check karlo ki package.json file hai ya nahi directories mai

<!-- ls -->

then, project ko start karne ke liye hum start script cla skte hai

<!-- npm run start -->

<!-- npm run build -->

npm run build jo hota hai vo production folder hota hai aur jab hum apne code ko production mai daalte hai tab humara ye folder use hota hai


jaise hi npm run build use kiya build folder ban gya




<!-- yeh sab humne npx create-react-app se kiya hai-->
lekin ye acha tarika nahi hai


<!-- hum vite vgrh use karenge -->

<!-- npm create vite@latest -->

lekin jo npx vala tarika tha au ye jo vite vala tarika hai isme dekhe toh ta chlega ki
vite vale tarike mai 1 folder nahi hai which is modules


ab jaise isme humare pass node module nahi hai toh same tarike se jo humne vite ka project bnaya hai cd ki help se us folder par jaao then 
n

<!-- npm install -->

isme bhi time lagega but it is comparatively slower than npx 


<!-- npm run dev -->





kisi bhi cheez ko learn karne ka sabse sahi tarika hota hai ki edit karna us chiz ko

yha pe src folder pe jana hai aur delete karke edit karke dekhna hai