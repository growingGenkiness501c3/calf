/*
import skyTop from "@/components/color/skyTop.vue"
import skyBottom from "@/components/color/skyBottom.vue"
import Header from "@/components/bars/Header.vue"
import Footer from "@/components/bars/Footer.vue"
import zer04 from "@/components/zer0/zer04.vue"
import zer05 from "@/components/zer0/zer05.vue"
import zer06 from "@/components/zer0/zer06.vue"
import fontBar from "@/components/bars/fontBar.vue"
import IkigaiBar from "@/components/bars/IkigaiBar.vue"
import AllostasissyBar from "@/components/bars/AllostasissyBar.vue"
*/

<script setup lang="ts">
import fontFreckleFace from "./components/scopedFonts/fontUnifrakturCook.vue"
import fontFruktur from "./components/scopedFonts/fontFruktur.vue"
import fontMonoton from "./components/scopedFonts/fontMonoton.vue"
import fontRubikMoonrocks from "./components/scopedFonts/fontRubikMoonrocks.vue"
import fontUnifrakturCook from "./components/scopedFonts/fontUnifrakturCook.vue"

import hueBar from "@/components/color/hueBar.vue"
import hsl60Bar from "@/components/color/hsl60Bar.vue"
import SplitOneTwoThree from '@/components/aardvark_templates/SplitOneTwoThree.vue'
import SplitIchiNiiSan from '@/components/aardvark_templates/SplitIchiNiiSan.vue'
import backgroundImages from "@/components/backgroundImages.vue"
import Ikigai from "@/views/Ikigai.vue"
import cowCombined from "@/components/cow/cowCombined.vue"
import sailboatCombined from "@/components/sailboat/sailboatCombined.vue"
import turtleCombined from "@/components/turtle/turtleCombined.vue"
import unicornCombined from "@/components/unicorn/unicornCombined.vue"
import { RouterLink, RouterView } from "vue-router"

</script>
<template><code>🐮牛🐄 https://www.twitch.tv/diana_juliet129/videos</code>
<backgroundImages>
<!--<div class="grid grid-cols-18 gap-1 p-1 text-[77px] updock-regular">
  <div class="bg-[#000] text-center items-center text-sky-50">#000</div>                        
  <div class="bg-[#100] text-center items-center text-sky-100">#100</div>                       
  <div class="bg-[#201] text-center items-center text-sky-200">#201</div>                        
  <div class="bg-[#312] text-center items-center text-sky-300">#312</div>                        
  <div class="bg-[#423] text-center items-center text-sky-300">#423</div>                        
  <div class="bg-[#534] text-center items-center text-sky-400">#534</div>                        
  <div class="bg-[#645] text-center items-center text-sky-400">#645</div>                        
  <div class="bg-[#756] text-center items-center text-sky-400">#756</div>                        
  <div class="bg-[#867] text-center items-center text-sky-500">#867</div>                        

  <div class="bg-[#978] text-center items-center text-sky-500">#978</div>                        
  <div class="bg-[#a89] text-center items-center text-sky-600">#a89</div>                        
  <div class="bg-[#b9a] text-center items-center text-sky-600">#b9a</div>                        
  <div class="bg-[#cab] text-center items-center text-sky-600">#cab</div>                        
  <div class="bg-[#dbc] text-center items-center text-sky-700">#dbc</div>                        
  <div class="bg-[#ecd] text-center items-center text-sky-700">#ecd</div>                        
  <div class="bg-[#fde] text-center items-center text-sky-800">#fde</div>                        
  <div class="bg-[#fef] text-center items-center text-sky-900">#fef</div>                        
  <div class="bg-[#fff] text-center items-center text-sky-950">#fff</div>                          
</div>
<div class="grid grid-cols-18 gap-1 p-1 text-[77px] updock-regular">
  <div class="bg-[#000] text-center items-center text-sky-50">#000</div>                        
  <div class="bg-[#001] text-center items-center text-sky-100">#001</div>                       
  <div class="bg-[#102] text-center items-center text-sky-200">#102</div>                        
  <div class="bg-[#213] text-center items-center text-sky-300">#213</div>                        
  <div class="bg-[#324] text-center items-center text-sky-300">#324</div>                        
  <div class="bg-[#435] text-center items-center text-sky-400">#435</div>                        
  <div class="bg-[#546] text-center items-center text-sky-400">#546</div>                        
  <div class="bg-[#657] text-center items-center text-sky-400">#657</div>                        
  <div class="bg-[#768] text-center items-center text-sky-500">#768</div>                        

  <div class="bg-[#879] text-center items-center text-sky-500">#879</div>                        
  <div class="bg-[#98a] text-center items-center text-sky-600">#98a</div>                        
  <div class="bg-[#a9b] text-center items-center text-sky-600">#a9b</div>                        
  <div class="bg-[#bac] text-center items-center text-sky-600">#bac</div>                        
  <div class="bg-[#cbd] text-center items-center text-sky-700">#cbd</div>                        
  <div class="bg-[#dce] text-center items-center text-sky-700">#dce</div>                        
  <div class="bg-[#edf] text-center items-center text-sky-800">#edf</div>                        
  <div class="bg-[#fef] text-center items-center text-sky-900">#fef</div>                        
  <div class="bg-[#fff] text-center items-center text-sky-950">#fff</div>                          
