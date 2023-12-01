---
title: Hextra Theme
layout: hextra-home
---

<!-- Invisible Table for Layout -->
<table border="0" style="width: 100%; border-collapse: collapse;">
  <tr>
    <!-- Left Column -->
    <td style="width: 60%; vertical-align: top; border: none;">

{{< hextra/hero-badge >}}
  <div class="w-2 h-2 rounded-full bg-primary-400"></div>
  <span>Open to network</span>
  {{< icon name="globe-alt" attributes="height=14" >}} <!-- Icon representing connection -->
{{< /hextra/hero-badge >}}

<div class="mt-6 mb-6">
{{< hextra/hero-headline >}}
  Saul Garcia Huertes <!-- Title -->
{{< /hextra/hero-headline >}}
</div>

<div class="mb-12">
{{< hextra/hero-subtitle >}}
  Startup CEO & Co-founder. Tech Strategist. Lecturer. <!-- Subtitle -->
{{< /hextra/hero-subtitle >}}
</div>

<div class="mb-6">
{{< hextra/hero-button text="Contact Me" link="mailto:me@saulgh.xyz" >}}
</div>

</td>
    <!-- Right Column -->
    <td style="width: 40%; vertical-align: top; border: none;">


<div class="mb-12">
{{< hextra/hero-title-image image="/images/hero.svg" alt="Saul Garcia" imgStyle="width: 300px; height: auto;" >}}
</div>

  </td>
  </tr>
</table>

<div class="mt-6"></div>

{{< hextra/feature-grid >}}
  {{< hextra/feature-card
    title="Fast and Full-featured"
    subtitle="Simple and easy to use, yet powerful and feature-rich."
    class="aspect-auto md:aspect-[1.1/1] max-md:min-h-[340px]"
    image="images/hextra-doc.webp"
    imageClass="top-[40%] left-[24px] w-[180%] sm:w-[110%] dark:opacity-80"
    style="background: radial-gradient(ellipse at 50% 80%,rgba(194,97,254,0.15),hsla(0,0%,100%,0));"
  >}}
  {{< hextra/feature-card
    title="Markdown is All You Need"
    subtitle="Compose with just Markdown. Enrich with Shortcode components."
    class="aspect-auto md:aspect-[1.1/1] max-lg:min-h-[340px]"
    image="images/hextra-markdown.webp"
    imageClass="top-[40%] left-[36px] w-[180%] sm:w-[110%] dark:opacity-80"
    style="background: radial-gradient(ellipse at 50% 80%,rgba(142,53,74,0.15),hsla(0,0%,100%,0));"
  >}}
  {{< hextra/feature-card
    title="Full Text Search"
    subtitle="Built-in full text search with FlexSearch, no extra setup required."
    class="aspect-auto md:aspect-[1.1/1] max-md:min-h-[340px]"
    image="images/hextra-search.webp"
    imageClass="top-[40%] left-[36px] w-[110%] sm:w-[110%] dark:opacity-80"
    style="background: radial-gradient(ellipse at 50% 80%,rgba(221,210,59,0.15),hsla(0,0%,100%,0));"
  >}}
  {{< hextra/feature-card
    title="Lightweight as a Feather"
    subtitle="No dependency or Node.js is needed to use Hextra. Powered by Hugo, one of *the fastest* static site generators, building your site in just seconds with a single binary."
  >}}
  {{< hextra/feature-card
    title="Responsive with Dark Mode Included"
    subtitle="Looks great on different screen sizes. Built-in dark mode support, with auto-switching based on user's system preference."
  >}}
  {{< hextra/feature-card
    title="Build and Host for Free"
    subtitle="Build with GitHub Actions, and host for free on GitHub Pages. Alternatively it can be hosted on any static hosting service."
  >}}
  {{< hextra/feature-card
    title="Multi-Language Made Easy"
    subtitle="Create multi-language pages by just adding locales suffix to the Markdown file. Adding i18n support to your site is intuitive."
  >}}
  {{< hextra/feature-card
    title="And Much More..."
    icon="sparkles"
    subtitle="Syntax highlighting / Table of contents / SEO / RSS / LaTeX / Mermaid / Customizable / and more..."
  >}}
{{< /hextra/feature-grid >}}
