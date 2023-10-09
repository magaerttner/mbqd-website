---
# An instance of the People widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: blank

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

design:
  columns: "1"

title: Networks and Funding
subtitle:
---
<style>
  .funding-row {
    margin: 25px 5px;
  }

  .funding-cell * {
  margin: auto;
  }

  @media (min-width: 576px){
    .funding-cell {
      display: table-cell;
      vertical-align: middle;
    }

    .funding-cell:nth-child(1) {
      width: 30%;
      /*padding: 5%;*/
    }

    .funding-row {
      display: table-row;
    }

    .funding-table {
      display: table;
      border-spacing: 0.5em;
    }
  }
</style>

<div class="funding-table">
  <div class="funding-row">
    <div class="funding-cell">
      <a href="https://www.isoquant-heidelberg.de/">
        <img src="/logos/acp.jpg" alt="ACP logo Jena">
      </a>
    </div>
    <div class="funding-cell">
      <span>Martin Gärttner is a principal scientist within the <a href="https://www.acp.uni-jena.de/">Abbe Center of Photonics</a>, which bundles research activities in optics and photonics in Jena.</span>
    </div>
  </div>
</div>