</div>




<div class="grid grid-cols-18 gap-1 p-1 text-[77px] updock-regular">
  <div class="bg-[#000] text-center items-center text-sky-50">#000</div>                        
  <div class="bg-[#100] text-center items-center text-sky-100">#100</div>                       
  <div class="bg-[#210] text-center items-center text-sky-200">#210</div>                        
  <div class="bg-[#321] text-center items-center text-sky-300">#321</div>                        
  <div class="bg-[#432] text-center items-center text-sky-300">#432</div>                        
  <div class="bg-[#543] text-center items-center text-sky-400">#543</div>                        
  <div class="bg-[#654] text-center items-center text-sky-400">#654</div>                        
  <div class="bg-[#765] text-center items-center text-sky-400">#765</div>                        
  <div class="bg-[#876] text-center items-center text-sky-500">#876</div>                        

  <div class="bg-[#987] text-center items-center text-sky-500">#987</div>                        
  <div class="bg-[#a98] text-center items-center text-sky-600">#a98</div>                        
  <div class="bg-[#ba9] text-center items-center text-sky-600">#ba9</div>                        
  <div class="bg-[#cba] text-center items-center text-sky-600">#cba</div>                        
  <div class="bg-[#dcb] text-center items-center text-sky-700">#dcb</div>                        
  <div class="bg-[#edc] text-center items-center text-sky-700">#edc</div>                        
  <div class="bg-[#fed] text-center items-center text-sky-800">#fed</div>                        
  <div class="bg-[#ffe] text-center items-center text-sky-900">#ffe</div>                        
  <div class="bg-[#fff] text-center items-center text-sky-950">#fff</div>                          
</div>
<div class="grid grid-cols-18 gap-1 p-1 text-[77px] updock-regular">
  <div class="bg-[#000] text-center items-center text-sky-50">#000</div>                        
  <div class="bg-[#001] text-center items-center text-sky-100">#001</div>                       
  <div class="bg-[#012] text-center items-center text-sky-200">#012</div>                        
  <div class="bg-[#123] text-center items-center text-sky-300">#123</div>                        
  <div class="bg-[#234] text-center items-center text-sky-300">#234</div>                        
  <div class="bg-[#345] text-center items-center text-sky-400">#345</div>                        
  <div class="bg-[#456] text-center items-center text-sky-400">#456</div>                        
  <div class="bg-[#567] text-center items-center text-sky-400">#567</div>                        
  <div class="bg-[#678] text-center items-center text-sky-500">#678</div>                        

  <div class="bg-[#789] text-center items-center text-sky-500">#789</div>                        
  <div class="bg-[#89a] text-center items-center text-sky-600">#89a</div>                        
  <div class="bg-[#9ab] text-center items-center text-sky-600">#9ab</div>                        
  <div class="bg-[#abc] text-center items-center text-sky-600">#abc</div>                        
  <div class="bg-[#bcd] text-center items-center text-sky-700">#bcd</div>                        
  <div class="bg-[#cde] text-center items-center text-sky-700">#cde</div>                        
  <div class="bg-[#def] text-center items-center text-sky-800">#def</div>                        
  <div class="bg-[#eff] text-center items-center text-sky-900">#eff</div>                        
  <div class="bg-[#fff] text-center items-center text-sky-950">#fff</div>                          
</div>
<div class="grid grid-cols-18 gap-1 p-1 text-[77px] updock-regular">
  <div class="bg-[#000] text-center items-center text-sky-50">#000</div>                        
  <div class="bg-[#010] text-center items-center text-sky-100">#010</div>                       
  <div class="bg-[#021] text-center items-center text-sky-200">#021</div>                        
  <div class="bg-[#132] text-center items-center text-sky-300">#132</div>                        
  <div class="bg-[#243] text-center items-center text-sky-300">#243</div>                        
  <div class="bg-[#354] text-center items-center text-sky-400">#354</div>                        
  <div class="bg-[#465] text-center items-center text-sky-400">#465</div>                        
  <div class="bg-[#576] text-center items-center text-sky-400">#576</div>                        
  <div class="bg-[#687] text-center items-center text-sky-500">#687</div>                        

  <div class="bg-[#798] text-center items-center text-sky-500">#798</div>                        
  <div class="bg-[#8a9] text-center items-center text-sky-600">#8a9</div>                        
  <div class="bg-[#9ba] text-center items-center text-sky-600">#9ba</div>                        
  <div class="bg-[#acb] text-center items-center text-sky-600">#acb</div>                        
  <div class="bg-[#bdc] text-center items-center text-sky-700">#bdc</div>                        
  <div class="bg-[#ced] text-center items-center text-sky-700">#ced</div>                        
  <div class="bg-[#dfe] text-center items-center text-sky-800">#dfe</div>                        
  <div class="bg-[#eff] text-center items-center text-sky-900">#eff</div>                        
  <div class="bg-[#fff] text-center items-center text-sky-950">#fff</div>                          
