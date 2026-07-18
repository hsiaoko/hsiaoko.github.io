---
permalink: /
title: "About Me"
excerpt: "Homepage"
author_profile: true
hide_title: true
redirect_from: 
  - /about/
  - /about.html
---

<section class="home-hero" aria-label="Introduction">
  <canvas id="network-hero" class="home-hero__canvas"></canvas>
  <div class="home-hero__content">
    <h1 class="home-hero__name">Xiaoke Zhu</h1>
    <p class="home-hero__title">Research Fellow, Shenzhen Institute of Computing Sciences (SICS)</p>
    <p class="home-hero__tagline">Building fast, scalable systems for graph analytics, data cleaning, and AI-driven databases.</p>
    <div class="home-hero__actions">
      <a class="home-cta home-cta--primary" href="/publications/"><i class="fa fa-book" aria-hidden="true"></i> Publications</a>
      <a class="home-cta home-cta--secondary" href="/files/Xiaoke_Zhu_En_CV.pdf"><i class="fa fa-file-text" aria-hidden="true"></i> Download CV</a>
      <a class="home-cta home-cta--secondary" href="mailto:{{ site.author.email }}"><i class="fa fa-envelope" aria-hidden="true"></i> Email</a>
    </div>
  </div>
</section>

<p class="home-intro">
I am Xiaoke Zhu (Hsiaoko Chu in Wade-Giles romanization), currently a research fellow at <a href="https://en.sics.ac.cn">Shenzhen Institute of Computing Sciences</a> (SICS). I received my Ph.D. from <a href="https://ev.buaa.edu.cn/">Beihang University</a> in October 2025, advised by <a href="https://homepages.inf.ed.ac.uk/wenfei/">Prof. Wenfei Fan</a>, and my M.S. from <a href="http://english.ynu.edu.cn/">Yunnan University</a> in 2020. My work focuses on graph computing, GPU-accelerated algorithms, high-performance data cleaning, and AI4DB. I welcome collaborations and discussions—feel free to reach out via email.
</p>

<h2 class="home-section-title">News</h2>
<ul class="news-timeline">
  <li><span class="news-date">NOV 2025</span><span class="venue-badge">SIGMOD'26</span> Our paper <a href="/files/paper/NPML_paper.pdf">Enumerating Graph Pattern Matches with ML Oracles</a> was accepted to <b>SIGMOD 2026</b>.</li>
  <li><span class="news-date">OCT 2025</span> I joined <a href="https://en.sics.ac.cn">Shenzhen Institute of Computing Sciences</a> (SICS) as a research fellow.</li>
  <li><span class="news-date">NOV 2024</span> Successfully defended my Ph.D. thesis. <a href="/files/slides/Thesis-slides.pdf">(Download slides)</a></li>
  <li><span class="news-date">NOV 2024</span><span class="venue-badge">SIGMOD'25</span> Our paper <a href="/files/paper/MiniClean_paper.pdf">GPU-Accelerated Graph Cleaning with a Single Machine</a> was accepted to <b>SIGMOD 2025</b>.</li>
  <li><span class="news-date">NOV 2024</span><span class="venue-badge">VLDB'25</span> Our paper <a href="/files/paper/Planar_paper.pdf">A Single Machine System for Querying Big Graphs with PRAM</a> was accepted to <b>VLDB 2025</b>.</li>
  <li><span class="news-date">OCT 2024</span><span class="venue-badge">VLDB'25</span> Our paper <a href="/files/paper/HyperBlocker_full_paper.pdf">HyperBlocker: Accelerating Rule-Based Blocking in Entity Resolution Using GPUs</a> was accepted to <b>VLDB 2025</b>.</li>
  <li><span class="news-date">OCT 2024</span><span class="venue-badge">IEEE BigData'24</span> Our paper <a href="/files/paper/NN-sort_paper.pdf">Deep Learning Service for Efficient Data Distribution Aware Sorting</a> was accepted to <b>IEEE BigData 2024</b>.</li>
  <li><span class="news-date">APR 2023</span><span class="venue-badge">VLDB'23</span> Our paper <a href="/files/paper/MiniGraph_full_paper.pdf">MiniGraph: Querying Big Graphs with a Single Machine</a> was accepted to <b>VLDB 2023</b>.</li>
  <li><span class="news-date">FEB 2022</span><span class="venue-badge">ICDE'22</span> Our paper <a href="/files/paper/PER_paper.pdf">Deep and Collective Entity Resolution in Parallel</a> was accepted to <b>ICDE 2022</b>.</li>
  <li><span class="news-date">SEP 2021</span> I joined <a href="https://en.sics.ac.cn">Shenzhen Institute of Computing Sciences</a> (SICS) as a research intern.</li>
  <li><span class="news-date">JUL 2021</span><span class="venue-badge">IEEE CLOUD'21</span> Our paper <a href="/files/paper/DLB_paper.pdf">DLB: Deep Learning Based Load Balancing</a> was accepted to <b>IEEE CLOUD 2021</b>.</li>
</ul>

<h2 class="home-section-title">Research Interests</h2>

<div class="research-card">
  <h3>Graph Computing Systems</h3>
  <p>Building high-level programming models and runtime systems that execute graph applications on shared-memory, out-of-memory, CPU, or GPU architectures. I have improved I/O efficiency for out-of-core graph analytics (e.g., PageRank, SSSP) and optimized GPU performance for graph mining tasks such as graph cleaning and pattern matching.</p>
  <p><strong>Representative work:</strong> <a href="/files/paper/MiniGraph_full_paper.pdf">VLDB'23</a>, <a href="/files/paper/Planar_paper.pdf">VLDB'25</a>, <a href="/files/paper/MiniClean_paper.pdf">SIGMOD'25</a>, <a href="/files/paper/NPML_paper.pdf">SIGMOD'26</a></p>
