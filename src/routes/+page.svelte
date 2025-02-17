<script>
    import Nav from "../components/Nav.svelte";
    import Front from "../components/Front.svelte";
</script>

<title>Ping Pong</title>
<main class="pt-[6rem]">
    <div class="main mt-0 pl-0">
     <Nav />

     <!-- news alert -->
     <div class="bg-indigo-50 py-2 h-24 mt-0 mb-0 pb-0 pl-[70px]  ">
      <div class="container mx-auto px-4 mr-8px">
        <div class="flex items-center space-x-3">
          <span class="bg-indigo-600 text-white text-sm font-semibold px-3 py-1 ml-8 mt-2 ">News</span>
          <p class="text-indigo-700 font-semibold">PingPong is joining Hotjar</p>
        </div>
        <p class="text-indigo-600 text-sm mt-1 ml-18">
          We are happy to announce that PingPong has been acquired by Hotjar.
        </p>
      </div>
    </div>
    
     <Front />

     <!-- company logos -->
     <section class="bg-white py-8  pt-1">
        <div class="container mx-auto px-6 lg:px-12">
          <div class=" pt-0 pb-8 flex flex-wrap justify-center items-center gap-20 ">
            <img src="/hotjar.svg" alt="Hotjar" class="h-12 opacity-80 pt-0"  />
            <img src="/mccompany.svg" alt="McKinsey & Company" class="h-12 pt-0 " />
            <img src="/nestle.svg" alt="Nestlé" class="h-12 pt-0" />
            <img src="/skyscanner.svg" alt="Skyscanner" class="h-12 pt-0 " />
            <img src="/wise.svg" alt="Wise" class="h-12 pt-0 " />
            <img src="/zapier.svg" alt="Zapier" class="h-12 pt-0" />
            <img src="/dropbox.svg" alt="Dropbox" class="h-12 pt-0" />
          </div>
          <div class="border-b border-gray-200 mt-4"></div>
        </div>
      </section >
      
      <!-- feedback -->
      <section class="bg-white py-16">
        <div class="container px-6 text-start w-100 ml-20 text-2xl">
          <h2 class="text-3xl font-bold text-gray-900  leading-tight ml-20 w-80 font-sans">
            Get feedback that makes a difference
          </h2>
          <p class="text-lg text-gray-600 mt-4 ml-20 w-140 text-start ">
            PingPong takes care of all your remote UX research needs in one place, so
            you can focus on what matters most: building products users will love.
          </p></div>

          <!-- feedback box -->
       <!-- Box Layout -->
  <div class="flex space-x-10 w-full pt-10 pl-10 justify-center">
    <!-- Box 1 -->
    <div class="w-90 h-80 p-6 rounded-lg shadow-md bg-[#EFEFFC] flex flex-col items-center text-center">
      <div class="w-16 h-16 bg-white rounded-xl flex items-center justify-center mb-4 pl-0">
        <img src="feedback1.svg" alt="User Connect Icon" class="w-10 h-10" />
      </div>
      <h3 class="font-semibold text-lg text-gray-900">Connect to users from your audience</h3>
      <p class="text-gray-600 mt-2">
        Find your target users wherever they are and whatever they do and see your product through their eyes.
      </p>
    </div>

    <!-- Box 2 -->
    <div class="w-90 h-80 p-6 rounded-lg shadow-md bg-[#EDFEF6] flex flex-col items-center text-center">
      <div class="w-16 h-16 bg-white rounded-xl flex items-center justify-center mb-4">
        <img src="/feedback2.svg" alt="Team Research Icon" class="w-10 h-10" />
      </div>
      <h3 class="font-semibold text-lg text-gray-900">Make research a team effort – and benefit</h3>
      <p class="text-gray-600 mt-2">
        Invite others to take part in research sessions so they can hear firsthand what users need, want and feel.
      </p>
    </div>

    <!-- Box 3 -->
    <div class="w-90 h-80 p-6 rounded-lg shadow-md bg-[#FEF9E5] flex flex-col items-center text-center">
      <div class="w-16 h-16 bg-white rounded-xl flex items-center justify-center mb-4 ">
        <img src="/feedback3.svg" alt="Workflow Icon" class="w-10 h-10 " />
      </div>
      <h3 class="font-semibold text-lg text-gray-900">Use one platform for the entire research workflow</h3>
      <p class="text-gray-600 mt-2">
        No need for plugins, workarounds, or even a new tab. Automate and manage the research process through a single interface.
      </p>
    </div>
  </div>
