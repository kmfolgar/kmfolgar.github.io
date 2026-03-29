---
layout: default
title: Home
---

<!-- ══ OPENER: The problem ══════════════════════════════════════ -->
<section class="opener">
  <div class="opener-inner shell">
    <p class="opener-eyebrow">Population Health &nbsp;·&nbsp; Cancer Epidemiology &nbsp;·&nbsp; Health Equity</p>
    <p class="opener-statement">"Cancer doesn't<br>discriminate.."</p>
    <p class="opener-twist">But we know it does.</p>
    <p class="opener-explain">
      Differences in who gets cancer, at what stage, and whether they survive are not random.
      I argue that studying those differences is one of the most direct paths into understanding cancer.
    </p>
  </div>
  <div class="scroll-hint" aria-hidden="true">scroll</div>
</section>

<!-- ══ INTRO: Meet the researcher ══════════════════════════════ -->
<section class="section intro-section" id="overview">
  <div class="shell">
    <div class="intro-layout" data-animate>
      <div class="intro-text">
        <span class="section-label">Meet the researcher</span>
        <h2 class="intro-name">Kevin Martínez-Folgar, MD, PhD</h2>
        <p class="intro-role">Postdoctoral Research Fellow &nbsp;·&nbsp; Metabolic Epidemiology Branch, Division of Cancer Epidemiology and Genetics &nbsp;·&nbsp; National Cancer Institute, NIH</p>
        <p class="intro-bio">
As physicians we act as lifeguards in a river, always pulling the drowning to shore. But one day we need to ask who (or what) is throwing so many people into the river? I was treating patients daily, but one day I wanted to understand the <strong>why's</strong>. So I became an epidemiologist. I am a physician-scientist born in Guatemala and trained in Guatemala and the United States, and my work tries to answer Geoffrey Rose's fundamental question: <em>why does this patient have this disease, in this place, at this particular time?</em> My research integrates cancer surveillance, molecular epidemiology, and biomarker approaches to understand inequities in cancer outcomes and the ways in which social conditions become biologically embedded in disease. Much of my work has focused on disparities and hepato-gastro malignancies, but my broader goal is to understand how place, environment, and social context interact with biology to shape cancer etiology, risk, and treatment.
        </p>
        <p class="intro-bio">
I received my medical degree from the University of San Carlos of Guatemala and earned a PhD in Epidemiology from Drexel University. I completed postdoctoral training at the University of Michigan and at the Division of Cancer Epidemiology and Genetics at the U.S. National Cancer Institute, National Institutes of Health. My work combines quantitative epidemiology with computational methods, using tools such as R, Python, Spark, geographic information systems, and AI-assisted workflows to translate complex data into insights that can inform public health policy and clinical practice.
        </p>
        <div class="actions">
          <a class="btn btn-primary" href="{{ '/about/' | relative_url }}">About Me</a>
          <a class="btn" href="{{ '/publications/' | relative_url }}">Publications</a>
          <a class="btn" href="{{ '/cv/' | relative_url }}">CV</a>
          <a class="btn" href="{{ site.google_scholar }}" target="_blank" rel="noopener">Google Scholar</a>
          <a class="btn" href="https://orcid.org/{{ site.orcid }}" target="_blank" rel="noopener">ORCID</a>
          <a class="btn" href="https://github.com/{{ site.github_username }}" target="_blank" rel="noopener">GitHub</a>
        </div>
      </div>
      <div class="intro-illustration">
        <img src="{{ '/images/kevin-who-illustration.jpeg' | relative_url }}" alt="Illustration of Kevin presenting at a WHO event" />
      </div>
    </div>
  </div>
</section>