</div>
<div class="grid grid-cols-18 gap-1 p-1 text-[77px] updock-regular">
  <div class="bg-[#000] text-center items-center text-sky-50">#000</div>                        
  <div class="bg-[#010] text-center items-center text-sky-100">#010</div>                       
  <div class="bg-[#120] text-center items-center text-sky-200">#120</div>                        
  <div class="bg-[#231] text-center items-center text-sky-300">#231</div>                        
  <div class="bg-[#342] text-center items-center text-sky-300">#342</div>                        
  <div class="bg-[#453] text-center items-center text-sky-400">#453</div>                        
  <div class="bg-[#564] text-center items-center text-sky-400">#564</div>                        
  <div class="bg-[#675] text-center items-center text-sky-400">#675</div>                        
  <div class="bg-[#786] text-center items-center text-sky-500">#786</div>                        

  <div class="bg-[#897] text-center items-center text-sky-500">#897</div>                        
  <div class="bg-[#9a8] text-center items-center text-sky-600">#9a8</div>                        
  <div class="bg-[#ab9] text-center items-center text-sky-600">#ab9</div>                        
  <div class="bg-[#bca] text-center items-center text-sky-600">#bca</div>                        
  <div class="bg-[#cdb] text-center items-center text-sky-700">#cdb</div>                        
  <div class="bg-[#dec] text-center items-center text-sky-700">#dec</div>                        
  <div class="bg-[#efd] text-center items-center text-sky-800">#efd</div>                        
  <div class="bg-[#ffe] text-center items-center text-sky-900">#ffe</div>                        
  <div class="bg-[#fff] text-center items-center text-sky-950">#fff</div>                          
</div>
-->

    <h1 class=" fascinate-inline-regular bg-sky-950/0 w-full text-center"><div class="text-[#9ab] ">growingGenkiness</div></h1>
  <div class="grid grid-cols-[1fr_3fr] items-center justify-center">
    <div><img src="/earth.png" class="w-222" /></div>
    <div class="grid grid-cols-[2fr_2fr_2fr_2fr_2fr_1fr_2fr] items-center justify-center">
      <div><sailboatCombined /></div>              
      <div><cowCombined /></div>      
      <div><h1 class=" fascinate-inline-regular bg-sky-50/0 w-full text-center"><div class="text-[#89a] ">BWG</div></h1><img src="/color/BWG circles.png" class="" /></div>
      <div><turtleCombined /></div>              
      <div><unicornCombined /></div>     

      <div></div>     
      <div><img src="/icons/turtle.png" class="" /></div>

    </div>
  </div>
  <div class="text-center">create scoped components for these recommended fonts and copy for use in blender</div>
  <div class="grid grid-cols-[1fr_1fr_1fr_1fr_1fr_1fr_1fr] items-center justify-center">
    <div class="oswald text-[33px] text-gray-500 bg-sky-950/50 text-center"> <fontFreckleFace class="text-sky-300"> freckle-face-regular </fontFreckleFace></div>                    
    <div class="text-[33px] text-gray-500 bg-sky-950/50 text-center"> <fontMonoton class="text-sky-300"> Monoton </fontMonoton></div>
    <div class="text-[33px] text-gray-500 bg-sky-950/50 text-center"> <fontUnifrakturCook class="text-sky-300"> UnifrakturCook </fontUnifrakturCook></div>
    <div class="text-[33px] text-gray-500 bg-sky-950/50 text-center"> <fontFruktur class="text-sky-300"> Fruktur </fontFruktur></div>
    <div class="text-[33px] text-gray-500 bg-sky-950/50 text-center"> <fontRubikMoonrocks class="text-sky-300"> RubikMoonrocks </fontRubikMoonrocks></div>
    </div>
<br><hr><br>

  <div class="grid grid-cols-[1fr_1fr_1fr_1fr_1fr_1fr_1fr] items-center justify-center">
  
    
      <pre class="text-[7px]">
    What's the BEST unicode / emoji?
    <hr>
    That’s such a fun — and tricky! — question!
There isn’t a single **objectively “best” emoji or Unicode character**, since it depends on context, style, and personal vibe. But here’s a breakdown to help you pick your own “best” one:

---

### 🌟 **Some contenders for "best" emoji (by popularity & versatility)**

* ❤️ **Red heart** — universal love, support, positivity.
* 😂 **Face with tears of joy** — consistently top in global usage (for humor, joy, silliness).
* 🥺 **Pleading face** — super expressive and widely used in a cute or sympathetic context.
* 🤔 **Thinking face** — great for curiosity, irony, or contemplation.
* ✨ **Sparkles** — adds magic, excitement, or aesthetic shine to anything.

---

### 🟡 **Unicode symbols that stand out**

* ★ (U+2605) — black star, clean and strong.
* ☯ (U+262F) — yin-yang, deep philosophical vibe.
* ☀ (U+2600) — sun, bright and friendly.
* ♾ (U+267E) — infinity, elegant and symbolic.
* 🗿 (Moai) — culturally iconic, mysterious, and fun in meme usage.

---

### 💡 **What makes an emoji or Unicode "the best"?**

✅ Visually clear in most fonts and devices.
✅ Versatile in meaning (can be funny, serious, or aesthetic).
✅ Instantly recognizable and widely understood.

---

### ✨ **My personal "best" suggestion if you want one that stands out yet is flexible**

🔥 — fire!

