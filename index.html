<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <title>Bardak's İşletim Sistemi v8.1</title>
  <link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><text y='.9em' font-size='90'>☕</text></svg>">
  <style>
    body{margin:0;padding:0;overflow:hidden}
    #root{width:100vw;height:100vh}
    .ld{width:100vw;height:100vh;display:flex;flex-direction:column;align-items:center;justify-content:center;background:#F5F0E8}
    .sp{width:40px;height:40px;border:3px solid rgba(27,79,142,.15);border-top-color:#1B4F8E;border-radius:50%;animation:spin .8s linear infinite;margin-bottom:16px}
    @keyframes spin{to{transform:rotate(360deg)}}
    .ld p{color:#1B4F8E;font-size:14px;font-weight:600;font-family:-apple-system,sans-serif}
  </style>
</head>
<body>
  <div id="root"><div class="ld"><div class="sp"></div><p>Bardak's yükleniyor...</p></div></div>
  <script crossorigin src="https://unpkg.com/react@18/umd/react.production.min.js"></script>
  <script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.production.min.js"></script>
  <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
  <script type="text/babel">
    const { useState, useEffect, useCallback, useMemo, useRef } = React;



/* ═══════════════════════════════════════════════════════════════
   B A R D A K S   v 8 . 1  —  U L T I M A T E   E X E C U T I V E
   Finansal Komuta Merkezi + Operasyon Sistemi
   ═══════════════════════════════════════════════════════════════ */

const A={pasta:"data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDAAgGBgcGBQgHBwcJCQgKDBQNDAsLDBkSEw8UHRofHh0aHBwgJC4nICIsIxwcKDcpLDAxNDQ0Hyc5PTgyPC4zNDL/2wBDAQkJCQwLDBgNDRgyIRwhMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjL/wAARCABgAGADASIAAhEBAxEB/8QAGQABAQEBAQEAAAAAAAAAAAAAAAQGBQMH/8QALBAAAgICAQMCBQMFAAAAAAAAAAECAwQRBRIhMUFRBhNhcaEiUrEyYoGR0f/EABgBAQEBAQEAAAAAAAAAAAAAAAADAQQC/8QAHBEBAAMAAwEBAAAAAAAAAAAAAAECEQMSITFR/9oADAMBAAIRAxEAPwD7yADnewAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACR58WpdFU3Jb0n26vsT89y64Ti55jpla4tJQX19/ZfUx3Fc7Rl8jXh341+E7NyVkbm60/WD6l+7a++i3Hw2tXtniV+SKzjcSzumyEZVdEZy0pTlrfbft/gmyOWnjZdMZ1Qlj2SVcpVyblCbfZ613j6bXhk8MV14ssrH5CE6ZOU5TnBPqb7PbXf0/B5Y8crkJY0l8iVMbI2TnCe32+j7rx7/7EVqdpaIAEVQAAAAADaS23pIEnKSshxOXKpyVkaZODitveu2l6mxGzjJnIZ/4t43Gz6qrc3l54WOk90QinK3unHS872vyY/WDRCNqqjV0zc55V6XzJNt+I/0wT9l+TvVcDyHLzhkSxpY9jT68nN25yb/bDf8AOjRcZ8Lcfx9kcicXlZce6uu79L/tj4j/AD9TujlrxV67rlmlr23HM4i6274eroux75w/VtT0p922m4yab8opjn51F1Lsp+TVDs9Y0nqOuyen9vB0MvCttypzdFVkG9xcoKTXZfVNeCWVM6oSbx7IJPxB2R/6iHaLTv6rkx46+Fl152LG+vw+z89mvuUEPFRksSTcpPqsk11Pb129fUuIWjJ8Vj4AAxoAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAD/2Q==",kafe:"data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDAAgGBgcGBQgHBwcJCQgKDBQNDAsLDBkSEw8UHRofHh0aHBwgJC4nICIsIxwcKDcpLDAxNDQ0Hyc5PTgyPC4zNDL/2wBDAQkJCQwLDBgNDRgyIRwhMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjL/wAARCABgAGADASIAAhEBAxEB/8QAGwABAAICAwAAAAAAAAAAAAAAAAQFAgMBBgf/xAApEAACAgIBAwMCBwAAAAAAAAAAAQIDBREEEhRRITEyFWETQXFzgZHR/8QAGAEBAQEBAQAAAAAAAAAAAAAAAAMBAgT/xAAaEQEBAQEBAQEAAAAAAAAAAAAAAgERIRIx/9oADAMBAAIRAxEAPwD3kAHndgAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAwttjTVKyclGMfVuTSS/lkf6lxNb7nj6/fj/pxlOJVzsdbRdGM63qTjNbjLTT01+a9CpswmElRJvCY7bhvfaQ8ede5Scnc9cVtd8XP1Di9Kl3FGn7P8aIhzuNZZGEL6ZSk9KMbYt/0ileHxll3EhZhse4tNwTpjJa1916exJrwuN42S4s+PjeHxrINzUqqIxfj3X6m7MM7S6ABJQAAAAAAABEyN7o4u+lNSkov11peSkhkOZOjVuOVUJVSddndRmpNLXxS9G0dh5PHjyaXXPWn5WzQ8fU4xi4wagtRXQik1OZ64qd3UCcrqFXcnC50Qc4w+Gko/Hfn7mrG5Xl5LJQ7jHriqEGt9xGzbbXhIuJcWM4dEuhxa010L1MaeFVRKLrhCPTv2ib9Tz89Z871KABJQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAH//Z",icerik:"data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDAAgGBgcGBQgHBwcJCQgKDBQNDAsLDBkSEw8UHRofHh0aHBwgJC4nICIsIxwcKDcpLDAxNDQ0Hyc5PTgyPC4zNDL/2wBDAQkJCQwLDBgNDRgyIRwhMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjL/wAARCABgAGADASIAAhEBAxEB/8QAGgABAAIDAQAAAAAAAAAAAAAAAAUGAgMEB//EACgQAAICAgEDAgYDAAAAAAAAAAABAgMEEQUSEyEUIiMxQVFhkQYVof/EABgBAQEBAQEAAAAAAAAAAAAAAAADAgQB/8QAGxEBAAMBAAMAAAAAAAAAAAAAAAECEQMSMUH/2gAMAwEAAhEDEQA/APeQAc7YAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAMbLIU1Ssskowgtyk/ojm/ssZZMaJd2M5T6E5VSUerW9b1rejVzK7vF5WNCaV1tMlWmm9/pN621+ymcfV6LkKrp0Xwpha7E+nqUF3H8NNe6djc4xSkt6W09FufOLRMyle81nF4s5LHry/Tatnakm1CtyS35S399LejorthdFyg9pNxf4aemilcnb6jl1k+lynGEutroUHVKMFFxm5J9DalFxlHbe9L7lk4Sc1iuOQu3fbbbd22pbinPettLeupbF+fjWJK32cSgAIqgAAAAAAAInk6sxchjZONRZdCNVlc41XRrkm3Fp+fDXtf+EC6L4vkr8mVtT71clR6iPizcejUtNKS8Sk0nvf483QrGdwOTyGRdXZj46Tusshl2S6+mM0k9V+Pd0pR234W2i/K8epRvX7Dgzq8u5WSc5d1Z8YXUK5OMp6j0baitw+UdNeG978eZDg+Jy8Xl5ZNtFlUHXKMnZODcn7VHxD5vUXuT8t6NFv8AHMymd/apxbrcjWsqHwXX8RT90fPUlJbT3vy18i2/U106ZXKvKU2dkABzLgAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA/9k=",kahve:"data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDAAgGBgcGBQgHBwcJCQgKDBQNDAsLDBkSEw8UHRofHh0aHBwgJC4nICIsIxwcKDcpLDAxNDQ0Hyc5PTgyPC4zNDL/2wBDAQkJCQwLDBgNDRgyIRwhMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjL/wAARCABgAGADASIAAhEBAxEB/8QAGgABAQACAwAAAAAAAAAAAAAAAAQFBgECB//EACsQAAMAAgEBBgUFAQAAAAAAAAABAgMRBBIFEyExQYEVIlFhwRREVIKE0f/EABgBAQEBAQEAAAAAAAAAAAAAAAADAgEE/8QAGREBAAMBAQAAAAAAAAAAAAAAAAECEQMx/9oADAMBAAIRAxEAPwD3kAHnbAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABNzuXPD4l5qqZe1Muk2tt6XkRfFcf8/G/8t/9LufinNwM8VKr5G0n9Utoii+Le1+gxty0qSuHpvyXi0UrmMW3XHxiJ/ccev6ZJ/DLeDzcfOw1kx63FuKSba37pejRHgycLlYu8wdn47jeup9C8fdlXZ0zPEVTjnH13VOVr1p/T7aFojPCszqsAE2wAAAAAAABpUnL8n4Gv8nBhjsrDWWc+WLrbxzaSh6fU09b9H+NGwGFtd3WbFePkKO8p+FNzSb2vBpr1KUYuh4XA4PM5FzLzVhjFNTk7/beq6lta8PPy37Gw8Ja4ODfn3ct+62YnJfVx80YcfIurl/JNKeptevSkZuJURMLylJHekzLlIdgASUAAAAAAAAAAA39wAAAAAAAAAAAAAAAAAAAAAAAf//Z",kruvasan:"data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDAAgGBgcGBQgHBwcJCQgKDBQNDAsLDBkSEw8UHRofHh0aHBwgJC4nICIsIxwcKDcpLDAxNDQ0Hyc5PTgyPC4zNDL/2wBDAQkJCQwLDBgNDRgyIRwhMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjL/wAARCABgAGADASIAAhEBAxEB/8QAGwABAAICAwAAAAAAAAAAAAAAAAQFAwYBAgf/xAApEAACAgEDAgUEAwAAAAAAAAAAAQIDEQQhMQUSBhRBUXETImGRgYLB/8QAGAEBAQEBAQAAAAAAAAAAAAAAAAIDAQT/xAAeEQEBAQABBAMAAAAAAAAAAAAAARECAxITMSFBUf/aAAwDAQACEQMRAD8A95AB51gAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABxKSjFyfCWWB0nfVUm7LYRxzmXBhXUdI5YjcpbpZim1vxv+Sp0cfMS7+9QtcnOMmlmEm2+1+65x8NbrB31MZ/Wm4KMra/tnVnEZqWOPb498NfnXsm5Wfdfa8hOM4qUWmn6nJVvqNGhojp4T81qo7SjGW7lndt+iy/8xkj6fxTobepeQlJfV7ux2Vvur7s47cvHrtnGMk+PlfmR3vn2vAAQsAAAAACN1BN6OaxJwbirO1ZfZld23xkkg7LlcrW512WJ+V011sZR7IyjHEWvR74w0kl/CecogeJ6+uWaLS26XRJaqEZfVuhPuk0lstvfn54NzBpOrl3EXp7M152tFqX0PWONko2S1SrtllpqCwopNe2ZS/syRTpl0aqjT0RcZ3UK2y6xRxTXx67N7+q2w3vg3W7RabUOTtpjJyWJPjK9njkwS6N06clKWkrbSwueP2aeeX2jxfiJ4a1q1XTIwVllqrX2WzrcO+LzhpPf8frguTBRo6NNOydNajKzHc8844M5hyst2NeMsmUABKgAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAH/9k=",logo:"data:image/jpeg;base64,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"};

// ━━━ DESIGN TOKENS ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
const D={ivory:"#F5F0E8",blue:"#1B4F8E",blueDk:"#133B6B",blueLt:"#2563A8",blueGh:"rgba(27,79,142,0.05)",blueMi:"rgba(27,79,142,0.08)",blueBd:"rgba(27,79,142,0.10)",w:"#FFF",t:"#1C1C1E",t2:"#636366",t3:"#AEAEB2",t4:"#D1D1D6",g:"#30B060",gS:"rgba(48,176,96,0.08)",r:"#E8453C",rS:"rgba(232,69,60,0.07)",o:"#F5A623",oS:"rgba(245,166,35,0.08)",s1:"0 1px 3px rgba(27,79,142,0.04)",s2:"0 4px 16px rgba(27,79,142,0.06)",s3:"0 12px 40px rgba(27,79,142,0.10)",font:"'DM Sans',sans-serif",disp:"'Playfair Display',serif"};

const CSS=`@import url('https://fonts.googleapis.com/css2?family=DM+Sans:wght@300;400;500;600;700&family=Playfair+Display:wght@600;700;800&display=swap');
*,*::before,*::after{margin:0;padding:0;box-sizing:border-box;-webkit-tap-highlight-color:transparent}
@keyframes eu{from{opacity:0;transform:translateY(14px)}to{opacity:1;transform:translateY(0)}}
@keyframes es{from{opacity:0;transform:scale(.93)}to{opacity:1;transform:scale(1)}}
@keyframes toast{from{opacity:0;transform:translateY(16px) scale(.96)}to{opacity:1;transform:translateY(0) scale(1)}}
@keyframes pulse{0%,100%{opacity:1}50%{opacity:.5}}
@keyframes glow{0%,100%{box-shadow:0 0 8px rgba(232,69,60,.2)}50%{box-shadow:0 0 20px rgba(232,69,60,.5)}}
::-webkit-scrollbar{width:5px}::-webkit-scrollbar-thumb{background:${D.blueBd};border-radius:10px}
.au{animation:eu .4s cubic-bezier(.22,1,.36,1) both}
.pf{transition:transform .12s cubic-bezier(.22,1,.36,1)}.pf:active{transform:scale(.965)!important}`;

// ━━━ DATA ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
const COMPANIES=[
  {id:"ltd",name:"Bardaks Limited Şti.",branches:[{id:"meydan",name:"Meydan",type:"garsonlu",tables:16}]},
  {id:"sahis",name:"Bardaks Şahıs İşletmesi",branches:[{id:"ktu",name:"KTÜ",type:"self"},{id:"samsun",name:"Samsun",type:"self"},{id:"imalathane",name:"İmalathane",type:"uretim"}]}
];
const USERS=[
  {pin:"0000",name:"Patron",role:"patron",branches:["meydan","ktu","samsun","imalathane"]},
  {pin:"1111",name:"Arif",role:"personel",branches:["ktu"]},
  {pin:"2222",name:"Emine",role:"personel",branches:["samsun"]},
  {pin:"3333",name:"Cihan",role:"personel",branches:["meydan"]},
  {pin:"4444",name:"Gülüzar",role:"personel",branches:["imalathane"]},
];
const DEBTS={
  krediler:[
    {id:1,bank:"Ziraat",amount:950000,monthly:9500,remaining:84,nextDate:"2026-04-05",rate:2.49},
    {id:2,bank:"İş Bankası",amount:1200000,monthly:12800,remaining:96,nextDate:"2026-04-10",rate:2.79},
  ],
  kartlar:[
    {id:1,name:"Yapı Kredi",limit:150000,used:87000,kesim:15,odeme:5,minPayment:4350},
    {id:2,name:"Garanti",limit:100000,used:62000,kesim:20,odeme:10,minPayment:3100},
    {id:3,name:"Akbank",limit:80000,used:41000,kesim:1,odeme:18,minPayment:2050},
  ],
  altin:[
    {id:1,kisi:"Mehmet Abi",gram:150,fiyat:3250,tarih:"2025-08-15"},
    {id:2,kisi:"Halil Usta",gram:80,fiyat:3100,tarih:"2025-11-20"},
  ],
  sahisBorclari:[
    {id:1,kisi:"Ahmet Bey",tutar:45000,aciklama:"Ekipman",tarih:"2025-06-10"},
    {id:2,kisi:"Tedarikçi X",tutar:28000,aciklama:"Hammadde",tarih:"2026-01-15"},
  ]
};
const TODAY=new Date();
const daysTil=(dateStr)=>{const d=new Date(dateStr);return Math.ceil((d-TODAY)/(1000*60*60*24));};
const fmt=(n)=>n.toLocaleString("tr-TR");
const fmtTL=(n)=>`₺${fmt(n)}`;

// ━━━ ICON HELPERS ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
const Ic={
  Home:({s=18,c="currentColor"})=><svg width={s} height={s} viewBox="0 0 24 24" fill="none" stroke={c} strokeWidth="1.8" strokeLinecap="round"><path d="M3 9l9-7 9 7v11a2 2 0 01-2 2H5a2 2 0 01-2-2z"/><path d="M9 22V12h6v10"/></svg>,
  Chart:({s=18,c="currentColor"})=><svg width={s} height={s} viewBox="0 0 24 24" fill="none" stroke={c} strokeWidth="1.8" strokeLinecap="round"><rect x="3" y="12" width="4" height="9" rx="1"/><rect x="10" y="7" width="4" height="14" rx="1"/><rect x="17" y="3" width="4" height="18" rx="1"/></svg>,
  Wallet:({s=18,c="currentColor"})=><svg width={s} height={s} viewBox="0 0 24 24" fill="none" stroke={c} strokeWidth="1.8" strokeLinecap="round"><rect x="2" y="5" width="20" height="16" rx="3"/><path d="M16 12a1 1 0 110 2 1 1 0 010-2z" fill={c}/><path d="M2 10h20"/></svg>,
  Transfer:({s=18,c="currentColor"})=><svg width={s} height={s} viewBox="0 0 24 24" fill="none" stroke={c} strokeWidth="1.8" strokeLinecap="round"><path d="M7 16V4m0 0L3 8m4-4l4 4M17 8v12m0 0l4-4m-4 4l-4-4"/></svg>,
  Users:({s=18,c="currentColor"})=><svg width={s} height={s} viewBox="0 0 24 24" fill="none" stroke={c} strokeWidth="1.8" strokeLinecap="round"><path d="M17 21v-2a4 4 0 00-4-4H5a4 4 0 00-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 00-3-3.87M16 3.13a4 4 0 010 7.75"/></svg>,
  Alert:({s=18,c=D.o})=><svg width={s} height={s} viewBox="0 0 24 24" fill="none" stroke={c} strokeWidth="2" strokeLinecap="round"><path d="M10.29 3.86L1.82 18a2 2 0 001.71 3h16.94a2 2 0 001.71-3L13.71 3.86a2 2 0 00-3.42 0z"/><line x1="12" y1="9" x2="12" y2="13"/><circle cx="12" cy="17" r=".5" fill={c}/></svg>,
  Lock:({s=18,c="currentColor"})=><svg width={s} height={s} viewBox="0 0 24 24" fill="none" stroke={c} strokeWidth="1.8" strokeLinecap="round"><rect x="5" y="11" width="14" height="10" rx="3"/><path d="M8 11V7a4 4 0 018 0v4"/></svg>,
  Coffee:({s=18,c=D.blue})=><svg width={s} height={s} viewBox="0 0 24 24" fill="none" stroke={c} strokeWidth="1.8" strokeLinecap="round"><path d="M4 8h12v8a4 4 0 01-4 4H8a4 4 0 01-4-4V8z"/><path d="M16 10c2 0 4 1 4 3s-2 3-4 3"/></svg>,
  Check:({s=18,c="currentColor"})=><svg width={s} height={s} viewBox="0 0 24 24" fill="none" stroke={c} strokeWidth="2.2" strokeLinecap="round"><path d="M5 12l5 5L20 7"/></svg>,
  X:({s=18,c="currentColor"})=><svg width={s} height={s} viewBox="0 0 24 24" fill="none" stroke={c} strokeWidth="1.8" strokeLinecap="round"><line x1="18" y1="6" x2="6" y2="18"/><line x1="6" y1="6" x2="18" y2="18"/></svg>,
};

function Img({src,size=36,round=false,style:ex}){
  return <div style={{width:size,height:size,borderRadius:round?size:10,overflow:"hidden",flexShrink:0,background:D.ivory,...ex}}><img src={src} alt="" style={{width:"100%",height:"100%",objectFit:"cover"}}/></div>;
}

// ━━━ LOGIN ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
function Login({onLogin}){
  const[pin,setPin]=useState("");const[err,setErr]=useState(false);const[step,setStep]=useState("pin");const[user,setUser]=useState(null);
  const digit=(d)=>{if(pin.length>=4)return;const n=pin+d;setPin(n);setErr(false);
    if(n.length===4){const u=USERS.find(u=>u.pin===n);if(u){if(u.branches.length===1){onLogin(u,u.branches[0]);}else{setUser(u);setStep("branch");}}else{setErr(true);setTimeout(()=>{setPin("");setErr(false);},600);}}};
  const allB=COMPANIES.flatMap(c=>c.branches.map(b=>({...b,co:c.name})));
  if(step==="branch"&&user){const uB=allB.filter(b=>user.branches.includes(b.id));
    return(<div style={{minHeight:"100vh",background:D.ivory,display:"flex",flexDirection:"column",alignItems:"center",justifyContent:"center"}}>
      <div className="au" style={{textAlign:"center",maxWidth:440,padding:32}}>
        <Img src={A.logo} size={72} round style={{margin:"0 auto 16px"}}/>
        <h2 style={{fontFamily:D.disp,fontSize:26,fontWeight:700,color:D.blue,marginBottom:4}}>Hoş geldin, {user.name}</h2>
        <p style={{color:D.t2,marginBottom:28,fontSize:14}}>Şube seç</p>
        <div style={{display:"flex",flexDirection:"column",gap:10}}>
          {uB.map(b=><button key={b.id} className="pf" onClick={()=>onLogin(user,b.id)} style={{background:D.w,borderRadius:18,padding:"16px 20px",border:`1.5px solid ${D.blueBd}`,cursor:"pointer",textAlign:"left",display:"flex",alignItems:"center",gap:14,boxShadow:D.s1}}>
            <Img src={b.type==="garsonlu"?A.kafe:b.type==="uretim"?A.kruvasan:A.kahve} size={40} round/>
            <div><div style={{fontWeight:600,fontSize:15}}>{b.name}</div><div style={{fontSize:12,color:D.t3}}>{b.co} • {b.type==="garsonlu"?"Garsonlu":b.type==="uretim"?"Üretim":"Self Servis"}</div></div>
          </button>)}
        </div>
        <button onClick={()=>{setStep("pin");setPin("");}} style={{background:"none",border:"none",color:D.t3,marginTop:20,cursor:"pointer",fontSize:13}}>← Geri</button>
      </div></div>);}
  return(<div style={{minHeight:"100vh",background:D.ivory,display:"flex",flexDirection:"column",alignItems:"center",justifyContent:"center"}}>
    <div className="au" style={{textAlign:"center",padding:32}}>
      <Img src={A.logo} size={88} round style={{margin:"0 auto 16px",boxShadow:D.s2}}/>
      <h1 style={{fontFamily:D.disp,fontSize:32,fontWeight:700,color:D.blue}}>Bardak's</h1>
      <p style={{color:D.t3,fontSize:13,marginBottom:32}}>İşletim Sistemi v8.1</p>
      <div style={{display:"flex",gap:14,justifyContent:"center",marginBottom:28}}>
        {[0,1,2,3].map(i=><div key={i} style={{width:14,height:14,borderRadius:7,background:i<pin.length?D.blue:"transparent",border:`2px solid ${err?D.r:D.blue}`,transition:"all .2s"}}/>)}
      </div>
      {err&&<p style={{color:D.r,fontSize:13,marginBottom:12}}>Geçersiz PIN</p>}
      <div style={{display:"grid",gridTemplateColumns:"repeat(3,72px)",gap:10,justifyContent:"center"}}>
        {[1,2,3,4,5,6,7,8,9,null,0,"⌫"].map((d,i)=><button key={i} className="pf" onClick={()=>d==="⌫"?setPin(pin.slice(0,-1)):d!==null&&digit(String(d))} style={{width:72,height:72,borderRadius:18,border:"none",background:d===null?"transparent":D.w,fontSize:d==="⌫"?16:24,fontWeight:600,color:D.t,cursor:d===null?"default":"pointer",boxShadow:d===null?"none":D.s1}}>{d!==null?d:""}</button>)}
      </div>
    </div></div>);
}

// ━━━ DEBT WARNING BADGE ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
function DebtAlert({debts}){
  const warnings=[];
  debts.krediler.forEach(k=>{const d=daysTil(k.nextDate);if(d<=5&&d>=0)warnings.push(`${k.bank} kredisi ${d} gün`);});
  debts.kartlar.forEach(k=>{const d=daysTil(`2026-04-${String(k.odeme).padStart(2,"0")}`);if(d<=5&&d>=0)warnings.push(`${k.name} kartı ${d} gün`);});
  if(!warnings.length)return null;
  return(<div style={{background:"rgba(232,69,60,0.06)",border:`1.5px solid rgba(232,69,60,0.2)`,borderRadius:16,padding:"14px 18px",marginBottom:16,animation:"glow 2s ease infinite"}}>
    <div style={{display:"flex",alignItems:"center",gap:8,marginBottom:6}}><Ic.Alert s={18}/><span style={{fontWeight:700,color:D.r,fontSize:14}}>Yaklaşan Ödemeler</span></div>
    {warnings.map((w,i)=><div key={i} style={{fontSize:13,color:D.r,paddingLeft:26}}>• {w}</div>)}
  </div>);
}

// ━━━ FINANCIAL DASHBOARD ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
function FinanceDash({debts}){
  const totalKredi=debts.krediler.reduce((s,k)=>s+k.monthly*k.remaining,0);
  const totalKart=debts.kartlar.reduce((s,k)=>s+k.used,0);
  const totalAltin=debts.altin.reduce((s,a)=>s+a.gram*a.fiyat,0);
  const totalSahis=debts.sahisBorclari.reduce((s,b)=>s+b.tutar,0);
  const grand=totalKredi+totalKart+totalAltin+totalSahis;
  const channels=[
    {label:"Krediler",total:totalKredi,color:"#1B4F8E",icon:"🏦",items:debts.krediler.map(k=>({t:`${k.bank}`,sub:`${k.remaining} taksit × ${fmtTL(k.monthly)}`,v:k.monthly*k.remaining,warn:daysTil(k.nextDate)<=5}))},
    {label:"Kredi Kartları",total:totalKart,color:"#8E1B4F",icon:"💳",items:debts.kartlar.map(k=>({t:k.name,sub:`Limit: ${fmtTL(k.limit)} | Kesim: ${k.kesim}. gün | Ödeme: ${k.odeme}. gün`,v:k.used,warn:daysTil(`2026-04-${String(k.odeme).padStart(2,"0")}`)<=5}))},
    {label:"Altın Borçları",total:totalAltin,color:"#B8860B",icon:"🥇",items:debts.altin.map(a=>({t:a.kisi,sub:`${a.gram}g × ₺${fmt(a.fiyat)}/g`,v:a.gram*a.fiyat}))},
    {label:"Şahıs Borçları",total:totalSahis,color:"#4F1B8E",icon:"🤝",items:debts.sahisBorclari.map(b=>({t:b.kisi,sub:b.aciklama,v:b.tutar}))},
  ];
  return(<div style={{padding:24}}>
    <DebtAlert debts={debts}/>
    {/* Grand Total */}
    <div className="au" style={{background:`linear-gradient(135deg,${D.blue},${D.blueDk})`,borderRadius:24,padding:"28px 28px 24px",marginBottom:20,color:D.w}}>
      <div style={{fontSize:13,opacity:.7,marginBottom:4}}>Toplam Borç Yükü</div>
      <div style={{fontSize:36,fontWeight:800,fontFamily:D.disp,letterSpacing:"-0.03em"}}>{fmtTL(grand)}</div>
      <div style={{display:"flex",gap:16,marginTop:16,flexWrap:"wrap"}}>
        {channels.map(c=><div key={c.label} style={{background:"rgba(255,255,255,0.12)",borderRadius:12,padding:"10px 16px",flex:"1 1 140px"}}>
          <div style={{fontSize:11,opacity:.7}}>{c.icon} {c.label}</div>
          <div style={{fontSize:18,fontWeight:700,marginTop:2}}>{fmtTL(c.total)}</div>
          <div style={{fontSize:11,opacity:.5}}>{((c.total/grand)*100).toFixed(1)}%</div>
        </div>)}
      </div>
    </div>
    {/* Detail Cards */}
    {channels.map((ch,ci)=><div key={ci} className="au" style={{background:D.w,borderRadius:20,boxShadow:D.s1,border:`1px solid ${D.blueBd}`,marginBottom:14,overflow:"hidden",animationDelay:`${ci*0.08}s`}}>
      <div style={{padding:"16px 20px",borderBottom:`1px solid ${D.blueBd}`,display:"flex",justifyContent:"space-between",alignItems:"center"}}>
        <div style={{display:"flex",alignItems:"center",gap:10}}>
          <span style={{fontSize:20}}>{ch.icon}</span>
          <div><div style={{fontWeight:700,fontSize:15}}>{ch.label}</div><div style={{fontSize:12,color:D.t3}}>{ch.items.length} kalem</div></div>
        </div>
        <div style={{fontSize:18,fontWeight:800,color:ch.color}}>{fmtTL(ch.total)}</div>
      </div>
      {ch.items.map((it,i)=><div key={i} style={{padding:"12px 20px",borderBottom:i<ch.items.length-1?`1px solid ${D.blueGh}`:"none",display:"flex",justifyContent:"space-between",alignItems:"center",background:it.warn?"rgba(232,69,60,0.03)":"transparent"}}>
        <div><div style={{fontWeight:600,fontSize:14,display:"flex",alignItems:"center",gap:6}}>{it.t}{it.warn&&<span style={{width:8,height:8,borderRadius:4,background:D.r,animation:"pulse 1.5s ease infinite"}}/>}</div><div style={{fontSize:12,color:D.t3}}>{it.sub}</div></div>
        <div style={{fontWeight:700,fontSize:15,color:D.t,fontVariantNumeric:"tabular-nums"}}>{fmtTL(it.v)}</div>
      </div>)}
    </div>)}
  </div>);
}

// ━━━ QUICK POS (Satış) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
const CATS=[{id:"kahve",name:"Kahveler",a:"kahve"},{id:"pasta",name:"Pastalar",a:"pasta"},{id:"kruv",name:"Kruvasanlar",a:"kruvasan"},{id:"icecek",name:"İçecekler",a:"icerik"}];
const PRODS=[{id:"p1",n:"Filtre Kahve",p:60,c:"kahve"},{id:"p2",n:"Latte",p:80,c:"kahve"},{id:"p3",n:"Cappuccino",p:80,c:"kahve"},{id:"p4",n:"Espresso",p:55,c:"kahve"},{id:"p5",n:"Türk Kahvesi",p:50,c:"kahve"},{id:"p6",n:"San Sebastian",p:120,c:"pasta"},{id:"p7",n:"Tiramisu",p:110,c:"pasta"},{id:"p8",n:"Cheesecake",p:100,c:"pasta"},{id:"p9",n:"Klasik Kruvasan",p:70,c:"kruv"},{id:"p10",n:"Çikolatalı",p:85,c:"kruv"},{id:"p11",n:"Limonata",p:65,c:"icecek"},{id:"p12",n:"Ice Tea",p:55,c:"icecek"},{id:"p13",n:"Su",p:15,c:"icecek"}];

function QuickPOS({branchType}){
  const[cat,setCat]=useState("kahve");const[cart,setCart]=useState([]);
  const prods=PRODS.filter(p=>p.c===cat);const total=cart.reduce((s,c)=>s+c.p*c.q,0);
  const add=(p)=>setCart(prev=>{const e=prev.find(c=>c.id===p.id);if(e)return prev.map(c=>c.id===p.id?{...c,q:c.q+1}:c);return[...prev,{...p,q:1}];});
  const upd=(id,d)=>setCart(prev=>prev.map(c=>c.id===id?{...c,q:Math.max(0,c.q+d)}:c).filter(c=>c.q>0));
  return(<div style={{display:"flex",height:"100%"}}>
    <div style={{flex:1,display:"flex",flexDirection:"column"}}>
      <div style={{display:"flex",gap:8,padding:"14px 20px",overflowX:"auto"}}>
        {CATS.map(c=>{const ac=cat===c.id;return<button key={c.id} onClick={()=>setCat(c.id)} className="pf" style={{display:"flex",alignItems:"center",gap:8,padding:"8px 16px 8px 8px",borderRadius:50,border:"none",cursor:"pointer",background:ac?D.blue:D.w,boxShadow:ac?D.s2:D.s1}}>
          <Img src={A[c.a]} size={30} round style={{border:ac?"2px solid rgba(255,255,255,.4)":`2px solid ${D.blueBd}`}}/>
          <span style={{fontSize:13,fontWeight:600,color:ac?D.w:D.t,whiteSpace:"nowrap"}}>{c.name}</span>
        </button>;})}
      </div>
      <div style={{flex:1,overflow:"auto",padding:"8px 20px 20px"}}>
        <div style={{display:"grid",gridTemplateColumns:"repeat(auto-fill,minmax(130px,1fr))",gap:10}}>
          {prods.map((p,i)=>{const ic=cart.find(c=>c.id===p.id);return<button key={p.id} onClick={()=>add(p)} className="pf" style={{background:D.w,borderRadius:16,border:ic?`2px solid ${D.blue}`:`1px solid ${D.blueBd}`,padding:"16px 12px 12px",cursor:"pointer",textAlign:"left",position:"relative",boxShadow:ic?D.s2:D.s1}}>
            {ic&&<div style={{position:"absolute",top:8,right:8,width:24,height:24,borderRadius:12,background:D.blue,color:D.w,fontSize:12,fontWeight:700,display:"flex",alignItems:"center",justifyContent:"center"}}>{ic.q}</div>}
            <div style={{fontSize:13,fontWeight:600,lineHeight:1.3,paddingRight:ic?28:0}}>{p.n}</div>
            <div style={{fontSize:16,fontWeight:800,color:D.blue,marginTop:4}}>₺{p.p}</div>
          </button>;})}
        </div>
      </div>
    </div>
    <div style={{width:320,background:D.w,borderLeft:`1px solid ${D.blueBd}`,display:"flex",flexDirection:"column"}}>
      <div style={{padding:"16px 20px",borderBottom:`1px solid ${D.blueBd}`}}>
        <h3 style={{fontSize:17,fontWeight:700}}>Adisyon</h3>
        <span style={{fontSize:12,color:D.t3}}>{cart.length?`${cart.reduce((s,c)=>s+c.q,0)} kalem`:"Boş"}</span>
      </div>
      <div style={{flex:1,overflow:"auto",padding:"8px 0"}}>
        {!cart.length?<div style={{textAlign:"center",padding:40,opacity:.3}}><Ic.Coffee s={40}/><p style={{marginTop:10,fontSize:13}}>Ürün ekleyin</p></div>
        :cart.map(it=><div key={it.id} style={{display:"flex",alignItems:"center",gap:10,padding:"10px 20px",borderBottom:`1px solid ${D.blueGh}`}}>
          <div style={{flex:1}}><div style={{fontSize:13,fontWeight:600}}>{it.n}</div><div style={{fontSize:12,color:D.t3}}>₺{it.p}×{it.q}</div></div>
          <div style={{display:"flex",alignItems:"center",gap:2,background:D.ivory,borderRadius:50,padding:3}}>
            <button onClick={()=>upd(it.id,-1)} className="pf" style={{width:28,height:28,borderRadius:14,border:"none",background:D.w,cursor:"pointer",display:"flex",alignItems:"center",justifyContent:"center",boxShadow:D.s1}}><Ic.X s={12} c={it.q===1?D.r:D.t3}/></button>
            <span style={{width:26,textAlign:"center",fontSize:14,fontWeight:700}}>{it.q}</span>
            <button onClick={()=>upd(it.id,1)} className="pf" style={{width:28,height:28,borderRadius:14,border:"none",background:D.w,cursor:"pointer",display:"flex",alignItems:"center",justifyContent:"center",boxShadow:D.s1}}>+</button>
          </div>
          <div style={{fontWeight:700,fontSize:14,color:D.blue,minWidth:48,textAlign:"right"}}>₺{it.p*it.q}</div>
        </div>)}
      </div>
      {cart.length>0&&<div style={{padding:"16px 20px",borderTop:`1px solid ${D.blueBd}`,background:`linear-gradient(${D.w},${D.ivory})`}}>
        <div style={{display:"flex",justifyContent:"space-between",marginBottom:14}}>
          <span style={{fontWeight:600,color:D.t2}}>Toplam</span>
          <span style={{fontSize:24,fontWeight:800,color:D.blue,fontFamily:D.disp}}>₺{fmt(total)}</span>
        </div>
        <div style={{display:"flex",gap:8}}>
          <button className="pf" style={{flex:1,padding:14,borderRadius:16,border:"none",background:D.gS,cursor:"pointer",fontWeight:700,color:D.g,fontSize:14}}>Nakit</button>
          <button className="pf" style={{flex:1,padding:14,borderRadius:16,border:"none",background:D.blueMi,cursor:"pointer",fontWeight:700,color:D.blue,fontSize:14}}>Kart</button>
        </div>
      </div>}
    </div>
  </div>);
}

// ━━━ TRANSFER MODULE ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
function TransferMod(){
  const allB=COMPANIES.flatMap(c=>c.branches);
  const[from,setFrom]=useState("imalathane");const[to,setTo]=useState("meydan");
  return(<div style={{padding:24,maxWidth:560,margin:"0 auto"}}>
    <div style={{background:D.w,borderRadius:20,boxShadow:D.s2,padding:24}}>
      <h3 style={{fontSize:18,fontWeight:700,marginBottom:20,display:"flex",alignItems:"center",gap:10}}><Ic.Transfer s={22} c={D.blue}/> Şubeler Arası Sevk</h3>
      <div style={{display:"grid",gridTemplateColumns:"1fr auto 1fr",gap:12,alignItems:"center",marginBottom:20}}>
        <div><label style={{fontSize:12,fontWeight:600,color:D.t3,display:"block",marginBottom:6}}>Kaynak</label>
          <select value={from} onChange={e=>setFrom(e.target.value)} style={{width:"100%",padding:"12px 14px",borderRadius:12,border:`2px solid ${D.blueBd}`,fontSize:14,fontWeight:600,outline:"none"}}>{allB.map(b=><option key={b.id} value={b.id}>{b.name}</option>)}</select></div>
        <div style={{width:40,height:40,borderRadius:20,background:D.blueGh,display:"flex",alignItems:"center",justifyContent:"center",marginTop:18}}><Ic.Transfer s={20} c={D.blue}/></div>
        <div><label style={{fontSize:12,fontWeight:600,color:D.t3,display:"block",marginBottom:6}}>Hedef</label>
          <select value={to} onChange={e=>setTo(e.target.value)} style={{width:"100%",padding:"12px 14px",borderRadius:12,border:`2px solid ${D.blueBd}`,fontSize:14,fontWeight:600,outline:"none"}}>{allB.filter(b=>b.id!==from).map(b=><option key={b.id} value={b.id}>{b.name}</option>)}</select></div>
      </div>
      <p style={{fontSize:13,color:D.t3,textAlign:"center"}}>Ürün seçimi ve onay modülü Supabase bağlantısıyla aktif olacak</p>
      <button className="pf" style={{width:"100%",padding:16,borderRadius:16,border:"none",background:D.blue,color:D.w,fontSize:15,fontWeight:700,marginTop:16,cursor:"pointer"}}>Sevk İşlemini Başlat</button>
    </div>
  </div>);
}

// ━━━ BANK RECONCILIATION ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
function BankRecon(){
  const mockData=[
    {date:"24.03.2026",pos:14455,system:14455,diff:0,status:"ok"},
    {date:"23.03.2026",pos:12890,system:12690,diff:200,status:"warn"},
    {date:"22.03.2026",pos:16200,system:16200,diff:0,status:"ok"},
  ];
  return(<div style={{padding:24}}>
    <div style={{background:D.w,borderRadius:20,boxShadow:D.s2,overflow:"hidden"}}>
      <div style={{padding:"18px 22px",borderBottom:`1px solid ${D.blueBd}`}}>
        <h3 style={{fontSize:18,fontWeight:700}}>Banka POS Mutabakatı</h3>
        <p style={{fontSize:12,color:D.t3}}>Kartlı satış vs Banka POS verisi karşılaştırması</p>
      </div>
      {mockData.map((d,i)=><div key={i} style={{display:"flex",alignItems:"center",padding:"14px 22px",borderBottom:`1px solid ${D.blueGh}`,background:d.status==="warn"?"rgba(245,166,35,0.04)":"transparent"}}>
        <div style={{flex:1}}><div style={{fontWeight:600,fontSize:14}}>{d.date}</div></div>
        <div style={{width:120,textAlign:"right"}}><div style={{fontSize:12,color:D.t3}}>POS</div><div style={{fontWeight:700}}>{fmtTL(d.pos)}</div></div>
        <div style={{width:120,textAlign:"right"}}><div style={{fontSize:12,color:D.t3}}>Sistem</div><div style={{fontWeight:700}}>{fmtTL(d.system)}</div></div>
        <div style={{width:100,textAlign:"right"}}><div style={{fontSize:12,color:D.t3}}>Fark</div><div style={{fontWeight:700,color:d.diff?D.r:D.g}}>{d.diff?fmtTL(d.diff):"✓ Eşit"}</div></div>
      </div>)}
    </div>
  </div>);
}

// ━━━ MAIN APP ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
function BardaksOS(){
  const[user,setUser]=useState(null);const[branch,setBranch]=useState(null);const[view,setView]=useState("home");
  const branchInfo=useMemo(()=>{if(!branch)return null;for(const c of COMPANIES){const b=c.branches.find(br=>br.id===branch);if(b)return{...b,co:c.name,coId:c.id};}return null;},[branch]);
  const handleLogin=(u,b)=>{setUser(u);setBranch(b);const br=COMPANIES.flatMap(c=>c.branches).find(x=>x.id===b);
    if(br?.type==="garsonlu")setView("pos");else if(br?.type==="uretim")setView("transfer");else setView("pos");};
  if(!user)return<><style>{CSS}</style><Login onLogin={handleLogin}/></>;

  const isPatron=user.role==="patron";
  const navItems=[
    {id:"home",label:"Genel",icon:Ic.Home,show:isPatron},
    {id:"finance",label:"Finans",icon:Ic.Wallet,show:isPatron},
    {id:"pos",label:"Satış",icon:Ic.Coffee,show:true},
    {id:"transfer",label:"Sevk",icon:Ic.Transfer,show:isPatron||branchInfo?.type==="uretim"},
    {id:"recon",label:"Mutabakat",icon:Ic.Chart,show:isPatron},
  ].filter(n=>n.show);

  return(<>
    <style>{CSS}</style>
    <div style={{display:"flex",height:"100vh",fontFamily:D.font,background:D.ivory,color:D.t,overflow:"hidden"}}>
      {/* Sidebar */}
      <aside style={{width:72,height:"100vh",background:D.w,borderRight:`1px solid ${D.blueBd}`,display:"flex",flexDirection:"column",alignItems:"center",paddingTop:16,flexShrink:0}}>
        <Img src={A.logo} size={42} round style={{marginBottom:20,cursor:"pointer"}} />
        <nav style={{flex:1,display:"flex",flexDirection:"column",gap:4,width:"100%",padding:"0 8px"}}>
          {navItems.map(n=>{const ac=view===n.id;const IC=n.icon;return<button key={n.id} onClick={()=>setView(n.id)} className="pf" style={{width:"100%",height:52,borderRadius:14,border:"none",cursor:"pointer",background:ac?D.blueGh:"transparent",display:"flex",flexDirection:"column",alignItems:"center",justifyContent:"center",gap:2,color:ac?D.blue:D.t3}}>
            <IC s={20} c={ac?D.blue:D.t3}/><span style={{fontSize:9,fontWeight:ac?700:500}}>{n.label}</span>
          </button>;})}
        </nav>
        <button onClick={()=>{setUser(null);setBranch(null);}} className="pf" style={{width:56,height:52,borderRadius:14,border:"none",cursor:"pointer",background:"transparent",display:"flex",flexDirection:"column",alignItems:"center",justifyContent:"center",gap:2,color:D.t3,marginBottom:16}}>
          <Ic.Lock s={18} c={D.t3}/><span style={{fontSize:9}}>Çıkış</span>
        </button>
      </aside>

      {/* Main */}
      <main style={{flex:1,display:"flex",flexDirection:"column",overflow:"hidden"}}>
        <header style={{display:"flex",alignItems:"center",justifyContent:"space-between",padding:"12px 24px",background:D.w,borderBottom:`1px solid ${D.blueBd}`}}>
          <div><h2 style={{fontSize:17,fontWeight:700}}>
            {view==="home"&&"Komuta Merkezi"}{view==="finance"&&"Finansal Zırh"}{view==="pos"&&"Satış Ekranı"}{view==="transfer"&&"Sevk Yönetimi"}{view==="recon"&&"Banka Mutabakatı"}
          </h2><p style={{fontSize:12,color:D.t3}}>{branchInfo?.co} — {branchInfo?.name}</p></div>
          <div style={{display:"flex",alignItems:"center",gap:10}}>
            <div style={{padding:"5px 12px",borderRadius:50,background:D.gS,fontSize:11,fontWeight:600,color:D.g}}>● Çevrimiçi</div>
            <div style={{padding:"5px 12px",borderRadius:50,background:D.blueMi,fontSize:11,fontWeight:600,color:D.blue}}>{user.name}</div>
          </div>
        </header>
        <div style={{flex:1,overflow:"auto"}}>
          {view==="home"&&isPatron&&<div style={{padding:24}}>
            <DebtAlert debts={DEBTS}/>
            {/* KasaCEPTE-style summary cards */}
            <div style={{display:"grid",gridTemplateColumns:"repeat(auto-fit,minmax(200px,1fr))",gap:14,marginBottom:20}}>
              {[{label:"Nakit",val:3030,pct:"17.3%",color:D.g,bg:D.gS},{label:"Kredi Kartı",val:14455,pct:"82.7%",color:D.blue,bg:D.blueMi},{label:"Kasa Durumu",val:17485,color:D.blueDk,bg:"rgba(19,59,107,0.08)"},{label:"Açık Masalar",val:"6,340 / 23,825",color:"#6B3FA0",bg:"rgba(107,63,160,0.08)"}].map((c,i)=>
                <div key={i} className="au" style={{background:D.w,borderRadius:18,padding:"18px 20px",boxShadow:D.s1,borderLeft:`4px solid ${c.color}`,animationDelay:`${i*0.08}s`}}>
                  <div style={{fontSize:12,color:D.t3,fontWeight:600,marginBottom:6}}>{c.label}</div>
                  <div style={{fontSize:22,fontWeight:800,color:c.color}}>{typeof c.val==="number"?fmtTL(c.val):`₺${c.val}`}</div>
                  {c.pct&&<div style={{fontSize:11,color:D.t3,marginTop:2}}>{c.pct}</div>}
                </div>
              )}
            </div>
            <div style={{display:"grid",gridTemplateColumns:"1fr 1fr",gap:14}}>
              <div style={{background:D.w,borderRadius:18,padding:20,boxShadow:D.s1}}>
                <h4 style={{fontSize:14,fontWeight:700,marginBottom:12}}>Şirket Yapısı</h4>
                {COMPANIES.map(c=><div key={c.id} style={{marginBottom:12}}>
                  <div style={{fontSize:13,fontWeight:700,color:D.blue,marginBottom:4}}>{c.name}</div>
                  {c.branches.map(b=><div key={b.id} style={{fontSize:12,color:D.t2,paddingLeft:12}}>• {b.name} ({b.type})</div>)}
                </div>)}
              </div>
              <div style={{background:D.w,borderRadius:18,padding:20,boxShadow:D.s1}}>
                <h4 style={{fontSize:14,fontWeight:700,marginBottom:12}}>Personel</h4>
                {USERS.filter(u=>u.role==="personel").map(u=><div key={u.pin} style={{display:"flex",justifyContent:"space-between",padding:"6px 0",borderBottom:`1px solid ${D.blueGh}`,fontSize:13}}>
                  <span style={{fontWeight:600}}>{u.name}</span>
                  <span style={{color:D.t3}}>{u.branches.join(", ")}</span>
                </div>)}
              </div>
            </div>
          </div>}
          {view==="finance"&&isPatron&&<FinanceDash debts={DEBTS}/>}
          {view==="pos"&&<QuickPOS branchType={branchInfo?.type}/>}
          {view==="transfer"&&<TransferMod/>}
          {view==="recon"&&isPatron&&<BankRecon/>}
        </div>
      </main>
    </div>
  </>);
}


    const root = ReactDOM.createRoot(document.getElementById('root'));
    root.render(<BardaksOS />);
  </script>
</body>
</html>
