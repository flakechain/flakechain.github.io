---
layout: splash
permalink: /
header:
  overlay_color: "#4A148C"
  overlay_image: hero.jpg
  ctas:
    - cta_label: "<i class='fa fa-building'></i> Learn More"
      cta_url: "/getting-started/"
    - cta_label: "<i class='fab fa-github'></i> Github"
      cta_url: "https://github.com/flakechain"
    - cta_label: "<i class='fas fa-cog'></i> Roadmap"
      cta_url: "/roadmap/"
  caption:
excerpt: 'A stable Cryptonote7 network with rich ecosystem. Total supply of 10 million of FLAKE and own Decentralized Exchange.<br />'
feature_row:
  - image_path: ecosystem-feature.png
    alt: "Rich Ecosystem"
    title: "Rich Ecosystem"
    excerpt: "FlakeChain has a rich ecosystem acively supported and growed by developers. Learn more about it compares with other coins."
    url: "/getting-started/"
    btn_label: "Learn More"
  - image_path: transparent-feature.png
    alt: "Transparency and Stability"
    title: "Transparency and Stability"
    excerpt: "In cryptocurrency, transparency brings trust. The Core team hold strong transparency in its financial and development process. Our strong principles also build a stable platform."
    url: "https://github.com/flakechain/meta"
    btn_label: "Learn More"
  - image_path: lamp-feature.png
    alt: "Community Driven"
    title: "Community Driven"
    excerpt: "We have a welcoming community and a donation-based development process. You have full control over the cryptocurrency you use, and can always choose a team you trust to develop FlakeChain."
    url: "/donate/"
    btn_label: "Support Us"
monthly-update:
  - excerpt: "Monthly Flake Update - Jun 2018 [Read Now](/2018/06/24/monthly-update-jun-2018/){: .btn}"
---

{% capture social_media %}
    <div class="social-intro" style="vertical-align: top;">FlakeChain Community</div>
  <div>
    <div class="social-links">
      <a href="https://github.com/flakechain"><i class="fab fa-github"></i></a>
      <a href="https://twitter.com/flakechain"><i class="fab fa-twitter"></i></a>
      <a href="https://flakechain.github.io/discrod/"><i class="fab fa-discord"></i></a>
      <a href="https://t.me/flakechain"><i class="fab fa-telegram"></i></a>
      <a href="https://bitcointalk.org/index.php?topic=3249137"><i class="fab fa-bitcoin"></i></a>
    </div>
  </div>
{% endcapture %}

{% include feature_row excerpt=social_media type="center" %}

{% include feature_row %}

{% include feature_row id="monthly-update" type="center" %}