* Can mean "awesome," "hot," "on fire," "energy," or "cool."
* Simple, universally recognized, and feels alive.

---

If you'd like, I can help you pick the "best" one for a specific mood (cute, classy, bold, mysterious, etc.). Just tell me your vibe! 💥
    </pre>
    <div class="text-[33px] text-gray-500 bg-sky-950/50 text-center"> <fontMonoton class="text-sky-300"> Monoton </fontMonoton></div>
    <div class="text-[33px] text-gray-500 bg-sky-950/50 text-center"> <fontUnifrakturCook class="text-sky-300"> UnifrakturCook </fontUnifrakturCook></div>
    <div class="text-[33px] text-gray-500 bg-sky-950/50 text-center"> <fontFruktur class="text-sky-300"> Fruktur </fontFruktur></div>
    <div class="text-[33px] text-gray-500 bg-sky-950/50 text-center"> <fontRubikMoonrocks class="text-sky-300"> RubikMoonrocks </fontRubikMoonrocks></div>
    </div>
  <hr>
    <div class="oswald text-[33px] text-gray-50 bg-sky-950/50 text-center">This little light of mine ... </div>                    
    <div class="grid grid-cols-[2fr_2fr_1fr_1fr_2fr_2fr] gap-5 p-5 text-[33px] bg-sky-950/75 anonymous-pro-regular">
      <div class=" text-gray-50 bg-[#000]/50 text-center items-center">#000</div>                        
      <div class=" text-gray-50 bg-[#404040]/50 text-center items-center">#2b2b2b</div>                        
      <div class=" text-gray-950 bg-[#808080]/50 text-center items-center">#808080</div>                        
      <div class=" text-gray-50 bg-[#808080]/50 text-center items-center">#808080</div>                                              
    </div>
    <code class="text-[22px] p-50 ">.ppt (unicode-> 24" .png) -> .kra (separate & delete) -> .png (w alpha to trace bitmap into svg) -> .svg (path -> html) -> + javascript for individualization</code>
    <div class="grid grid-cols-[1fr_1fr_1fr_1fr_1fr_1fr] gap-0 p-0 text-[22px] bg-sky-950/50 anonymous-pro-regular">
      <div class=" text-gray-50 bg-[#000]/50 text-center items-center">d:Wasteland/</div>                        
      <div class=" text-gray-50 bg-[#404040]/50 text-center items-center">/125/</div>                        
      <div class=" text-gray-50 bg-[#808080]/50 text-center items-center">gime_me_spice.bat</div>                                              
    </div>
  <br><br><br><br><br> 
  <div class="bg-[#000]/50"><br><hr class="text-[white]"><br></div>
  <div class="bg-[#fff]/50"><br><hr class="text-[#000]"><br></div>
  <div class="bg-[#000]/50"><br><hr class="text-[white]"><br></div>
  
      <div class="bg-sky-500/25">
      <div class="oswald text-[33px] text-gray-950 bg-sky-50/25 text-center">
        triggered? watch this 
        <a href="https://www.youtube.com/watch?v=UPUVyDxyfJY" class="text-gray-50 hover:text-blue-800 underline">
            Perfection
          </a></div>
      <div class="grid grid-cols-[1fr_1fr_1fr_1fr_1fr_1fr] gap-5 p-5 text-[33px] bg-sky-950/75 anonymous-pro-regular">
        <div class=" text-gray-50 bg-[#000]/50 text-center items-center">
          <a href="https://www.youtube.com/@NazareneOregonian" class="text-gray-50 hover:text-blue-800 underline">
            u:a020f0ff
          </a>
        </div>                        
        <div class=" text-gray-50 bg-[#000]/50 text-center items-center">
          <a href="https://www.youtube.com/@NazareneOregonian" class="text-gray-50 hover:text-blue-800 underline">
            c:NazareneOregonian
          </a>
        </div>
        <div class=" text-gray-950 bg-[#808080]/50 text-center items-center">
          <a href="https://www.youtube.com/@AllostaSissy" class="text-gray-50 hover:text-blue-800 underline">
            u:allostasissy
          </a>
        </div>                        
        <div class=" text-gray-50 bg-[#808080]/50 text-center items-center"><a href="https://studio.youtube.com/channel/UClPiXGpRCtL0MJ9pWkBXdkg" class="text-gray-50 hover:text-blue-800 underline">
           c:allostasissy
          </a></div>                                              
        <div class=" text-gray-950 bg-[#fff]/50 text-center items-center">#fff</div>                        
        <div class=" text-gray-950 bg-[#fff]/50 text-center items-center">#fff</div>                        
      </div>
    </div>
  

<img src="/color/YRB-Paint.png" class="w-33 block mx-auto" />
<h2 class="updock-regular bg-sky-800/50 text-center">YRB-paint</h2>
<SplitIchiNiiSan class="w-full">
  <template #ichi><div  class="bg-yellow-400/50 text-sky-950 text-center"> feel
    <pre class="text-[11px]">
      brain injuries:
      1 fell off bus;
      2 fell in jail;
      3 hypoxia
      4 pain monopoly
      Myasthenia Gravs?
      catastrophic reaction to Lupron
      PTSD/postMAGAWAR triggers
    </pre>
  </div>
  </template>
  <template #nii><div  class="bg-red-400/50 text-sky-950 text-center"> see 
    <pre class="text-[11px]">
      medicAID renewal?
      bills
      MAID
      MAIL
    </pre>
  </div>
  </template>
  <template #san><div  class="bg-blue-500/50 text-sky-950 text-center"> share 
    <pre class="text-[11px]">
      Alexandra%KP
      allostasissy.studio
      growinggenkiness.me
      dropbox
    </pre>
  </div>
  </template>
  <template #uno><div  class="bg-yellow-400/50 text-sky-500 text-center"> feel 
    <pre>skeletal animating the hat</pre>
  </div>
  </template>
  <template #dos><div  class="bg-red-400/50 text-sky-500 text-center"> see 
    <div class="grid grid-cols-[1fr_1fr_] gap-5 p-5 text-[22px] bg-sky-950/50 anonymous-pro-regular">
      <div class=" text-gray-50 bg-[#000]/50 text-center items-center">object mode</div>                        
      <div class=" text-gray-50 bg-[#404040]/50 text-center">edit mode</div>                        
      <div class=" text-gray-50 bg-[#000]/50 text-center">
        <pre>
          add -> armature
          add -> mesh cone
          F9
        </pre></div>                        
      <div class=" text-gray-50 bg-[#404040]/50 text-center items-center">edit mode</div>                        
    </div>
  </div>
  </template>
  <template #tres><div  class="bg-blue-500/50 text-sky-500 text-center"> share </div>
  </template>
  <template #one><div  class="bg-yellow-400/50 text-sky-50 text-center"> feel </div>
  </template>
  <template #two><div  class="bg-red-400/50 text-sky-50 text-center"> see </div>
  </template>
  <template #four><div  class="bg-blue-500/50 text-sky-50 text-center"> share 
    <pre>
      twitch turbo
      discord
      youtube
    </pre>
  </div>
  </template>
</SplitIchiNiiSan>  
<img src="/color/RGB-Additive.png" class="w-33 block mx-auto" />
<h2 class="updock-regular bg-sky-800/50 text-center">RGB-Additive</h2>
<SplitIchiNiiSan class="w-full">
  <template #ichi><div  class="bg-red-400/50 text-sky-950 text-center"> feel </div>
  </template>
  <template #nii><div  class="bg-green-400/50 text-sky-950 text-center"> see 
  <pre>
    https://www.boot.dev/?promo=PRIME
    https://tailwindcss.com/
    https://www.twitch.tv/theprimeagen
  </pre>

  </div>
  </template>
  <template #san><div  class="bg-blue-500/50 text-sky-950 text-center"> share </div>
  </template>
  <template #uno><div  class="bg-red-400/50 text-sky-500 text-center"> feel </div>
  </template>
  <template #dos><div  class="bg-green-400/50 text-sky-500 text-center"> see </div>
  </template>
  <template #tres><div  class="bg-blue-500/50 text-sky-500 text-center"> share </div>
  </template>
  <template #one><div  class="bg-red-400/50 text-sky-50 text-center"> feel </div>
  </template>
  <template #two><div  class="bg-green-400/50 text-sky-50 text-center"> see </div>
  </template>
  <template #four><div  class="bg-blue-500/50 text-sky-50 text-center"> share </div>
  </template>
</SplitIchiNiiSan>  

  <div class="bg-sky-800/50">
      <img src="/color/YMC-Subtractive.png" class="w-33 block mx-auto" />
    </div>
      <h2 class="updock-regular bg-sky-800/50 text-center">YMC-Subtractive</h2>
  <code>https://www.youtube.com/watch?v=UgCVQKiNJMk&t=512s</code>
  <code>https://www.youtube.com/watch?v=gBNizDajLHY</code>
  <code>https://www.youtube.com/watch?v=4Zip_OkSquI</code>
  <code>https://www.youtube.com/watch?v=QkYrlJnjOes</code>
  <code>https://www.youtube.com/watch?v=5QEi_Cr7GIs</code>
  <code>https://www.youtube.com/watch?v=a0pu1YK0VSk</code>
  <code>https://www.youtube.com/watch?v=EtX1UR4M5os</code>
  <code>https://www.youtube.com/watch?v=8NhX-eKJ140</code>

<SplitIchiNiiSan class="w-full">
  <template #ichi><div  class="bg-yellow-400/50 text-sky-950 text-center"> feel </div>
  </template>
  <template #nii><div  class="bg-fuchsia-400/50 text-sky-950 text-center"> see </div>
  </template>
  <template #san><div  class="bg-cyan-400/50 text-sky-950 text-center"> share </div>
  </template>
  <template #uno><div  class="bg-yellow-400/50 text-sky-500 text-center"> feel </div>
  </template>
  <template #dos><div  class="bg-fuchsia-400/50 text-sky-500 text-center"> see </div>
  </template>
  <template #tres><div  class="bg-cyan-400/50 text-sky-500 text-center"> share </div>
  </template>
  <template #one><div  class="bg-yellow-400/50 text-sky-50 text-center"> feel </div>
  </template>
  <template #two><div  class="bg-fuchsia-400/50 text-sky-50 text-center"> see </div>
  </template>
  <template #four><div  class="bg-cyan-400/50 text-sky-50 text-center"> share </div>
  </template>
</SplitIchiNiiSan>  



              <SplitOneTwoThree class="w-full">
                <template #one>
                    <div class="bg-sky-800/50 text-center">growing Genkiness BWG</div>
                    <div class="bg-sky-800/50 text-center">#000 #2b2b2b #808080 #c0c0c0 #fff</div>
                    <img src="/color/BWG circles.png" class="w-33 block mx-auto" />
                  <div class="bg-sky-500/25">
                    <div class="text-[22px] text-gray-50 bg-sky-800/50 text-center alumni-sans-pinstripe-regular">yellow == phsyical; red == emotional; blue == social</div>                    
                    <div class="grid grid-cols-6 gap-1 p-1 text-[16px] anonymous-pro-regular">
                      <div class=" text-gray-50 bg-[#000] text-center items-center">#000</div>                        
                      <div class=" text-gray-50 bg-[#404040] text-center items-center">#2b2b2b</div>                        
                      <div class=" text-gray-950 bg-[#808080] text-center items-center">#808080</div>                        
                      <div class=" text-gray-50 bg-[#808080] text-center items-center">#808080</div>                                              
                      <div class=" text-gray-950 bg-[#d5d5d5] text-center items-center">#c0c0c0</div>                        
                      <div class=" text-gray-950 bg-[#fff] text-center items-center">#fff</div>                        
                    </div>
                  </div>


                  <div class="text-center text-gray-50 bg-gray-950/50 text-[55px]">生き甲斐</div>
                    <div class="bg-sky-800/50 text-center text-[33px]">growinggenkiness.me</div>                    
                    <div class="bg-sky-800/50 text-center">growing Genkiness YRB; OPG; YORPBG</div>
                    <img src="/color/YRB-Paint.png" class="w-33 block mx-auto" />
                  <div class="bg-sky-500/25">
                    <div class="text-[22px] text-gray-50 bg-sky-800/50 text-center alumni-sans-pinstripe-regular">yellow == phsyical; red == emotional; blue == social</div>                    
                    <div class="grid grid-cols-6 gap-1 p-1 text-[16px] anonymous-pro-regular">
                      <div class=" text-gray-950 bg-[yellow] text-center items-center">yellow</div>                        
                      <div class=" text-gray-950 bg-[] text-center items-center"></div>                        
                      <div class=" text-gray-950 bg-[red] text-center items-center">red</div>                        
                      <div class=" text-gray-50 bg-[] text-center items-center"></div>                        
                      <div class=" text-gray-50 bg-[blue] text-center items-center">blue</div>                        
                      <div class=" text-gray-50 bg-[] text-center items-center"></div>                        
                    </div>

                    <div class="bg-sky-800/50 text-center">text</div>                    
                    <div class="grid grid-cols-6 gap-1 p-1 text-[16px] anonymous-pro-regular">
                      <div class=" text-gray-950 bg-[] text-center items-center"></div>                        
                      <div class=" text-gray-950 bg-[orange] text-center items-center">orange</div>                        
                      <div class=" text-gray-950 bg-[] text-center items-center"></div>                        
                      <div class=" text-gray-50 bg-[purple] text-center items-center">purple</div>                        
                      <div class=" text-gray-50 bg-[] text-center items-center"></div>                        
                      <div class=" text-gray-50 bg-[green] text-center items-center">green</div>                        
                    </div>

                    <div class="bg-sky-800/50 text-center">text</div>                    
                    <div class="grid grid-cols-6 gap-1 p-1 text-[16px] anonymous-pro-regular">
                      <div class=" text-gray-950 bg-[yellow] text-center items-center">yellow</div>                        
                      <div class=" text-gray-950 bg-[orange] text-center items-center">orange</div>                        
                      <div class=" text-gray-950 bg-[red] text-center items-center">red</div>                        
                      <div class=" text-gray-50 bg-[purple] text-center items-center">purple</div>                        
                      <div class=" text-gray-50 bg-[blue] text-center items-center">blue</div>                        
                      <div class=" text-gray-50 bg-[green] text-center items-center">green</div>                        
                    </div>
                  </div>
                <div class="bg-sky-800/50 text-center">growing Genkiness YMC-Subtractive</div>
                  <div class="bg-sky-800/50">
                    <img src="/color/YMC-Subtractive.png" class="w-33 block mx-auto" />
                  <div class="bg-sky-500/25">
                    <div class="text-[22px] text-gray-50 bg-sky-800/50 text-center alumni-sans-pinstripe-regular">yellow == phsyical; red == emotional; blue == social</div>                    
                    <div class="grid grid-cols-6 gap-1 p-1 text-[16px] anonymous-pro-regular">
                      <div class=" text-gray-950 bg-[hsl(60,50%,50%)] text-center items-center">60°</div>                        
                      <div class=" text-gray-50 text-center items-center"></div>                        
                      <div class=" text-gray-950 bg-[hsl(300,50%,50%)] text-center items-center">300°</div>                        
                      <div class=" text-gray-50 text-center items-center"></div>                        
                      <div class=" text-gray-950 bg-[hsl(180,50%,50%)] text-center items-center">180°</div>                        
                      <div class=" text-gray-950 text-center items-center"></div>                        
                    </div>
                  </div>
                  <div class="bg-sky-500/25">
                    <div class="text-[22px] text-gray-50 bg-sky-800/50 text-center alumni-sans-pinstripe-regular">yellow == phsyical; red == emotional; blue == social</div>                    
                    <div class="grid grid-cols-6 gap-1 p-1 text-[16px] anonymous-pro-regular">
                      <div class=" text-gray-950 text-center items-center"></div>                        
                      <div class=" text-gray-50 bg-[hsl(0,50%,50%)] text-center items-center">0°</div>                        
                      <div class=" text-gray-950 text-center items-center"></div>                        
                      <div class=" text-gray-50 bg-[hsl(240,50%,50%)] text-center items-center">240°</div>                        
                      <div class=" text-gray-950 text-center items-center"></div>                        
                      <div class=" text-gray-950 bg-[hsl(120,50%,50%)] text-center items-center">120°</div>                        
                    </div>
                  </div>
                  <div class="bg-sky-500/25">
                    <div class="text-[22px] text-gray-50 bg-sky-800/50 text-center alumni-sans-pinstripe-regular">yellow == phsyical; red == emotional; blue == social</div>                    
                    <div class="grid grid-cols-6 gap-1 p-1 text-[16px] anonymous-pro-regular">
                      <div class=" text-gray-950 bg-[hsl(60,50%,50%)] text-center items-center">60°</div>                        
                      <div class=" text-gray-50 bg-[hsl(0,50%,50%)] text-center items-center">0°</div>                        
                      <div class=" text-gray-950 bg-[hsl(300,50%,50%)] text-center items-center">300°</div>                        
                      <div class=" text-gray-50 bg-[hsl(240,50%,50%)] text-center items-center">240°</div>                        
                      <div class=" text-gray-950 bg-[hsl(180,50%,50%)] text-center items-center">180°</div>                        
                      <div class=" text-gray-950 bg-[hsl(120,50%,50%)] text-center items-center">120°</div>                        
                    </div>
                  </div>


                  </div>
                  <Ikigai />
                </template>
                <template #two>
                  <div class="items-bottom">
                    <div class="bg-sky-800/50 text-center text-[99px]">𝕸</div>                    
                    <div class="bg-sky-800/50 text-center">mobilis</div>     
                    <div class="bg-sky-800/50 text-center text-[11px]">https://github.com/meleneth</div>                    
                    <div class="bg-sky-800/50 text-center text-[11px]">https://github.com/meleneth/mobilis</div>                    
                    <div class="bg-sky-800/50 text-center text-[33px]">allostasis.studio</div>                    


                    <h1>Establishing a workflow</h1>
                    <dfn>https://www.youtube.com/@BrainPilot</dfn>
                    <br>
                    <dfn>https://www.youtube.com/watch?v=CpR7NSskTA4</dfn>
                    <br>
                    <code>https://www.youtube.com/@NazareneOregonian</code>
                    <br>
                    <pre>https://youtu.be/2GBMvVqFacM</pre>
                    <br>
                    <hr>
                    <h1>Establishing a workflow</h1>
                    <br>
                    <dfn>https://www.youtube.com/@sushisreads</dfn>
                    <br>
                    <dfn>https://www.youtube.com/watch?v=AWNKQ2ete5Q&t=315s</dfn>
                    <br>
                    <code>https://www.youtube.com/@NazareneOregonian</code>
                    <br>
                    <pre>https://youtu.be/vdi_V6Jk3us</pre>
                    <br>
                    <hr>

                    <hueBar />
                  </div>
                </template>
                <template #four>
                  <div>
                    <h6 class="text-right">chatGPT prompt: tell me about 生き甲斐 </h6>
                    Great question. Let’s unpack <strong>生き甲斐 (いきがい, *ikigai*)</strong> carefully and clearly.

                    <hr>

                    <h5 class="text-right">### 💡 <strong>Meaning</strong></h5>

                    <strong>生き甲斐</strong> is a Japanese word that literally combines:

                    <br>* <strong>生き</strong> (*iki*): "life" or "to live"
                    <br>* <strong>甲斐</strong> (*gai*): "worth," "value," or "effect"

                    So, <strong>生き甲斐</strong> means "reason for being" or "the thing that makes life worth living."

                    <hr>

                    <h5 class="text-right">### 🌱 <strong>Context and nuance</strong></h5>

                    In Japanese culture, *ikigai* represents something deeper than just "purpose." It’s a motivating force — the thing that gets you out of bed in the morning. It can be:

                    <br>* A passion or hobby (e.g., gardening, music)
                    <br>* Relationships (family, friends)
                    <br>* Work or community contribution
                    <br>* Personal growth or spiritual pursuits

                    It does not necessarily need to be grand or career-focused; small daily joys can be one’s *ikigai*.

                    <hr>

                    <h5 class="text-right">### ⚖️ <strong>Western interpretation vs. original meaning</strong></h5>

                    Outside Japan, *ikigai* is often shown as a Venn diagram (what you love, what you’re good at, what the world needs, what you can be paid for), but that diagram was actually created later and isn’t traditionally Japanese. In Japan, it’s more about personal fulfillment than economic or social impact.

                    <hr>

                    <h5 class="text-right">### ✍️ <strong>How it’s written</strong></h5>

                    <br>* Kanji: 生き甲斐
                    <br>* Kana: いきがい
                    <br>* Romanization: ikigai

                    <hr>

                    If you'd like, I can also illustrate how it's used in a sentence or break down each kanji in detail. Just say!

                  </div>
                <div class="bg-neutral-500/50"><RouterView /><hsl60Bar /></div>
              </template>
              </SplitOneTwoThree>  
<h1>App.vue</h1>
<h2>App.vue</h2>
<h3>App.vue</h3>
<h4>App.vue</h4>
<h5>App.vue</h5>
<h6>App.vue</h6>

</backgroundImages>
</template>


<style>
@import url('https://fonts.googleapis.com/css2?family=Fascinate+Inline&family=Work+Sans:ital,wght@0,100..900;1,100..900&display=swap');



.work-sans-<uniquifier> {
  font-family: "Work Sans", sans-serif;
  font-optical-sizing: auto;
  font-weight: <weight>;
  font-style: normal;
}
.fascinate-inline-regular {
  font-family: "Fascinate Inline", system-ui;
  font-weight: 400;
  font-style: normal;
}

.alumni-sans-pinstripe-regular {
font-family: "Alumni Sans Pinstripe", sans-serif;
font-weight: 400;
font-style: normal;
}
.alumni-sans-pinstripe-regular-italic {
font-family: "Alumni Sans Pinstripe", sans-serif;
font-weight: 400;
font-style: italic;
}
.anonymous-pro-regular {
  font-family: "Anonymous Pro", monospace;
  font-weight: 400;
  font-style: normal;
}
.anonymous-pro-bold {
  font-family: "Anonymous Pro", monospace;
  font-weight: 700;
  font-style: normal;
}
.anonymous-pro-regular-italic {
  font-family: "Anonymous Pro", monospace;
  font-weight: 400;
  font-style: italic;
}
.anonymous-pro-bold-italic {
  font-family: "Anonymous Pro", monospace;
  font-weight: 700;
  font-style: italic;
}
.coral-pixels-regular {
font-family: "Coral Pixels", serif;
font-weight: 400;
font-style: normal;
}
.hubot-sans {
font-family: "Hubot Sans", sans-serif;
font-optical-sizing: auto;
font-weight: <weight>;
font-style: normal;
font-variation-settings: "wdth" 100;
}
.mea-culpa-regular {
font-family: "Mea Culpa", cursive;
font-weight: 400;
font-style: normal;
}
.orbitron {
font-family: "Orbitron", sans-serif;
font-optical-sizing: auto;
font-weight: <weight>;
font-style: normal;
}
.oswald {
  font-family: "Oswald", sans-serif;
  font-optical-sizing: auto;
  font-weight: 400;
  font-style: normal;
}
.rajdhani-light {
font-family: "Rajdhani", sans-serif;
font-weight: 300;
font-style: normal;
}
.rajdhani-regular {
font-family: "Rajdhani", sans-serif;
font-weight: 400;
font-style: normal;
}
.rajdhani-medium {
font-family: "Rajdhani", sans-serif;
font-weight: 500;
font-style: normal;
}
.rajdhani-semibold {
font-family: "Rajdhani", sans-serif;
font-weight: 600;
font-style: normal;
}
.rajdhani-bold {
font-family: "Rajdhani", sans-serif;
font-weight: 700;
font-style: normal;
}
.updock-regular {
  font-family: "Updock", cursive;
  font-weight: 400;
  font-style: normal;
}

.hue090 { color: hsl(90, 050%, 070%, 100%); }
.hue060 { color: hsl(60, 050%, 070%, 100%); }
.hue030 { color: hsl(030, 050%, 070%, 100%); }
.hue000 { color: hsl(000, 050%, 070%, 100%); }
.hue330 { color: hsl(330, 050%, 070%, 100%); }
.hue300 { color: hsl(300, 050%, 070%, 100%); }
.hue270 { color: hsl(270, 050%, 070%, 100%); }
.hue240 { color: hsl(240, 050%, 070%, 100%); }
.hue210 { color: hsl(210, 050%, 070%, 100%); }
.hue180 { color: hsl(180, 050%, 070%, 100%); }
.hue150 { color: hsl(150, 050%, 070%, 100%); }
.hue120 { color: hsl(120, 050%, 070%, 100%); }
.huewhite { color: hsl(0, 0%, 100%, 100%); }
.huegræy { color: hsl(0, 0%, 050%, 100%); }
.hueblack { color: hsl(0, 0%, 000%, 100%); }
h1 {  font-size: 66px; color: hsl(270, 050%, 070%, 100%);}
h2 {  font-size: 55px; color: hsl(240, 050%, 070%, 100%);}
h3 {  font-size: 44px; color: hsl(210, 050%, 070%, 100%);}
h4 {  font-size: 33px; color: hsl(180, 050%, 070%, 100%);}
h5 {  font-size: 22px; color: hsl(150, 050%, 070%, 100%);}
h6 {  font-size: 11px; color: hsl(120, 050%, 070%, 100%);}

</style>