</section>





<section class="py-16 bg-white">
  <div class="max-w-6xl mx-auto px-6 grid md:grid-cols-2 gap-10 items-center">
    <!-- Left Content -->
    <div>
      <p class="text-indigo-600 font-medium tracking-widest uppercase">Recruit</p>
      <h2 class="text-4xl font-bold text-gray-900 leading-tight mt-2">
        Reach testers in minutes
      </h2>
      <p class="text-lg text-gray-600 mt-4">
        From consumers to working professionals, get access to more than
        175,000 testers from all over the world.
      </p>
      <a href="#" class="mt-6 inline-block px-6 py-3 text-[#6161E5] font-medium bg-indigo-100 ">
        Learn more
      </a>
    </div>

    <!-- Right Image -->
    <div class="mr-0 ">
      <img src="/form.png" alt="Reach Testers in Minutes" class="max-w-full h-auto">
    </div>
  </div>
</section>







   <!-- call -->
   <section class="py-16 bg-gray-50">
    <div class="max-w-6xl mx-auto px-6 grid lg:grid-cols-2 gap-0 items-center">
      
      <!-- Left Image -->
      <div class="flex justify-center w-100 ml-2 pt-0  ">
        <img src="/girl.png" alt="Video Call Preview" class="max-w-full h-auto mt-0 ">
      </div>
  
      <!-- Right Content -->
      <div>
        <p class="text-indigo-600 font-sans font-medium tracking-widest uppercase">Call</p>
        <h2 class="text-4xl font-bold font-sans text-gray-900 leading-tight mt-2">
          Get onto a video call in a few taps
        </h2>
        <p class="text-lg text-gray-600 mt-4 font-sans">
          Connect with users without ever leaving PingPong using our built-in video call tool – just log in when your interview begins.
        </p>
        <a href="#" class="mt-6 inline-block px-6 py-3 text-[#6161E5] font-medium bg-indigo-100 ">
          Learn more
        </a>
      </div>
  
    </div>
  </section>
  