</div>

<div class="research-card">
  <h3>Data Cleaning</h3>
  <p>Accelerating data cleaning systems on modern hardware such as GPUs and distributed clusters. I have benchmarked parallel runtime systems for data cleaning and identified their performance bottlenecks, with a focus on rule-based blocking and entity resolution.</p>
  <p><strong>Representative work:</strong> <a href="/files/paper/PER_paper.pdf">ICDE'22</a>, <a href="/files/paper/HyperBlocker_full_paper.pdf">VLDB'25</a>, <a href="/files/paper/MiniClean_paper.pdf">SIGMOD'25</a></p>
</div>

<div class="research-card">
  <h3>AI4DB</h3>
  <p>Leveraging machine learning and deep learning to replace manual DBA effort and classical algorithms, enabling more efficient data processing and resource management. I have designed learned models for sorting, load balancing, and scheduling.</p>
  <p><strong>Representative work:</strong> <a href="/files/paper/DLB_paper.pdf">IEEE CLOUD'21</a>, <a href="/files/paper/NN-sort_paper.pdf">IEEE BigData'24</a></p>
</div>

{% if site.goatcounter %}
<div class="visitor-map">
  <h3 class="visitor-map__title">Site Analytics</h3>
  <p class="visitor-map__caption">
    Visitor statistics are collected by <a href="https://goatcounter.com">GoatCounter</a> (privacy-friendly, no cookies).
    View the dashboard at <a href="https://{{ site.goatcounter }}.goatcounter.com">{{ site.goatcounter }}.goatcounter.com</a>.
  </p>
  <script data-goatcounter="https://{{ site.goatcounter }}.goatcounter.com/count" async src="//gc.zgo.at/count.js"></script>
</div>
{% endif %}

<script>
(function() {
  'use strict';

  var canvas = document.getElementById('network-hero');
  if (!canvas) return;

  var ctx = canvas.getContext('2d');
  var hero = canvas.parentElement;
  var width, height, dpr;
  var particles = [];
  var mouse = { x: null, y: null };
  var isVisible = true;
  var rafId = null;

  var prefersReducedMotion = window.matchMedia &&
    window.matchMedia('(prefers-reduced-motion: reduce)').matches;

  function resize() {
    dpr = window.devicePixelRatio || 1;
    width = hero.clientWidth;
    height = hero.clientHeight;
    canvas.width = Math.floor(width * dpr);
    canvas.height = Math.floor(height * dpr);
    ctx.setTransform(1, 0, 0, 1, 0, 0);
    ctx.scale(dpr, dpr);
  }

  function initParticles() {
    particles = [];
    var count = Math.min(60, Math.floor((width * height) / 12000));
    for (var i = 0; i < count; i++) {
      particles.push({
        x: Math.random() * width,
        y: Math.random() * height,
        vx: (Math.random() - 0.5) * 0.4,
        vy: (Math.random() - 0.5) * 0.4,
        r: Math.random() * 2 + 1.5
      });
    }
  }

  function draw() {
    ctx.clearRect(0, 0, width, height);

    for (var i = 0; i < particles.length; i++) {
      var p = particles[i];

      if (!prefersReducedMotion) {
        p.x += p.vx;
        p.y += p.vy;

        if (p.x < 0 || p.x > width) p.vx *= -1;
        if (p.y < 0 || p.y > height) p.vy *= -1;

        if (mouse.x !== null && mouse.y !== null) {
          var dx = p.x - mouse.x;
          var dy = p.y - mouse.y;
          var dist = Math.sqrt(dx * dx + dy * dy);
          if (dist < 100 && dist > 0) {
            var force = (100 - dist) / 100;
            p.x += (dx / dist) * force * 1.5;
            p.y += (dy / dist) * force * 1.5;
          }
        }
      }

      ctx.beginPath();
      ctx.arc(p.x, p.y, p.r, 0, Math.PI * 2);
      ctx.fillStyle = 'rgba(253, 252, 248, 0.6)';
      ctx.fill();
    }

    for (var a = 0; a < particles.length; a++) {
      for (var b = a + 1; b < particles.length; b++) {
        var dx = particles[a].x - particles[b].x;
        var dy = particles[a].y - particles[b].y;
        var dist = Math.sqrt(dx * dx + dy * dy);
        if (dist < 120) {
          ctx.beginPath();
          ctx.moveTo(particles[a].x, particles[a].y);
          ctx.lineTo(particles[b].x, particles[b].y);
          ctx.strokeStyle = 'rgba(10, 147, 150, ' + (1 - dist / 120) * 0.35 + ')';
          ctx.lineWidth = 1;
          ctx.stroke();
        }
      }
    }
  }

  function loop() {
    if (!isVisible) return;
    draw();
    rafId = requestAnimationFrame(loop);
  }

  function start() {
    if (rafId) cancelAnimationFrame(rafId);
    resize();
    initParticles();
    loop();
  }

  if ('IntersectionObserver' in window) {
    var observer = new IntersectionObserver(function(entries) {
      isVisible = entries[0].isIntersecting;
      if (isVisible && !rafId) loop();
    }, { threshold: 0 });
    observer.observe(hero);
  }

  hero.addEventListener('mousemove', function(e) {
    var rect = hero.getBoundingClientRect();
    mouse.x = e.clientX - rect.left;
    mouse.y = e.clientY - rect.top;
  });

  hero.addEventListener('mouseleave', function() {
    mouse.x = null;
    mouse.y = null;
  });

  window.addEventListener('resize', function() {
    resize();
    initParticles();
  });

  if (!prefersReducedMotion) {
    start();
  } else {
    resize();
    initParticles();
    draw();
  }
})();
</script>
