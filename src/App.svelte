<script>
  import LeftAlignedExample from "./sections/LeftAlignedExample.svelte";
  import RightAlignedExample from "./sections/RightAlignedExample.svelte";
  import ImageExample from "./sections/ImageExample.svelte";
  import TitleSection from "./sections/TitleSection.svelte";
  import InteresectionObserverBasicExample from "./sections/InteresectionObserverBasicExample.svelte";
  import IntersectionObserverAlertExample from "./sections/IntersectionObserverAlertExample.svelte";
  import DisappearingDuckExample from "./sections/DisappearingDuckExample.svelte";
  import IntersectionObserverSectionCard from "./sections/IntersectionObserverSectionCard.svelte";
  import IntersectionObserverListExample from "./sections/IntersectionObserverListExample.svelte";
</script>

<main>
  <section class="step">
    <h1>EchoZIP: Voices Behind the Numbers</h1>
    <p>
      San Francisco is known for innovation and opportunity, but in neighborhoods like 94124 and 94110, 
      those promises haven’t been equally delivered. EchoZIP blends real data with community voices to 
      reveal how racial wealth inequality shows up block by block, and reimagines what equity could 
      truly look like, ZIP code by ZIP code.
    </p>
  </section>

  <section class="step">
    <h2>📍 ZIP Code: 94124 — Bayview-Hunters Point</h2>
    <p><strong>Black Homeownership Rate:</strong> 22%</p>
    <p><strong>Median Income (Black Households):</strong> $38,000</p>
    <blockquote>
      “We used to own our home. Now we rent two blocks down and it’s double the price.”
    </blockquote>
    <img src="/images/94124-chart.png" alt="Chart for ZIP 94124">
  </section>

  <section class="step">
    <h2>📍 ZIP Code: 94110 — Mission District</h2>
    <p><strong>Black Population (2020):</strong> ~2.5%</p>
    <p><strong>Tech Jobs Held by Black Workers:</strong> 1.7%</p>
    <blockquote>
      “I thought being born here meant I’d stay here. But I can’t find work in my own city.”
    </blockquote>
    <img src="/images/94110-graph.png" alt="Graph for ZIP 94110" />
  </section>
  
  <section class="step">
  <h2>🔍 Snapshot: ZIP 94124 vs National Average</h2>
  <table class="data-grid">
    <thead>
      <tr>
        <th>Metric</th>
        <th>94124</th>
        <th>USA (Black households)</th>
      </tr>
    </thead>
    <tbody>
      <tr><td>Black Homeownership</td><td>22%</td><td>42%</td></tr>
      <tr><td>Black Population in SF</td><td>–</td><td>5.5%</td></tr>
      <tr><td>Black Median Income (94124)</td><td>$38K</td><td>–</td></tr>
    </tbody>
  </table>

  <p><em>These numbers show how localized disparities amplify structural inequality.</em></p>
</section>


<section class="step">
  <h2>📊 What If These Programs Were in Place?</h2>
  <div class="card-grid">
    <!-- Six flip-card entries as before -->
  </div>
</section>

  <section class="step">
    <h2>📊 What If These Programs Were in Place?</h2>
    <p>Hover over each card to see how targeted investments could impact Black homeownership in neighborhoods like ZIP 94124.</p>

    <div class="card-grid">
  <!-- Card 1: Tech Internships -->
  <div class="flip-card">
    <div class="flip-card-inner">
      <div class="flip-card-front">
        💻<br />
        <strong>Tech Internships</strong>
      </div>
      <div class="flip-card-back">
        Exposure to tech careers can raise long-term income by 40%.  
        In 94124, access could raise Black homeownership by 3%.
      </div>
    </div>
  </div>

  <!-- Card 2: Homebuyer Grants -->
  <div class="flip-card">
    <div class="flip-card-inner">
      <div class="flip-card-front">
        🏠<br />
        <strong>Homebuyer Grants</strong>
      </div>
      <div class="flip-card-back">
        Programs like down-payment assistance reduce barriers to ownership.  
        In SF, this could add 5% to Black homeownership rates.
      </div>
    </div>
  </div>

  <!-- Card 3: Community Broadband -->
  <div class="flip-card">
    <div class="flip-card-inner">
      <div class="flip-card-front">
        🌐<br />
        <strong>Community WiFi</strong>
      </div>
      <div class="flip-card-back">
        Broadband gaps fuel the digital divide.  
        Zip codes with free WiFi access report higher tech job readiness.
      </div>
    </div>
  </div>

  <!-- Card 4: Financial Literacy -->
  <div class="flip-card">
    <div class="flip-card-inner">
      <div class="flip-card-front">
        💸<br />
        <strong>Financial Literacy</strong>
      </div>
      <div class="flip-card-back">
        Wealth-building knowledge builds generational stability.  
        Teaching credit, savings, and investment early helps shift long-term trends.
      </div>
    </div>
  </div>

  <!-- Card 5: Rent-to-Own Programs -->
  <div class="flip-card">
    <div class="flip-card-inner">
      <div class="flip-card-front">
        🏘️<br />
        <strong>Rent-to-Own Housing</strong>
      </div>
      <div class="flip-card-back">
        Transitional programs create pathways to ownership.  
        Especially powerful in areas with historically low Black homeownership.
      </div>
    </div>
  </div>

  <!-- Card 6: Mentorship & Networks -->
  <div class="flip-card">
    <div class="flip-card-inner">
      <div class="flip-card-front">
        🤝<br />
        <strong>Mentorship Access</strong>
      </div>
      <div class="flip-card-back">
        Career and financial mentors increase opportunity confidence.  
        Peer and community-based mentorship boosts retention in tech.
      </div>
    </div>
  </div>
</div>

  </section>



  <section class="step">
    <h2>✨ Add Your Voice</h2>
    <p>What’s your ZIP? What’s your dream? What should access look like where you live?</p>
    <p><a href="https://forms.gle/example" target="_blank">Click here to share your story anonymously →</a></p>
    <p>EchoZIP turns numbers into narratives — and narratives into action.</p>
  </section>
</main>
