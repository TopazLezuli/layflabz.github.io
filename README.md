# layflabz.github.io
owo
<!DOCTYPE html>
<html>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Amatic+SC">
<style>
body, html {height: 100%}
body,h1,h2,h3,h4,h5,h6 {font-family: "Amatic SC", sans-serif}
.menu {display: none}
.bgimg {
  background-repeat: no-repeat;
  background-size: cover;
  background-image: url("https://wallpapercave.com/wp/B32Tpse.jpg");
  min-height: 90%;
}
</style>
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top w3-hide-small">
  <div class="w3-bar w3-xlarge w3-black w3-opacity w3-hover-opacity-off" id="myNavbar">
    <a href="#" class="w3-bar-item w3-button">HOME</a>
    <a href="#menu" class="w3-bar-item w3-button">INSIDE</a>
    <a href="#about" class="w3-bar-item w3-button">ABOUT</a>
    <a href="#myMap" class="w3-bar-item w3-button">
   </a>
  </div>
</div>
  
<!-- Header with image -->
<header class="bgimg w3-display-container w3-grayscale-min" id="home">
  <div class="w3-display-bottomleft w3-padding">
    <span class="w3-tag w3-xlarge"></span>
  </div>
  <div class="w3-display-middle w3-center">
    <span class="w3-text-white w3-hide-small" style="font-size:100px">Fire Hazard</span>
    <span class="w3-text-white w3-hide-large w3-hide-medium" style="font-size:60px"><b>Fire</b></span>
    <p><a href="#menu" class="w3-button w3-xxlarge w3-black">GROUP 5 ~ KAJINATICS</a></p>
  </div>
</header>

<!-- Menu Container -->
<div class="w3-container w3-black w3-padding-64 w3-xxlarge" id="menu">
  <div class="w3-content">
  
    <h1 class="w3-center w3-jumbo" style="margin-bottom:64px">＼(＾▽＾)／	</h1>
    <div class="w3-row w3-center w3-border w3-border-dark-grey">
      <a href="javascript:void(0)" onclick="openMenu(event, 'Pizza');" id="myLink">
        <div class="w3-col s4 tablink w3-padding-large w3-hover-red">Introduction</div>
      </a>
      <a href="javascript:void(0)" onclick="openMenu(event, 'Pasta');">
        <div class="w3-col s4 tablink w3-padding-large w3-hover-red">Mitigation</div>
      </a>
      <a href="javascript:void(0)" onclick="openMenu(event, 'Starter');">
        <div class="w3-col s4 tablink w3-padding-large w3-hover-red">Preparation</div>
      </a>
    </div>

    <div id="Pizza" class="w3-container menu w3-padding-32 w3-white">
      <h1><b>What is Fire Hazard?</b></h1>
      <p class="w3-text-grey">Fire hazard is the most common hazard in every community. Fire hazard can result to many bad impacts on the community. Cause of fire are combustile materials.
In pasay city, people's residence are close to another. Most people do not check their cables if it's been frayed and the kitchen that they left the stove open.
That's why we plan to have a DRP to inform the people on what they should and not what they should not do to prevent fire.
We would hand them free emergency kit and tell them what the emergency kit should be filled with such as clothes, non-prescription medicine, and etc.</p>
      <hr>
   
      <h1><b></b> <span class="w3-right w3-tag w3-dark-grey w3-round"></span></h1>
      <p class="w3-text-grey"></p>
      <hr>
      
      <h1><b></b> <span class="w3-right w3-tag w3-dark-grey w3-round"></span></h1>
      <p class="w3-text-grey"></p>
      <hr>

      <h1><b></b> <span class="w3-right w3-tag w3-dark-grey w3-round"></span></h1>
      <p class="w3-text-grey"></p>
      <hr>

      <h1><b></b> <span class="w3-tag w3-red w3-round"></span><span class="w3-right w3-tag w3-dark-grey w3-round"></span></h1>
      <p class="w3-text-grey"></p>
      <hr>

      <h1><b></b> <span class="w3-tag w3-grey w3-round"></span><span class="w3-right w3-tag w3-dark-grey w3-round"></span></h1>
      <p class="w3-text-grey"></p>
    </div>

    <div id="Pasta" class="w3-container menu w3-padding-32 w3-white">
      <h1><b></b>( ´ ▽ ` )/ M I T I G A T I O N \( ´ ▽ ` ) <span class="w3-tag w3-grey w3-round"><span class="w3-right w3-tag w3-dark-grey w3-round"></h1>
      <p class="w3-text-grey">Planning ahead of time is important because fire is likely to happen out of the blue and some people dont know on what to do if they see one. Accroding to the government, if we want to prevent fire from happening, we should stay vigilant and be cautious.
According to NDRRMC, the plan is to make the building more firmly.
 According to (Article???), the DREF's goal is to support the people affected by the fire. They plan to distribute relief items to the people.
