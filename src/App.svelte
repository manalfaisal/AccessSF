<script>
  import { onMount } from 'svelte';
  import AOS from 'aos';
  import 'aos/dist/aos.css';

  import { fade, fly } from 'svelte/transition';
  let showContent = false;

  function scrollToZip() {
    const target = document.getElementById('zip94124');
    if (target) {
      target.scrollIntoView({ behavior: 'smooth' });
    }
  }

  onMount(() => {
    AOS.init({ duration: 1000, once: true });
  });

  
</script>


<main>
  {#if !showContent}
    <section class="hero-screen">
      <h1>EchoZIP: Voices Behind the Numbers</h1>
      <p>
        San Francisco is known for innovation and opportunity, but in neighborhoods like 94124 and 94110,
        those promises haven’t been equally delivered. EchoZIP blends real data with community voices
        to reveal how racial wealth inequality shows up block by block, and reimagines what equity
        could truly look like, ZIP code by ZIP code.
      </p>
      <button class="enter-btn" on:click={() => showContent = true}>Click to Explore</button>
    </section>
  {/if}

  <div id="main-content" class:show={showContent}>
    {#if showContent}
    <section class="step" data-aos="fade-up">
      <h2>Why This Matters</h2>
      <p>
        San Francisco is known for its innovation, diversity, and promise -
        but zoom in, and that promise isn’t evenly distributed. 
        In neighborhoods like Bayview–Hunters Point, historical disinvestment, 
        environmental harm, and limited access to resources have shaped daily 
        life for generations.
      </p>
      <p>
        Inequality isn’t just a national issue, it’s hyperlocal. Two families 
        living just miles apart can experience vastly different opportunities, 
        not because of merit or ambition, but because of where they live. ZIP codes 
        can determine access to healthy food, clean air, good schools, public transit, 
        generational wealth, and even life expectancy.
      </p>
      <p>
        Bayview–Hunters Point, in particular, has been both a symbol of Black cultural 
        strength and a site of systemic neglect. Redlining, toxic dumping, and a lack 
        of city investment have all contributed to health disparities, housing insecurity, 
        and economic barriers. Yet despite these challenges, the community has remained 
        resilient, organizing for environmental justice, education equity, and neighborhood 
        power.
      </p>
      <p>EchoZIP was created to connect the dots between policy, place, and people. 
        It blends hard data with lived experience, showing not only what the numbers say, 
        but what they mean. While this project highlights the Black community in Bayview, 
        it’s part of a broader reflection on how cities serve, or fail, the people who 
        built them.
      </p>
      <p><b>What does equity look like where you live?</b></p>
      <p><i>ZIP code by ZIP code.</i></p>
      <p><i>Story by story</i></p>

      <p><b>Because where you live shouldn't determine what you’re worth.</b></p>
    </section>

      <section id="zip94124" class="step" data-aos="zoom-in">
        <h2>San Francisco County (CA)</h2>
        <p> With a <strong>Black population of just 5.1%</strong>, San Francisco continues to see the 
          long-term effects of displacement and systemic inequality.
          According to 2023 estimates, only <strong>2.7% of housing units</strong> in the city are 
          Black owner-occupied, a stark reminder of the city’s deep housing inequities and barriers 
          to generational wealth.<br /><br />
          The city also has a <strong>Social Vulnerability Index (SVI) score of 0.482</strong>. The 
          SVI is a measure of how vulnerable a community is to health, environmental, and economic shocks. 
          A higher score means a community is less equipped to recover from disasters or systemic 
          disruptions — which compounds risk in under-resourced areas.<br /><br />
          These disparities are especially concentrated in neighborhoods like Bayview–Hunters Point, 
          where the legacy of redlining, industrial pollution, and lack of investment have historically 
          undermined stability and access.
        </p>
        <p><i>Source: BWDC Website- <a href="https://www.census.gov/programs-surveys/acs/data.html">Social Vulnerability Index (2022), US Census American Community Survey</a> </i></p>

        <p> From 2007 to 2022, the median net worth of Black households in the U.S. increased from 
          just over $30,000 to $44,100. On the surface, that might seem like progress, but in reality, 
          it underscores a deeper issue. Over the same period, White household wealth surged past 
          $284,000, making the racial wealth gap not just persistent, but staggering. What this means 
          for neighborhoods like Bayview–Hunters Point is clear: even as the economy grows, Black 
          families are consistently locked out of wealth-building opportunities that create long-term 
          security, like homeownership, savings, and investment. When entire communities are held at 
          the margins of prosperity, we can’t call that an accident, it’s the result of policy, planning, 
          and decades of systemic exclusion. Data like this reminds us: the gap isn't just about dollars. 
          It's about dignity, stability, and the right to thrive. </p> <p><i>Source: Black Wealth Data 
          Center, based on US Federal Reserve, Survey of Consumer Finances (2007–2022)</i></p>

   
        <section class="step" data-aos="zoom-out">
          <h2>ZIP Code: 94124 — Bayview-Hunters Point</h2>
          <p>
            Bayview–Hunters Point has a long legacy of working-class strength and systemic neglect. Originally marshlands and a hub for Chinese shrimp fishing, the area became a shipbuilding center during WWII, drawing in African American workers who were denied housing elsewhere in San Francisco.
          </p>
          <p>
            After the war, many Black families remained, yet promises of opportunity gave way to redlining, industrial pollution, and underinvestment. The neighborhood’s isolation was reinforced by planning decisions that cut it off from the rest of the city.
          </p>
          <p>
            Despite these challenges, Bayview remains a cultural anchor and home to generations of resistance, resilience, and organizing for environmental justice, housing rights, and community power.
          </p>
          <p><b>Black Population Percentage:</b> 26.4%</p>
          <p><b>Median Income:</b> $82,928</p>
          <p><b>Black Median Income:</b> $46,265</p>

          <p><em>Source: Black Wealth Data Center - <a href= "https://www.census.gov/programs-surveys/acs/data.html">US Census American Community Survey</a></em></p>
        </section>


        <h3>Why Bayview–Hunters Point Matters</h3>
          <ul>
            <li>Bayview–Hunters Point is home to one of San Francisco’s largest Black communities, making it a key site for understanding local racial equity.</li>
            <li>Decades of disinvestment have resulted in underfunded schools, aging infrastructure, and limited access to generational wealth-building opportunities.</li>
            <li>Despite these barriers, Bayview is a hub of community resilience — where grassroots organizing, cultural pride, and calls for justice continue to shape its future.</li>
          </ul>

      </section>


      <section class="step" data-aos="fade-up">
        <h2>Life in ZIP 94124: A Closer Look</h2>
        <p>
          Meet Maya, a 34-year-old Bayview native and single mother of two. She works 
          full-time in logistics, lives in a rented apartment two blocks from her childhood 
          home, and spends nearly half her income on housing. Despite holding an associate 
          degree, she’s still priced out of homeownership.
        </p>
        <p>
          Maya’s story reflects the economic tightrope many Black families in 94124 walk daily. 
          Limited access to affordable credit, rising rents, and a lack of generational wealth 
          make it difficult to build financial security, even with full-time employment.
        </p>
        <p>
          These aren't isolated struggles. They're structural outcomes, shaped by decades of 
          policy decisions that disinvested in communities like hers.
        </p>
        <p><em>This is what the data doesn't always show, but EchoZIP does.</em></p>
      </section>


      <section class="step" data-aos="fade-left">
        <h2>What If These Programs Were in Place?</h2>
        <p>Hover over each card to see how targeted investments could impact Black homeownership in neighborhoods like ZIP 94124.</p>
          <div class="card-grid">
          <!-- Card 1 -->
          <div class="flip-card">
            <div class="flip-card-inner">
              <div class="flip-card-front bg1"><br /><strong>Tech Internships</strong></div>
              <div class="flip-card-back">Exposure to tech careers can raise long-term income by 40%. In 94124, access could raise Black homeownership by 3%.</div>
            </div>
          </div>

          <!-- Card 2 -->
          <div class="flip-card">
            <div class="flip-card-inner">
              <div class="flip-card-front bg2"><br /><strong>Homebuyer Grants</strong></div>
              <div class="flip-card-back">Programs like down-payment assistance reduce barriers to ownership. In SF, this could add 5% to Black homeownership rates.</div>
            </div>
          </div>

          <!-- Card 3 -->
          <div class="flip-card">
            <div class="flip-card-inner">
              <div class="flip-card-front bg3"><br /><strong>Community WiFi</strong></div>
              <div class="flip-card-back">Broadband gaps fuel the digital divide. Zip codes with free WiFi access report higher tech job readiness.</div>
            </div>
          </div>

          <!-- Card 4 -->
          <div class="flip-card">
            <div class="flip-card-inner">
              <div class="flip-card-front bg4"><br /><strong>Financial Literacy</strong></div>
              <div class="flip-card-back">Wealth-building knowledge builds generational stability. Teaching credit, savings, and investment early helps shift long-term trends.</div>
            </div>
          </div>

          <!-- Card 5 -->
          <div class="flip-card">
            <div class="flip-card-inner">
              <div class="flip-card-front bg5"><br /><strong>Rent-to-Own Housing</strong></div>
              <div class="flip-card-back">Transitional programs create pathways to ownership. Especially powerful in areas with historically low Black homeownership.</div>
            </div>
          </div>

          <!-- Card 6 -->
          <div class="flip-card">
            <div class="flip-card-inner">
              <div class="flip-card-front bg6"><br /><strong>Mentorship Access</strong></div>
              <div class="flip-card-back">Career and financial mentors increase opportunity confidence. Peer and community-based mentorship boosts retention in tech.</div>
            </div>
          </div>
      </section>

      <section class="step" data-aos="zoom-in">
        <h2>Add Your Voice</h2>
        <p>What’s your ZIP? What’s your dream? What should access look like where you live?</p>
        <p><a href="https://docs.google.com/forms/d/e/1FAIpQLSeb4Kx4A42ia0H5EpMTcFrysNK-p0DFDUWla3dv3I5PEo7xDg/viewform?usp=sharing&ouid=114090336160358375058" target="_blank">Click here to share your story anonymously →</a></p>
        <p>EchoZIP turns numbers into narratives, and narratives into action.</p>
      </section>
      
    {/if}
  </div>


</main>
