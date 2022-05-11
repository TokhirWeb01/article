# Article
#### What is it React Component Lifecycle ?
#### React Component Hayot tsikli nima ?

***
<code>React Component Lifecycle</code> ni har doim sodir bo'ladigon ishlar, voqeliklarga o'xshatishimiz mumkin. Misol uchun insonlarning hayotiga, 
yoki biror bir texnikaning ishlash tartibiga. <br/> Lekin boshqa Lifecycle lardan farqlari ham yoq emas! <code>React Component Lifecycle</code>  ni yaratamiz, yangilab boramiz va hohlagan joyimizda o'ldirib, tiriltirib ishlatishimiz mumkin.
<code>React Component Lifecycle</code> ning uch bosqichda ishlatishimiz mumkin, takidlaganimdek uni _yaratish_, _yangilab borish_ va  _o'ldirish_. <br /> <code>Lifecycle</code> yaratish uchun o'zining bir nechta meto'dlari mavjud ular: ***Mount***,  ***Update***,  ***Unmount***  <br/>
***Mount***: React Component yaratilganda "_Mount_ " holatida bo'ladi. <br/> <br/>
***Update***: React Component ichidagi ***Props*** yoki ***State*** ni o'zgartirmoqchi bo'lsak "_Update_ " ishga tushadi. <br/> <br/>
***Unmount***: Yoki aksincha Component ni o'ldirmoqchi bo'lsak "_Unmount_ " ishlaydi. <br/> <br/> 
<img src="https://miro.medium.com/max/446/1*e_kVCG_KA1XLT_14b9iEfg.png" height="250px" width="580x" /> <br /> <br />
Shu bilan birga har bir <code>React Component Lifecycle</code> Metodlarining o'zlarini ham alohida metodlari (_children methods_) bor. <br/>
***Mount***: <code>constructor function</code> <code>render</code> <code>componentDidMount</code> <br> 
_Mountning ishlash tartiblari_ - Birinchi "_constructor function_ " ishlasa undan so'ng "_render_ " va "_componentDidMount_ " <br>
Odatda <code>componentDidMount(){}</code> Ajax Request jo'natishda qo'l keladi! <br> 
<img src="">  <br> <br>
***Update***: <code>render</code> <code>componentDidUpdate</code> <br>
***Unmount***: <code>componentWillUnmount</code> <br>
