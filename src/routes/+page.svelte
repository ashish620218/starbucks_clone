<script lang="ts">
  import Home1 from "$lib/components/Home1.svelte";
  import Home2 from "$lib/components/Home2.svelte";
  import Navbar from "$lib/components/Navbar.svelte";
  import Bottom1 from "$lib/Bottom1.svelte";
  import Bottom2 from "$lib/components/Bottom2.svelte";
  import Bottom3 from "$lib/components/Bottom3.svelte";

  let imgsrc1 = "images/moblicup.webp";
  let headingData1 = "New Year, New Yays";
  let textData1 =
    "Jump-start your year with a week full of offers in the Starbucks app.*";
  let buttontext1 = "Open the app";
  let bgColor1 = "bg-[#bbf2d1]";
  let ct1 = "mb-10 mt-20 mx-20 text-[#232020] flex flex-col gap-3";
  let ht1 = "text-5xl font-medium px-5 mx-5 mb-5";
  let pt1 = "text-2xl";
  let bt1 =
    "border rounded-3xl border-black px-5 py-1 font-serif font-semibold hover:bg-[#acf5c9]";

  let ct2 = "mb-10 mt-20 mx-20 text-[#f6f1f1] flex flex-col gap-3";
  let ht2 = "text-5xl font-medium px-5 mx-5 mb-5";
  let pt2 = "text-2xl";
  let bt2 =
    "border rounded-3xl text-[#f6f1f1] px-5 py-1 font-serif font-semibold hover:bg-[#304a6e]";

  let imgsrc2 = "images/cup.jpg";
  let headingData2 = "Pistachi-Yum";
  let textData2 =
    " Creamy, cozy vibes make the Pistachio Latte a must-have this season.";
  let buttontext2 = "Order Now";
  let bgColor2 = "bg-[#337481]";

  let imgsrc3 = "images/man.webp";
  let headingData3 = "This is our community. We’re in it together.";
  let textData3 =
    "Olivia, Starbucks Partner (Employee) Our partners uplift each other and their communities every day.";
  let buttontext3 = "Learn more";
  let bgColor3 = "bg-[#006241]";

  let ct3 = "mb-10 mt-20 mx-20 text-[#f6f1f1] flex flex-col gap-3";
  let ht3 = "text-2xl font-medium px-5 mx-5 mb-5";
  let pt3 = "text-xl";
  let bt3 =
    "border rounded-3xl text-[#f6f1f1] px-5 py-1 font-serif font-semibold hover:bg-[#338167]";

  let imgsrc4 = "images/bear.jpg";
  let headingData4 = "Hey there, hazelnut";
  let textData4 =
    "Say hello to our Hazelnut Oatmilk Shaken Espresso, a rich and layered pick-me-up.";
  let buttontext4 = "Order Now";
  let bgColor4 = "bg-[#efabfc]";

  let ct4 = "mb-10 mt-20 mx-20 text-[#232020] flex flex-col gap-3";
  let ht4 = "text-5xl font-medium px-5 mx-5 mb-5 leading-tight";
  let pt4 = "text-2xl";
  let bt4 =
    "border rounded-3xl border-black px-5 py-1 font-serif font-semibold hover:bg-[#a24a8c]";

  let imgsrc5 = "images/bread.jpg";
  let headingData5 = "Savory and satisfying";
  let textData5 =
    "Grab a subtly sweet Chicken, Maple Butter & Egg Sandwich on the way.";
  let buttontext5 = "Order Now";
  let bgColor5 = "bg-[#a5c4dc]";

  let ct5 = "mb-10 mt-20 mx-20 text-[#232020] flex flex-col gap-3";
  let ht5 = "text-5xl font-medium px-5 mx-5 mb-5 leading-tight";
  let pt5 = "text-2xl";
  let bt5 =
    "border rounded-3xl border-black px-5 py-1 font-serif font-semibold hover:bg-[#7e95ce]";

  let imgsrc6 = "images/venmo.jpg";
  let headingData6 = "Send Starbucks Cards in Venmo";
  let textData6 =
    "Send a little treat to someone you care about and brighten their day. You can now send Starbucks eGifts directly through Venmo.**";
  let buttontext6 = "View in Venmo";
  let bgColor6 = "bg-[#337481]";

  let ct6 = "mb-10 mt-20 mx-20 text-[#f6f1f1] flex flex-col gap-3";
  let ht6 = "text-2xl font-medium px-5 mx-5 mb-5";
  let pt6 = "text-xl";
  let bt6 =
    "border rounded-3xl text-[#f6f1f1] px-5 py-1 font-serif font-semibold hover:bg-[#338167]";

  let licon = "images/location_icon.svg";
  let logo = "images/foodlogo.png";

  let sicon = "images/spotifyicon.png";
  let ficon = "images/facbookicon.png";
  let picon = "images/pinterest-icon.png";
  let iicon = "images/instagramicon.svg";
  let yicon = "images/youtubeicon.jpg";
  let ticon = "images/twittericon.png";
</script>

<Navbar {licon} {logo} />
<hr />
<div class="pt-8">
  <Home2
    imgsrc={imgsrc1}
    headingData={headingData1}
    textData={textData1}
    buttonText={buttontext1}
    bgColor={bgColor1}
    ct={ct1}
    ht={ht1}
    pt={pt1}
    bt={bt1}
  />
</div>
<div class="pt-8">
  <Home1
    imgsrc={imgsrc2}
    headingData={headingData2}
    textData={textData2}
    buttonText={buttontext2}
    bgColor={bgColor2}
    ct={ct2}
    ht={ht2}
    bt={bt2}
    pt={pt2}
  />
</div>
<div class="pt-8">
  <Home2
    imgsrc={imgsrc3}
    headingData={headingData3}
    textData={textData3}
    buttonText={buttontext3}
    bgColor={bgColor3}
    ct={ct3}
    ht={ht3}
    bt={bt3}
    pt={pt3}
  />
</div>
<div class="pt-8">
  <Home1
    imgsrc={imgsrc4}
    headingData={headingData4}
    textData={textData4}
    buttonText={buttontext4}
    bgColor={bgColor4}
    ct={ct4}
    ht={ht4}
    bt={bt4}
    pt={pt4}
  />
</div>
<div class="pt-8">
  <Home2
    imgsrc={imgsrc5}
    headingData={headingData5}
    textData={textData5}
    buttonText={buttontext5}
    bgColor={bgColor5}
    ct={ct5}
    ht={ht5}
    bt={bt5}
    pt={pt5}
  />
</div>
<div class="pt-8">
  <Home1
    imgsrc={imgsrc6}
    headingData={headingData6}
    textData={textData6}
    buttonText={buttontext6}
    bgColor={bgColor6}
    ct={ct6}
    ht={ht6}
    bt={bt6}
    pt={pt6}
  />
</div>
<Bottom1></Bottom1>
<hr />
<Bottom2></Bottom2>
<hr />
<hr />
<Bottom3 {sicon} {ficon} {picon} {iicon} {yicon} {ticon} />