<!-- ══ RESEARCH AREAS ════════════════════════════════════════════ -->
<section class="section section-alt" id="expertise">
  <div class="shell">
    <div data-animate>
      <span class="section-label">Research</span>
      <h2 class="section-title">What I study</h2>
      <p class="section-intro">
        My work spans cancer epidemiology, molecular approaches, and data science, unified by one question:
        why are cancer burdens distributed unequally across populations?
      </p>
    </div>
    <div class="research-grid">
      <div class="r-card" data-animate data-delay="1">
        <span class="r-card-label">Cancer Epidemiology</span>
        <h3>Cancer Disparities &amp; Global Surveillance</h3>
        <p>Using population differences as a scientific instrument to understand why cancer occurs, in whom, and under what conditions. Population-level monitoring of incidence, mortality, and survival, from Latin American cities to global registries, as a tool for tracing causal pathways and informing prevention.</p>
      </div>
      <div class="r-card" data-animate data-delay="2">
        <span class="r-card-label">Molecular Epidemiology</span>
        <h3>Molecular &amp; Exposomic Approaches</h3>
        <p>Integrating biomarker data, proteomics, and exposomic frameworks to understand how biological pathways mediate the effects of social and environmental exposures on cancer risk and progression. Linking population-level patterns to molecular mechanisms.</p>
      </div>
      <div class="r-card" data-animate data-delay="3">
        <span class="r-card-label">Methods</span>
        <h3>Data Science &amp; AI in Epidemiology</h3>
        <p>Reproducible analytic workflows in R and Python. Geospatial analysis, multilevel modeling, causal inference, and AI-assisted data pipelines, translating complex population data into evidence for policy and clinical practice.</p>
      </div>
    </div>

    <ul class="chip-list" data-animate data-delay="5" style="margin-top:2rem;">
      <li>Cancer Epidemiology</li>
      <li>Global Cancer Surveillance</li>
      <li>Cancer Disparities</li>
      <li>Molecular Epidemiology</li>
      <li>Biomarker Approaches</li>
      <li>Infection-Related Malignancies</li>
      <li>Pediatric Cancer Surveillance</li>
      <li>Health Equity</li>
      <li>Geospatial Analysis</li>
      <li>Causal Inference</li>
      <li>AI-Assisted Analysis</li>
      <li>Data Visualization</li>
    </ul>
  </div>
</section>

<!-- ══ SELECTED PUBLICATIONS ════════════════════════════════════ -->
<section class="section" id="selected-work">
  <div class="shell">
    <div data-animate>
      <span class="section-label">Selected work</span>
      <h2 class="section-title">Publications</h2>
    </div>
    <ol class="pub-list">
      <li class="pub-item" data-animate data-delay="1">
        <span class="pub-num">01</span>
        <div>
          <p class="pub-title">Excess mortality during the COVID-19 pandemic in Guatemala</p>
          <p class="pub-authors"><strong>Martinez-Folgar K</strong>, Alburez-Gutierrez D, Paniagua-Avila A, Ramirez-Zea M, Bilal U</p>
          <p class="pub-journal">American Journal of Public Health, 2021</p>
          <a class="pub-doi" href="https://doi.org/10.2105/AJPH.2021.306452" target="_blank" rel="noopener">DOI: 10.2105/AJPH.2021.306452 ↗</a>
        </div>
      </li>
      <li class="pub-item" data-animate data-delay="2">
        <span class="pub-num">02</span>
        <div>
          <p class="pub-title">Inequalities in life expectancy in six large Latin American cities — SALURBAL study</p>
          <p class="pub-authors">Bilal U, …, <strong>Martinez-Folgar K</strong>, et al.</p>
          <p class="pub-journal">The Lancet Planetary Health, 2019</p>
          <a class="pub-doi" href="https://doi.org/10.1016/S2542-5196(19)30235-9" target="_blank" rel="noopener">DOI: 10.1016/S2542-5196(19)30235-9 ↗</a>
        </div>
      </li>
      <li class="pub-item" data-animate data-delay="3">
        <span class="pub-num">03</span>
        <div>
          <p class="pub-title">Mortality amenable to healthcare in Latin American cities</p>
          <p class="pub-authors">Mullachery P, …, <strong>Martinez-Folgar K</strong>, et al.</p>
          <p class="pub-journal">International Journal of Epidemiology, 2022</p>
          <a class="pub-doi" href="https://doi.org/10.1093/ije/dyab137" target="_blank" rel="noopener">DOI: 10.1093/ije/dyab137 ↗</a>
        </div>
      </li>
      <li class="pub-item" data-animate data-delay="4">
        <span class="pub-num">04</span>
        <div>
          <p class="pub-title">Variability and social patterning of cancer mortality in 343 Latin American cities</p>
          <p class="pub-authors">Alfaro T, <strong>Martinez-Folgar K</strong>, Bilal U, et al.</p>
          <p class="pub-journal">The Lancet Global Health, 2025</p>
          <a class="pub-doi" href="https://doi.org/10.1016/S2214-109X(24)00446-7" target="_blank" rel="noopener">DOI: 10.1016/S2214-109X(24)00446-7 ↗</a>
        </div>
      </li>
    </ol>
    <p class="pub-more" data-animate>
      Full list on <a href="{{ '/publications/' | relative_url }}">publications page</a> and <a href="{{ site.google_scholar }}" target="_blank" rel="noopener">Google Scholar ↗</a>
    </p>
  </div>
</section>