<!-- NOTES -->
  <section class="py-16 bg-gray-50">
    <div class="max-w-6xl mx-auto px-6 grid md:grid-cols-2 gap-0 items-center">
      
      <!-- Left Content -->
      <div>
        <p class="text-indigo-600 font-medium tracking-widest uppercase">Understand</p>
        <h2 class="text-4xl font-extrabold text-gray-900 leading-tight mt-2">
          Turn insights into shared knowledge
        </h2>
        <p class="text-lg text-gray-600 mt-4">
          Share session recordings, highlights, and notes with ease so everyone in your team or business can reap the rewards.
        </p>
        <a href="#" class="mt-6 inline-block px-6 py-3 text-indigo-600 font-medium bg-indigo-100">
          Learn more
        </a>
      </div>
  
      <!-- Right Image -->
      <div class="flex justify-center h-92">
        <img src="/note.png" alt="Notes Preview" class="max-w-full h-auto">
      </div>
  
    </div>
  </section>
  
    


  <!-- review -->
  <section class="py-0 bg-white flex justify-center mt-0">
    <div class="max-w-5xl flex items-center space-x-6 px-6 mt-0">
      
      <!-- Left Arrow Image -->
      <div class="hidden md:block mt-0">
        <img src="arrow.svg" alt="Decorative Arrow" class=" mt-0">
      </div>
  
      <!--  Content -->
      <div class="text-center  w-128">
        <p class="text-2xl nuinto-sans italic text-gray-900 mb-0 mt-0">
          PingPong allowed us to make user testing a habit and a truly fun thing to do by taking care of the painful parts. PingPong repeatedly connected me with people with just the right background, allowing us to focus solely on testing."
        </p>
        <p class="mt-4 nuinto-sans text-gray-500 text-lg">— Péter Gyöngyösi, One Identity</p>
      </div>
    </div>
  </section>


        <!-- latest from ping pong -->
        <section class="max-w-6xl mx-auto px-6 py-12">
          <!-- Section Title -->
          <h2 class="text-3xl font-sans font-bold text-left mb-8">The latest from PingPong</h2>
        
          <!-- Blog Grid -->
          <div class="grid grid-cols-3 gap-8 ">
            
            <!-- Blog Card 1 -->
            <div class="bg-white  overflow-hidden ">
              <img src="/aquire.png" alt="Hotjar has acquired PingPong" class="w-fit h-55 object-cover" />
              <div class="p-5">
                <div class="flex items-center  text-gray-500 text-sm mb-3">
                  <img src="/solt.png" alt="Zsolt" class="w-6 h-6 rounded-full mr-2" />
                  <span>Zsolt</span>
                  <span class="ml-auto">November 16, 2022</span>
                </div>
                <h3 class="text-lg font-bold ">Hotjar has acquired PingPong</h3>
                <p class="text-gray-600 mt-2">The day has come, and I have some fantastic news to share. I'm happy to announce a huge milestone for PingPong: we’re joining Hotjar!</p>
                <a href="#" class="text-blue-500 font-medium mt-3 inline-flex items-center">
                  Read more <span class="ml-1">→</span>
                </a>
              </div>
            </div>
        
            <!-- Blog Card 2 -->
            <div class="bg-white  overflow-hidden  ">
              <img src="/man.jpg" alt="UX Research Conferences in 2022" class="w-full h-55 object-cover" />
              <div class="p-5">
                <div class="flex items-center text-gray-500 text-sm mb-3">
                  <img src="/thomas.png" alt="Thomas" class="w-6 h-6 rounded-full mr-2" />
                  <span>Thomas</span>
                  <span class="ml-auto">January 17, 2022</span>
                </div>
                <h3 class="text-lg font-bold">UX Research Conferences in 2022</h3>
                <p class="text-gray-600 mt-2">It's a new year, with a new and updated list of conferences! Keep up with changes and developments in the industry. As you start to build your roadmap for the year, we've put together a list of UXR conferences that'll help keep you at the top of your game.</p>
                <a href="#" class="text-blue-500 font-medium mt-3 inline-flex items-center">
                  Read more <span class="ml-1">→</span>
                </a>
              </div>
            </div>
        
            <!-- Blog Card 3 -->
            <div class="bg-white overflow-hidden ">
              <img src="/2022.jpg" alt="Looking back on 2021" class="w-full h-55 object-cover" />
              <div class="p-5">
                <div class="flex items-center text-gray-500 text-sm mb-3">
                  <img src="/zsolt.png" alt="Zsolt" class="w-6 h-6 rounded-full mr-2" />
                  <span>Zsolt</span>
                  <span class="ml-auto">January 7, 2022</span>
                </div>
                <h3 class="text-lg font-bold">Looking back on 2021</h3>
                <p class="text-gray-600 mt-2">Another year has passed, so it’s time to reflect on how things are going at PingPong.</p>
                <a href="#" class="text-blue-500 font-medium mb-0  inline-flex items-center">
                  Read more <span class="ml-1">→</span>
                </a>
              </div>
            </div>
        
          </div>
        </section>
        <div class="border-b border-gray-200 mt-4"></div>
        





        <footer class="bg-white py-10 border-t">
          <div class="max-w-6xl mx-auto px-6 grid grid-cols-1 md:grid-cols-4 gap-8">
            
            <!-- Product Links -->
            <div>
              <h4 class="font-bold text-gray-900 mb-3">PRODUCT</h4>
              <ul class="space-y-2 text-gray-600">
                <li><a href="#" class="hover:text-gray-900">Overview</a></li>
                <li><a href="#" class="hover:text-gray-900">Pricing</a></li>
                <li><a href="#" class="hover:text-gray-900">Recruit</a></li>
                <li><a href="#" class="hover:text-gray-900">Call</a></li>
                <li><a href="#" class="hover:text-gray-900">Understand</a></li>
              </ul>
            </div>
        
            <!-- Company Links -->
            <div>
              <h4 class="font-bold text-gray-900 mb-3">COMPANY</h4>
              <ul class="space-y-2 text-gray-600">
                <li><a href="#" class="hover:text-gray-900">About</a></li>
                <li><a href="#" class="hover:text-gray-900">Customers</a></li>
                <li><a href="#" class="hover:text-gray-900">Security</a></li>
                <li><a href="#" class="hover:text-gray-900">Legal</a></li>
                <li><a href="#" class="hover:text-gray-900">Contact</a></li>
              </ul>
            </div>
        
            <!-- Resources Links -->
            <div>
              <h4 class="font-bold text-gray-900 mb-3">RESOURCES</h4>
              <ul class="space-y-2 text-gray-600">
                <li><a href="#" class="hover:text-gray-900">Blog</a></li>
                <li><a href="#" class="hover:text-gray-900">Learn</a></li>
                <li><a href="#" class="hover:text-gray-900">Help center</a></li>
                <li><a href="#" class="hover:text-gray-900">NDA for UX Research</a></li>
                <li><a href="#" class="hover:text-gray-900">Changelog</a></li>
              </ul>
            </div>
        
            <!-- Become a Tester CTA -->
            <div class="border border-gray-200 p-6 h-50 w-70 ml-0 mr-[30px] ">
              <h4 class="font-bold text-2xl text-center text-gray-900 mb-2 mr-2">Become a tester and earn money</h4>
              <a href="#" class="text-blue-400 bg-blue-100 px-4 py-2 text font-medium inline-block mt-2 ml-10 text-center items-center hover:bg-blue-200">Get paid to test</a>
            </div>
        
          </div>
        
          <!-- Footer Bottom -->
          <div class="max-w-6xl mx-auto px-6 mt-10 flex flex-col md:flex-row items-center justify-between text-gray-500 text-sm">
            <p>Copyright © Hotjar Ltd</p>
            <div class="flex items-center space-x-4 mt-4 md:mt-0">
              <span class="flex items-center">
                <span class="w-3 h-3 bg-green-500 rounded-full mr-2"></span> Status
              </span>
              <!-- X -->