Additional plan: The plan is to place the valuable things in a safe place in case of fire.
</p>
      <hr>
   
      <h1><b></b> <span class="w3-right w3-tag w3-dark-grey w3-round"></span></h1>
      <p class="w3-text-grey"></p>
      <hr>
      
      <h1><b></b> <span class="w3-right w3-tag w3-dark-grey w3-round"></span></h1>
      <p class="w3-text-grey"></p>
      <hr>

      <h1><b></b> <span class="w3-right w3-tag w3-dark-grey w3-round">＼(＾ω＾)／</span></h1>
      <p class="w3-text-grey"></p>
    </div>


    <div id="Starter" class="w3-container menu w3-padding-32 w3-white">
      <h1><b>~P R E P A R A T I O N~</b> <span class="w3-tag w3-grey w3-round"></span><span class="w3-right w3-tag w3-dark-grey w3-round"></span></h1>
      <p class="w3-text-grey"> A. Supplies and equipment
     It's important to have food supplies and medical supplies that can help to sustain us and survive longer during a disaster.
  1. Foods: Canned fruits and vegetables, canned soups, water bottles and biscuits.
  2.First aid kit: (Copy on what's stated)
  3.Non-prescription medicine: ("")
 B. Communications
  •Walkie talkie
  •Whistle
  •White cloth
 C. Personal supplies
Personal supplies must be filled with extra clothes, napkins(for female) non-perishable healty snacks, water, flashlight, and extra battery
  D. Emergency hotlines
  •National Emergency Hotline: 911
  •Bureau of Fire Protection: (02) 426-3812
  •Philippine Red Cross: 143 or (02) 527-8385 to 95
 E. Evacuation Plan
 According to queensu, leave the building immediately and notify other people by pulling the fire alarm. Always use the stairs. Also, do not panic when seeing fire. Try to calm yourself first. After leaving, report this to the fire department and leave it to them to take care of the situation. In case of fire at home, you should leave the house immediately and inform people that there is a fire by either using a whistle or scream "fire".
 F. Mandatory evacuation plan
Whan fire occurred, leave the building immediately and disregard your valuable items. Prioritize only on your safety.
 G. Informing the public about the evacuation plan
According to fema.gov, most people relied on social media for help but the most effective is sharing your plan personally so they can contact you
</p>
      <hr>
   
      <h1><b>R E S P O N S E</b> <span class="w3-right w3-tag w3-dark-grey w3-round"></span></h1>
      <p class="w3-text-grey">
  A. Responders
Responders are the fire fighters, EMT, and paramedics because they are experienced and professional
  B. Damage assessment
Construction workers and engineers are responsible for repairing the damaged property. The property's owner will be paying the construction workers and the engineer the payment.
  C. Basic necessities for evacuation
Mayor's role is to check on the victims' safety and the area that can harmful to people nearby, and submit a report to the news reporter. City council is the one to provide the victims with relief goods and assist them. PRC helps the victims in healing the victims' injuries and give shelter and medicines to them.</p>
      <hr>
      
      <h1><b>R E C O V E R Y</b> <span class="w3-right w3-tag w3-dark-grey w3-round"></span></h1>
      <p class="w3-text-grey">Red Cross' main mission is to help the people after the disaster by providing them their needs.</p>
      <hr>
      
      <h1><b></b> <span class="w3-right w3-tag w3-dark-grey w3-round"></span></h1>
      <p class="w3-text-grey"></p>
    </div><br>

  </div>
</div>

<!-- About Container -->
<div class="w3-container w3-padding-64 w3-red w3-grayscale w3-xlarge" id="about">
  <div class="w3-content">
    <h1 class="w3-center w3-jumbo" style="margin-bottom:64px">Reference</h1>
    <p>
Bueza, Michael. (December 6,2014). The role of LGUs, local councils during disasters
Retrieved February,6 2020 from: vappler.com

Here is how to build your own emergency kit. (July 13, 2018).
Retrieved February 6,2020 from: ranper.com

Alkot,Dawn.(n.d.). 10 items to have in your bag.
Retrieved  from: lotsahelpinghomed.com

Emergency Assistance. (.n.d)
Retrieved February 6,2020 from :ph. Uneassy.gov
</p>
    <p><strong></strong>
    <p></p>
   
    <h1><b>~ ~ G R O U P M E M B E R S ~ ~
    
    <div class="w3-row">
      <div class="w3-col s6">
        <p>Facilitator : Kristine Andrei Micaroz</p>
        <p>Reasearcher : Henrix Marcelo Papa<p>
          
        </p>Cloud Adrian Castillo</p>
        <p> Scribe     :Deeralynn Ofalla
         
         </p>Max Albino</p>
         Spokesperson : Sofia Rein Ballon
      </div>
      <div class="w3-col s6">
        <p> </p>
        <p> </p>
        <p> </p>
      </div>
    </div>
    
  </div>
</div>

<!-- Image of location/map -->
<img src="/w3images/map.jpg" class="w3-image w3-greyscale" style="width:100%;" id="myMap">



<!-- Footer -->
<footer class="w3-center w3-black w3-padding-48 w3-xxlarge">
  <p><a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-text-green">w3.css</a></p>
</footer>


<script>
// Tabbed Menu
function openMenu(evt, menuName) {
  var
  x = document.getElementsByClassName("menu");
  for (i = 0; i < x.length; i++) {
     x[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < x.length; i++) {
     tablinks[i].className = tablinks[i].className.replace(" w3-red", "");
  }
  document.getElementById(menuName).style.display = "block";
  evt.currentTarget.firstElementChild.className += " w3-red";
}
document.getElementById("myLink").click();
</script>

</body>
</html>
