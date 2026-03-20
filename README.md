# Ex08 Event Registration Web Application
## Date:20.3.2026

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:

```
main page 


css


height: 1047.108642578125px;
width: 424.96673583984375px;
display: flex;
flex-direction: column;
background-color: #0b0c1f;
padding: 96px 16px 48px;

Tailwind css

h-[1047.108642578125px] w-[424.96673583984375px] flex flex-col bg-[#0b0c1f] px-4 pt-24 pb-12


HTML+Tailwind

<div class="h-[1047.108642578125px] w-[424.96673583984375px] flex flex-col bg-[#0b0c1f] px-4 pt-24 pb-12">
  <div class="h-[500px] w-[500px] flex flex-col bg-[#f7f3ff] rounded-full"></div>
  <div class="h-[400px] w-[400px] flex flex-col bg-[#faffff] rounded-full"></div>
  <div class="h-[999.9000244140625px] w-[328px] flex flex-col gap-16">
    <div class="h-[145.90000915527344px] w-[328px] flex flex-col items-center gap-4">
      <div class="w-[147.15000915527344px] h-[24.600000381469727px] flex items-center gap-2 bg-[#f7f3ff] px-3 py-1 rounded-full border-[0.800000011920929px] border-solid border-[#eee7ff]">
        <div class="h-2 w-2 flex flex-col items-center bg-[#ac89ff] rounded-full"></div>
        <span class="font-bold text-[10px] text-center text-[#ac89ff]">Access Point 04</span>
      </div>
      <span class="font-bold text-[36px] text-center text-[#e4e3fe]">SYSTEM_ENTRY</span>
      <span class="font-light text-[18px] text-center text-[#a9a9c3]">Initialize your profile to join the next generation of digital architects.</span>
    </div>
    <div class="h-[693px] w-[328px] flex flex-col gap-6">
      <div class="flex h-[394.3999938964844px]">
        <div class="flex flex-col gap-2 self-stretch w-[328px]">
          <span class="font-bold text-[10px] text-[#99f7ff]">Full Name</span>
          <div class="h-[57.60000228881836px] w-[328px] flex flex-col bg-[#7a7b8c] rounded-3xl border-[0.800000011920929px] border-solid border-[#c7c7ce]">
            <div class="w-[326.3999938964844px] h-14 flex px-5 py-4">
              <span class="font-normal text-[16px] text-[#f1f1fe]">ALAN TURING</span>
            </div>
            <div class="h-0.5 w-[100px] flex flex-col bg-[#99f7ff]"></div>
          </div>
        </div>
        <div class="flex flex-col gap-2 self-stretch w-[328px]">
          <span class="font-bold text-[10px] text-[#99f7ff]">Email Address</span>
          <div class="h-[57.60000228881836px] w-[328px] flex flex-col bg-[#7a7b8c] rounded-3xl border-[0.800000011920929px] border-solid border-[#c7c7ce]">
            <div class="w-[326.3999938964844px] h-14 flex px-5 py-4">
              <span class="font-normal text-[16px] text-[#f1f1fe]">USER@TECHNOVERSE.IO</span>
            </div>
            <div class="h-0.5 w-[100px] flex flex-col bg-[#99f7ff]"></div>
          </div>
        </div>
        <div class="flex flex-col gap-2 self-stretch w-[328px]">
          <span class="font-bold text-[10px] text-[#99f7ff]">Phone Number</span>
          <div class="h-[57.60000228881836px] w-[328px] flex flex-col bg-[#7a7b8c] rounded-3xl border-[0.800000011920929px] border-solid border-[#c7c7ce]">
            <div class="w-[326.3999938964844px] h-14 flex px-5 py-4">
              <span class="font-normal text-[16px] text-[#f1f1fe]">+1 (555) 000-0000</span>
            </div>
            <div class="h-0.5 w-[100px] flex flex-col bg-[#99f7ff]"></div>
          </div>
        </div>
        <div class="flex flex-col gap-2 self-stretch w-[328px]">
          <span class="font-bold text-[10px] text-[#99f7ff]">College / Institute</span>
          <div class="h-[57.60000228881836px] w-[328px] flex flex-col bg-[#7a7b8c] rounded-3xl border-[0.800000011920929px] border-solid border-[#c7c7ce]">
            <div class="w-[326.3999938964844px] h-14 flex px-5 py-4">
              <span class="font-normal text-[16px] text-[#f1f1fe]">MIT GRADUATE SCHOOL</span>
            </div>
            <div class="h-0.5 w-[100px] flex flex-col bg-[#99f7ff]"></div>
          </div>
        </div>
      </div>
      <div class="h-[80.5999984741211px] w-[328px] flex flex-col gap-2">
        <span class="font-bold text-[10px] text-[#ac89ff]">Event Selection</span>
        <div class="h-[57.60000228881836px] w-[328px] flex flex-col bg-[#7a7b8c] rounded-3xl border-[0.800000011920929px] border-solid border-[#c7c7ce]">
          <div class="w-[326.3999938964844px] h-14 flex px-5 py-4">
            <span class="font-normal text-[16px] text-[#e4e3fe]">SELECT OPERATIONAL SECTOR</span>
          </div>
          <div class="h-[30.399999618530273px] w-6 flex flex-col">
            <span class="font-normal text-[24px] text-[#a9a9c3]">expand_more</span>
          </div>
          <div class="h-0.5 w-[100px] flex flex-col bg-[#ac89ff]"></div>
        </div>
      </div>
      <div class="w-[328px] h-[46px] flex items-center gap-3 px-1 pt-4">
        <div class="h-5 w-5 flex flex-col">
          <div class="h-4 w-4 flex flex-col border-[0.800000011920929px] border-solid border-white"></div>
          <div class="h-5 w-5 flex flex-col bg-[#16172f] rounded border-[0.800000011920929px] border-solid border-[#45465c]"></div>
          <span class="font-normal text-[12px]">check</span>
        </div>
        <div class="w-72 h-[30px] flex">
          <span class="font-normal text-[10px] text-[#a9a9c3]">I accept the  and data privacy policy.</span>
          <span class="font-normal text-[10px] text-[#99f7ff]">Neural Protocols</span>
        </div>
      </div>
      <div class="h-[100px] w-[328px] flex flex-col pt-8">
        <div class="w-[328px] h-[68px] flex justify-center items-center gap-4 bg-[#00f1fe] py-5 rounded-3xl">
          <span class="font-bold text-[20px] text-center text-[#005f64]">REGISTER</span>
          <span class="font-normal text-[24px] text-center text-[#005f64]">arrow_forward</span>
        </div>
      </div>
    </div>
    <div class="h-[57px] w-[328px] flex flex-col items-center gap-8">
      <div class="h-px w-[328px] flex flex-col"></div>
      <div class="w-[168px] h-6 flex gap-12">
        <img class="w-6 h-6 object-cover">
        <img class="w-6 h-6 object-cover">
        <img class="w-6 h-6 object-cover">
      </div>
    </div>
  </div>
</div>

LOGIN PAGE 

css

height: 1080px;
width: 427px;
display: flex;
flex-direction: column;
background-color: #0b0c1f;

h-[1080px] w-[427px] flex flex-col bg-[#0b0c1f]

html

<div class="h-[1080px] w-[427px] flex flex-col bg-[#0b0c1f]">
  <div class="h-[812px] w-[375.20001220703125px] flex flex-col">
    <div class="h-[353px] w-[340px] flex flex-col bg-[#f7f3ff] rounded-full"></div>
    <div class="h-[324.8000183105469px] w-[150.0749969482422px] flex flex-col bg-[#f5feff] rounded-full"></div>
    <div class="h-[812px] w-[375.20001220703125px] flex flex-col"></div>
  </div>
  <div class="h-[1063.300048828125px] w-[375.20001220703125px] flex flex-col gap-10 px-6 py-12">
    <div class="h-[312px] w-[327px] flex flex-col items-center gap-8">
      <div class="w-[327px] h-28 flex justify-center">
        <img class="w-[334px] h-[50px]">
      </div>
      <div class="w-16 h-16 flex justify-center items-center bg-[#16172f] rounded-xl border-[0.800000011920929px] border-solid border-[#ebfdff]">
        <span class="font-normal text-[36px] text-center text-[#99f7ff]">terminal</span>
      </div>
      <span class="font-normal text-[36px] text-center text-[#99f7ff]">TECHNOVERSE</span>
      <span class="font-normal text-[12px] text-center text-[#a9a9c3]">Secure Neural Gateway</span>
    </div>
    <div class="h-[536px] w-[323px] flex flex-col gap-8 bg-[#a7a7b2] p-8 rounded-xl border-[0.800000011920929px] border-solid border-[#dadade]">
      <div class="h-[348.8000183105469px] w-[261.6000061035156px] flex flex-col gap-6">
        <div class="h-[57.60000228881836px] w-[261.6000061035156px] flex flex-col">
          <div class="h-[15px] w-[71.625px] flex flex-col bg-[#101127] px-1">
            <span class="font-normal text-[10px] text-[#99f7ff]">IDENTIFIER</span>
          </div>
          <div class="w-[261.6000061035156px] h-[57.60000228881836px] flex items-center bg-black pl-4 rounded-xl border-[0.800000011920929px] border-solid border-[#c7c7ce]">
            <span class="font-normal text-[24px] text-[#a9a9c3]">alternate_email</span>
            <div class="h-14 w-[220px] flex flex-col p-4">
              <span class="font-normal text-[16px] text-[#f1f1fe]">user@technoverse.io</span>
            </div>
          </div>
        </div>
        <div class="h-[57.60000228881836px] w-[261.6000061035156px] flex flex-col">
          <div class="h-[15px] w-[110.9625015258789px] flex flex-col bg-[#101127] px-1">
            <span class="font-normal text-[10px] text-[#99f7ff]">ENCRYPTION_KEY</span>
          </div>
          <div class="w-[261.6000061035156px] h-[57.60000228881836px] flex items-center bg-black pl-4 rounded-xl border-[0.800000011920929px] border-solid border-[#c7c7ce]">
            <span class="font-normal text-[24px] text-[#a9a9c3]">lock</span>
            <div class="h-14 w-[180px] flex flex-col p-4">
              <span class="font-normal text-[16px] text-[#f1f1fe]">••••••••••••</span>
            </div>
            <div class="w-10 h-[30.399999618530273px] flex items-center pr-4">
              <span class="font-normal text-[24px] text-center text-[#a9a9c3]">visibility</span>
            </div>
          </div>
        </div>
        <div class="w-[261.6000061035156px] h-4 flex justify-between items-center px-1">
          <div class="w-[123.73750305175781px] h-4 flex items-center gap-2 bg-[#e7dcdc]">
            <div class="h-4 w-4 flex flex-col bg-[#660e0e] rounded border-[0.800000011920929px] border-solid border-[#a2a2ad]"></div>
            <span class="font-normal text-[10px] text-[#a9a9c3]">Remember Node</span>
          </div>
          <span class="font-normal text-[10px] text-[#491db1]">Reset Access</span>
        </div>
        <div class="h-[145.60000610351562px] w-[261.6000061035156px] flex flex-col gap-4 pt-4">
          <div class="w-[261.6000061035156px] h-14 flex items-center bg-[#00f1fe] py-4 rounded-xl">
            <span class="font-bold text-[16px] text-center text-[#005f64]">INITIALIZE_LOGIN</span>
          </div>
          <div class="w-[261.6000061035156px] h-[57.60000228881836px] flex items-center bg-[#d3d3d9] py-4 rounded-xl border-[0.800000011920929px] border-solid border-[#e6dcff]">
            <span class="font-bold text-[16px] text-center text-[#ac89ff]">CREATE_NEW_ENTITY</span>
          </div>
        </div>
      </div>
      <div class="h-6 w-[261.6000061035156px] flex flex-col items-center">
        <div class="w-[261.6000061035156px] h-6 flex items-center">
          <div class="h-[0.800000011920929px] w-[261.6000061035156px] flex flex-col items-center border-t-[0.800000011920929px] border-solid border-[#dadade]"></div>
        </div>
        <span class="font-normal text-[10px] text-center text-[#1919df]">Or Connect Via</span>
      </div>
      <div class="w-[261.6000061035156px] h-14 flex justify-center gap-4">
        <div class="w-[45.60000228881836px] h-14 flex items-center bg-black p-3 rounded-xl border-[0.800000011920929px] border-solid border-[#c7c7ce]">
          <img class="w-[23px] h-8 object-cover">
        </div>
        <div class="w-[49.60000228881836px] h-14 flex items-center bg-black p-3 rounded-xl border-[0.800000011920929px] border-solid border-[#c7c7ce]">
          <span class="font-normal text-[24px] text-center text-[#a9a9c3]">terminal</span>
        </div>
        <div class="w-[49.60000228881836px] h-14 flex items-center bg-black p-3 rounded-xl border-[0.800000011920929px] border-solid border-[#c7c7ce]">
          <span class="font-normal text-[24px] text-center text-[#a9a9c3]">database</span>
        </div>
      </div>
    </div>
    <div class="h-[77px] w-[327px] flex flex-col items-center gap-4">
      <div class="w-[225px] h-[39px] flex items-center gap-2 bg-[#16172f] px-3 py-1 rounded-full border-[0.800000011920929px] border-solid border-[#dadade]">
        <div class="h-2 w-2 flex flex-col items-center bg-[#99f7ff] rounded-full"></div>
        <span class="font-normal text-[10px] text-center text-[#a9a9c3]">BY SABARISH(25004630)</span>
      </div>
      <span class="font-normal text-[10px] text-center text-[#dddde7]">© 2024 TECHNOVERSE INC. // CORE_V2.0.4</span>
    </div>
  </div>
</div>

DASHBOARD HOME PAGE

css

height: 2716px;
width: 487px;
display: flex;
flex-direction: column;
background-color: #0b0c1f;

h-[2716px] w-[487px] flex flex-col bg-[#0b0c1f]

html


<div class="h-[2716px] w-[487px] flex flex-col bg-[#0b0c1f]">
  <div class="flex flex-col gap-20 self-stretch h-[2694px] px-6 pt-24 pb-32">
    <div class="h-[307px] w-[316px] flex flex-col">
      <div class="h-64 w-64 flex flex-col bg-[#f5feff] rounded-full"></div>
      <div class="h-96 w-96 flex flex-col bg-[#f7f3ff] rounded-full"></div>
      <div class="h-[282.25px] w-[312px] flex flex-col gap-4">
        <span class="font-normal text-[12px] text-[#99f7ff]">SYSTEM ACCESS GRANTED</span>
        <div class="flex self-stretch h-[51px]">
          <span class="font-bold text-[32px] text-[#5f58e5]">TECHNOVERSE</span>
        </div>
        <span class="font-bold text-[48px] text-[#070440]">Welcome to</span>
        <span class="font-normal text-[18px] text-[#1515de]">The digital frontier awaits. Explore high-stakes hackathons, deep-dive AI workshops, and elite coding challenges designed for the next generation of engineers.</span>
      </div>
    </div>
    <div class="flex w-[321px] h-[625px]">
      <div class="h-[271px] w-[312px] flex flex-col gap-8 bg-[#101127] p-6 rounded-xl border-solid border-[#99f7ff]">
        <div class="w-[260px] h-[116px] flex justify-between">
          <div class="h-[116px] w-[187.90000915527344px] flex flex-col gap-1">
            <span class="font-normal text-[12px] text-[#a9a9c3]">CURRENT STATUS</span>
            <span class="font-bold text-[24px] text-[#e4e3fe]">GENESIS HACKATHON LIVE</span>
          </div>
          <div class="w-[81px] h-[43px] flex items-center gap-2 bg-[#f5feff] px-3 py-1 rounded-full border-[0.800000011920929px] border-solid border-[#ebfdff]">
            <span class="font-bold text-[10px] text-[#51a3aa]">LIVE UPLINK</span>
            <div class="h-2 w-[4.425000190734863px] flex flex-col bg-[#99f7ff] rounded-full"></div>
          </div>
        </div>
        <div class="w-[282px] h-[67px] flex gap-8">
          <div class="h-[51px] w-[83.07500457763672px] flex flex-col">
            <span class="font-bold text-[30px] text-[#99f7ff]">1,284</span>
            <span class="font-normal text-[10px] text-[#a9a9c3]">PARTICIPANTS</span>
          </div>
          <div class="h-[51px] w-[74.4000015258789px] flex flex-col">
            <span class="font-bold text-[24px] text-[#ac89ff]">$50K</span>
            <span class="font-normal text-[10px] text-[#a9a9c3]">PRIZE POOL</span>
          </div>
          <div class="h-[51px] w-[65.2874984741211px] flex flex-col">
            <span class="font-bold text-[20px] text-[#e4e3fe]">18h</span>
            <span class="font-normal text-[10px] text-[#a9a9c3]">REMAINING</span>
          </div>
        </div>
      </div>
      <div class="h-[301px] w-[321px] flex flex-col gap-5 bg-[#16172f] px-6 pt-[53px] pb-6 rounded-xl">
        <span class="font-normal text-[12px] text-[#a9a9c3]">UPCOMING SESSION</span>
        <div class="h-[52px] w-[264px] flex flex-col gap-1">
          <span class="font-bold text-[20px] text-[#e4e3fe]">Neural Mesh Protocol</span>
          <span class="font-normal text-[14px] text-[#a9a9c3]">Starting in 45 minutes</span>
        </div>
        <div class="w-[264px] h-5 flex items-center gap-2">
          <span class="font-bold text-[10px] text-center text-[#ac89ff]">VIEW DETAILS</span>
          <span class="font-normal text-[14px] text-center text-[#ac89ff]">arrow_forward</span>
        </div>
      </div>
    </div>
    <div class="w-[312px] h-[72px] flex justify-between items-end">
      <span class="font-bold text-[30px] text-[#e4e3fe]">FEATURED EVENTS</span>
      <div class="flex flex-col grow h-px"></div>
    </div>
    <div class="flex h-[1276.75px]">
      <div class="flex flex-col self-stretch w-[312px] bg-[#101127] rounded-xl">
        <div class="h-48 w-[312px] flex flex-col">
          <img class="w-[312px] h-48 object-cover">
          <div class="h-48 w-[312px] flex flex-col"></div>
          <div class="h-[24.600000381469727px] w-[99.76250457763672px] flex flex-col bg-[#454559] px-3 py-1 rounded-full border-[0.800000011920929px] border-solid border-[#ebfdff]">
            <span class="font-bold text-[10px] text-[#99f7ff]">HACKATHON</span>
          </div>
        </div>
        <div class="flex flex-col gap-6 grow w-[312px] p-6">
          <span class="font-bold text-[20px] text-[#e4e3fe]">Cyber Sentinel 2.0</span>
          <span class="font-normal text-[14px] text-[#a9a9c3]">Forge unbreakable security protocols in this 48-hour offensive and defensive cybersecurity marathon.</span>
          <div class="w-[264px] h-9 flex justify-between items-center">
            <div class="h-[35px] w-[76.0374984741211px] flex flex-col">
              <span class="font-normal text-[10px] text-[#a9a9c3]">DATE</span>
              <span class="font-bold text-[14px] text-[#e4e3fe]">OCT 24-26</span>
            </div>
            <div class="w-[111.30000305175781px] h-9 flex items-center bg-[#00f1fe] px-6 py-2.5 rounded-lg">
              <span class="font-bold text-[12px] text-center text-[#005f64]">REGISTER</span>
            </div>
          </div>
        </div>
        <div class="h-0.5 w-[100px] flex flex-col bg-[#99f7ff]"></div>
      </div>
      <div class="flex flex-col self-stretch w-[312px] bg-[#101127] rounded-xl">
        <div class="h-48 w-[312px] flex flex-col">
          <img class="w-[312px] h-48 object-cover">
          <div class="h-48 w-[312px] flex flex-col"></div>
          <div class="h-[24.600000381469727px] w-[108.95000457763672px] flex flex-col bg-[#454559] px-3 py-1 rounded-full border-[0.800000011920929px] border-solid border-[#eee7ff]">
            <span class="font-bold text-[10px] text-[#ac89ff]">AI WORKSHOP</span>
          </div>
        </div>
        <div class="flex flex-col gap-6 grow w-[312px] p-6">
          <span class="font-bold text-[20px] text-[#e4e3fe]">Neural Nexus Deep Dive</span>
          <span class="font-normal text-[14px] text-[#a9a9c3]">Master transformer architectures and large language model fine-tuning with industry experts.</span>
          <div class="w-[264px] h-9 flex justify-between items-center">
            <div class="h-[35px] w-[52.92499923706055px] flex flex-col">
              <span class="font-normal text-[10px] text-[#a9a9c3]">DATE</span>
              <span class="font-bold text-[14px] text-[#e4e3fe]">NOV 02</span>
            </div>
            <div class="w-[111.30000305175781px] h-9 flex items-center bg-[#00f1fe] px-6 py-2.5 rounded-lg">
              <span class="font-bold text-[12px] text-center text-[#005f64]">REGISTER</span>
            </div>
          </div>
        </div>
        <div class="h-0.5 w-[100px] flex flex-col bg-[#99f7ff]"></div>
      </div>
      <div class="flex flex-col self-stretch w-[312px] bg-[#101127] rounded-xl">
        <div class="h-48 w-[312px] flex flex-col">
          <img class="w-[312px] h-48 object-cover">
          <div class="h-48 w-[312px] flex flex-col"></div>
          <div class="h-[24.600000381469727px] w-[130.85000610351562px] flex flex-col bg-[#454559] px-3 py-1 rounded-full border-[0.800000011920929px] border-solid border-[#e2f0ff]">
            <span class="font-bold text-[10px] text-[#6fb5ff]">CODING CONTEST</span>
          </div>
        </div>
        <div class="flex flex-col gap-6 grow w-[312px] p-6">
          <span class="font-bold text-[20px] text-[#e4e3fe]">Algo-Rhythm Blitz</span>
          <span class="font-normal text-[14px] text-[#a9a9c3]">A high-speed competitive programming clash where only the most efficient code survives.</span>
          <div class="w-[264px] h-9 flex justify-between items-center">
            <div class="h-[35px] w-[49.41250228881836px] flex flex-col">
              <span class="font-normal text-[10px] text-[#a9a9c3]">DATE</span>
              <span class="font-bold text-[14px] text-[#e4e3fe]">NOV 15</span>
            </div>
            <div class="w-[111.30000305175781px] h-9 flex items-center bg-[#00f1fe] px-6 py-2.5 rounded-lg">
              <span class="font-bold text-[12px] text-center text-[#005f64]">REGISTER</span>
            </div>
          </div>
        </div>
        <div class="h-0.5 w-[100px] flex flex-col bg-[#99f7ff]"></div>
      </div>
    </div>
    <div class="w-[312px] h-48 flex justify-center py-12">
      <div class="w-56 h-24 flex gap-4">
        <div class="h-16 w-2 flex flex-col bg-[#99f7ff]"></div>
        <div class="h-12 w-2 flex flex-col bg-[#c2faff]"></div>
        <div class="h-20 w-2 flex flex-col bg-[#adf9ff]"></div>
        <div class="h-8 w-2 flex flex-col bg-[#d6fcff]"></div>
        <div class="h-14 w-2 flex flex-col bg-[#99f7ff]"></div>
        <div class="h-10 w-2 flex flex-col bg-[#ccfbff]"></div>
        <div class="h-24 w-2 flex flex-col bg-[#a3f8ff]"></div>
        <div class="h-16 w-2 flex flex-col bg-[#99f7ff]"></div>
        <div class="h-12 w-2 flex flex-col bg-[#c2faff]"></div>
        <div class="h-20 w-2 flex flex-col bg-[#adf9ff]"></div>
      </div>
    </div>
  </div>
  <div class="w-[360px] h-[72px] flex justify-between items-center bg-[#737482] px-6 py-4">
    <div class="w-[184.5124969482422px] h-8 flex items-center gap-3">
      <span class="font-normal text-[24px] text-[#99f7ff]">terminal</span>
      <span class="font-normal text-[24px] text-[#99f7ff]">TECHNOVERSE</span>
    </div>
    <div class="w-10 h-10 flex items-center gap-4">
      <div class="w-10 h-10 flex justify-center items-center bg-[#16172f] rounded-full border-[0.800000011920929px] border-solid border-[#ebfdff]">
        <img class="w-[38.400001525878906px] h-[38.400001525878906px] object-cover">
      </div>
    </div>
  </div>
  <div class="w-[219px] h-[72px] flex items-center bg-[#111328] px-4 py-3 rounded-tl-2xl rounded-tr-2xl">
    <div class="h-[47.29999923706055px] w-[38.03249740600586px] flex flex-col justify-center items-center gap-1">
      <span class="font-normal text-[24px] text-[#00f1fe]">grid_view</span>
      <span class="font-bold text-[10px] text-[#00f1fe]">HOME</span>
    </div>
    <div class="h-[43px] w-[46.41250228881836px] flex flex-col justify-center items-center gap-1">
      <span class="font-normal text-[24px] text-[#a9a9c3]">confirmation_number</span>
      <span class="font-bold text-[10px] text-[#a9a9c3]">EVENTS</span>
    </div>
    <div class="h-[43px] w-[48.16250228881836px] flex flex-col justify-center items-center gap-1">
      <span class="font-normal text-[24px] text-[#a9a9c3]">account_circle</span>
      <span class="font-bold text-[10px] text-[#a9a9c3]">PROFILE</span>
    </div>
    <div class="h-[43px] w-[56.75px] flex flex-col justify-center items-center gap-1">
      <span class="font-normal text-[24px] text-[#a9a9c3]">how_to_reg</span>
      <span class="font-bold text-[10px] text-[#a9a9c3]">REGISTER</span>
    </div>
  </div>
</div>

CONFIRMATION SUCCESS PAGE 

css

height: 1466px;
width: 355px;
display: flex;
flex-direction: column;
background-color: #0b0c1f;


h-[1466px] w-[355px] flex flex-col bg-[#0b0c1f]

html

<div class="h-[1466px] w-[355px] flex flex-col bg-[#0b0c1f]">
  <div class="w-[360px] h-[84px] flex justify-center items-center bg-[#737482] p-6">
    <div class="w-[190.5124969482422px] h-9 flex items-center gap-3">
      <span class="font-normal text-[30px] text-[#99f7ff]">terminal</span>
      <span class="font-normal text-[24px] text-[#99f7ff]">TECHNOVERSE</span>
    </div>
  </div>
  <div class="w-[403px] h-[1503px] flex justify-center items-center p-6">
    <div class="h-[1241px] w-[375px] flex flex-col">
      <div class="h-[1463px] w-[355px] flex flex-col items-center gap-12">
        <div class="h-[350px] w-[312px] flex flex-col items-center gap-6">
          <div class="w-24 h-32 flex items-center">
            <div class="h-48 w-36 flex flex-col items-center bg-[#f4feff] rounded-full"></div>
          </div>
          <span class="font-normal text-[36px] text-center text-[#00f1fe]">Registration Successful ✅</span>
          <span class="font-normal text-[18px] text-center text-[#a9a9c3]">Your digital uplink has been established. Welcome to the frontier of innovation.</span>
        </div>
        <div class="flex items-center w-[312px] h-[485px]">
          <div class="flex flex-col gap-4 self-stretch w-[312px] bg-[#7a7b8c] p-8 rounded-xl border-[0.800000011920929px] border-solid border-white">
            <span class="font-bold text-[10px] text-[#99f7ff]">Attendee Profile</span>
            <div class="w-[246.40000915527344px] h-12 flex items-center gap-4">
              <div class="w-12 h-12 flex justify-center items-center bg-[#22233f] rounded-full border-[0.800000011920929px] border-solid border-[#ebfdff]">
                <img class="w-[46.400001525878906px] h-[46.400001525878906px] object-cover">
              </div>
              <div class="h-[44px] w-[135.6125030517578px] flex flex-col">
                <span class="font-bold text-[20px] text-[#e4e3fe]">Alex Rivera</span>
                <span class="font-normal text-[12px] text-[#ac89ff]">Techno_Explorer</span>
              </div>
            </div>
          </div>
          <div class="h-[166px] w-[312px] flex flex-col gap-4 bg-[#7a7b8c] p-8 rounded-xl border-[0.800000011920929px] border-solid border-white">
            <div class="h-[98.4000015258789px] w-[92px] flex flex-col p-4">
              <span class="font-normal text-[60px] text-[#e4e3fe]">qr_code_2</span>
            </div>
            <span class="font-bold text-[10px] text-[#99f7ff]">Active Protocol</span>
            <div class="h-12 w-[246.40000915527344px] flex flex-col gap-1">
              <span class="font-bold text-[20px] text-[#e4e3fe]">Neural Nexus Hackathon</span>
              <span class="font-normal text-[12px] text-[#a9a9c3]">Confirmed • Sept 12-14</span>
            </div>
          </div>
        </div>
        <div class="h-[151.60000610351562px] w-[312px] flex flex-col justify-center items-center gap-8 bg-[#878893] px-8 py-4 rounded-xl border-[0.800000011920929px] border-solid border-white">
          <div class="h-[43px] w-[84.51250457763672px] flex flex-col items-center gap-1">
            <span class="font-normal text-[10px] text-center text-[#eeeeff]">Pass ID</span>
            <span class="font-bold text-[16px] text-center text-[#e4e3fe]">TV-0042-X9</span>
          </div>
          <div class="h-[43px] w-[103.2750015258789px] flex flex-col items-center gap-1">
            <span class="font-normal text-[10px] text-center text-[#a9a9c3]">Status</span>
            <div class="w-[103.2750015258789px] h-6 flex items-center gap-2">
              <div class="h-2 w-2 flex flex-col items-center bg-[#c6fbff] rounded-full"></div>
              <span class="font-bold text-[16px] text-center text-[#99f7ff]">ACTIVE_LINK</span>
            </div>
          </div>
        </div>
        <div class="h-[157px] w-[326px] flex flex-col items-center pt-8">
          <div class="w-[291.7375183105469px] h-[68px] flex items-center gap-3 bg-[#00f1fe] px-12 py-5 rounded-xl">
            <span class="font-normal text-[18px] text-center text-[#005f64]">GO TO DASHBOARD</span>
            <span class="font-normal text-[24px] text-center text-[#005f64]">arrow_forward</span>
          </div>
        </div>
        <div class="w-[312px] h-[76px] flex justify-center gap-4 pt-12">
          <span class="font-normal text-[20px] text-center text-[#99f7ff]">data_object</span>
          <span class="font-normal text-[20px] text-center text-[#ac89ff]">hub</span>
          <span class="font-normal text-[20px] text-center text-[#99f7ff]">memory</span>
          <span class="font-normal text-[20px] text-center text-[#ac89ff]">rocket_launch</span>
        </div>
      </div>
    </div>
  </div>
</div>


```

## OUTPUT:

![alt text](<Screenshot 2026-03-20 214109.png>) ![alt text](<Screenshot 2026-03-20 214053.png>) ![alt text](<Screenshot 2026-03-20 214102.png>) ![alt text](<Screenshot 2026-03-20 214023.png>) ![alt text](<Screenshot 2026-03-20 214010.png>)
## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