<span class="[&>svg]:h-5 [&>svg]:w-5">
  <svg
    xmlns="http://www.w3.org/2000/svg"
    fill="currentColor"
    viewBox="0 0 512 512">
    <path
      d="M389.2 48h70.6L305.6 224.2 487 464H345L233.7 318.6 106.5 464H35.8L200.7 275.5 26.8 48H172.4L272.9 180.9 389.2 48zM364.4 421.8h39.1L151.1 88h-42L364.4 421.8z" />
  </svg>
</span>

<!-- linkdin -->
              <span class="[&>svg]:h-5 [&>svg]:w-5">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  fill="currentColor"
                  viewBox="0 0 448 512">
                  <path
                    d="M100.3 448H7.4V148.9h92.9zM53.8 108.1C24.1 108.1 0 83.5 0 53.8a53.8 53.8 0 0 1 107.6 0c0 29.7-24.1 54.3-53.8 54.3zM447.9 448h-92.7V302.4c0-34.7-.7-79.2-48.3-79.2-48.3 0-55.7 37.7-55.7 76.7V448h-92.8V148.9h89.1v40.8h1.3c12.4-23.5 42.7-48.3 87.9-48.3 94 0 111.3 61.9 111.3 142.3V448z" />
                </svg>
            </div>
          </div>
        </footer>
        
</div>    
</main>