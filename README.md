<!--
  Tableau Concepts README (HTML)
  - Upload images into ./images/ (or update paths below).
  - Copy-paste this block into README.md
-->

<style>
  /* Simple styles that GitHub will accept in README */
  .tb-container { max-width: 1100px; margin: 0 auto; font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial; line-height:1.5; color:#222; }
  .tb-hero { text-align:center; margin-bottom: 24px; }
  .tb-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); gap: 20px; }
  .tb-card { border: 1px solid #e6e6e6; border-radius: 8px; padding: 14px; background: #fff; box-shadow: 0 1px 2px rgba(0,0,0,0.03); }
  .tb-card h3 { margin: 6px 0 8px; font-size: 18px; }
  .tb-img { width: 100%; height: auto; border-radius: 4px; border: 1px solid #ddd; background:#fafafa; display:block; margin-bottom:10px; }
  .outcome { margin: 8px 0 0; padding-left: 18px; }
  figure { margin:0; }
  figcaption { font-size: 13px; color:#555; margin-top:4px; }
  .small { font-size:13px;color:#666; }
</style>

<div class="tb-container">
  <div class="tb-hero">
    <h1>📊 Tableau Concepts — Overview & Example Visuals</h1>
    <p class="small">Images referenced below should live in <code>./images/</code>. Replace placeholders with your exported Tableau images.</p>
  </div>

  <!-- MAPS -->
  <section>
    <h2>🗺 Maps</h2>
    <div class="tb-grid">
      <div class="tb-card">
        <figure>
          <img class="tb-img" src="./images/normal_map.png" alt="Normal Map - geographical map">
          <figcaption><strong>Normal map</strong> — geographic points/shape layers using Latitude/Longitude or geographic fields.</figcaption>
        </figure>
        <h3>What</h3>
        <p>Plot geographic data (countries, states, cities) to show spatial distribution and location-based values.</p>
        <h3>Outcomes</h3>
        <ul class="outcome">
          <li>Identify spatial clusters, hotspots and outliers.</li>
          <li>Compare metrics across regions (sales by state, incidents by city).</li>
        </ul>
      </div>

      <div class="tb-card">
        <figure>
          <img class="tb-img" src="./images/filled_map.png" alt="Filled Map - choropleth">
          <figcaption><strong>Filled map</strong> — choropleth shading of regions by a measure.</figcaption>
        </figure>
        <h3>What</h3>
        <p>Color geographic areas by a measure (darker = higher value).</p>
        <h3>Outcomes</h3>
        <ul class="outcome">
          <li>Visual intensity shows regional performance quickly.</li>
          <li>Useful for demographic or density comparisons.</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- TABLES -->
  <section>
    <h2>📄 Tables</h2>
    <div class="tb-grid">
      <div class="tb-card">
        <figure>
          <img class="tb-img" src="./images/text_table.png" alt="Text Table / Crosstab">
          <figcaption><strong>Text table (Crosstab)</strong> — exact values laid out in rows and columns.</figcaption>
        </figure>
        <h3>What</h3>
        <p>Display raw numbers for precise reporting (like a spreadsheet).</p>
        <h3>Outcomes</h3>
        <ul class="outcome">
          <li>Precise readout of metrics by category.</li>
          <li>Useful for exportable tabular reports and QA checks.</li>
        </ul>
      </div>

      <div class="tb-card">
        <figure>
          <img class="tb-img" src="./images/heat_table.png" alt="Heat Table">
          <figcaption><strong>Heat table</strong> — table with color-coded cells to highlight magnitude.</figcaption>
        </figure>
        <h3>What</h3>
        <p>Use color intensity within table cells to help users spot patterns.</p>
        <h3>Outcomes</h3>
        <ul class="outcome">
          <li>Fast detection of high/low values within a matrix.</li>
          <li>Works well for pivot-style comparisons.</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- CHARTS -->
  <section>
    <h2>📊 Charts & Visuals</h2>
    <div class="tb-grid">
      <div class="tb-card">
        <figure>
          <img class="tb-img" src="./images/pie_chart.png" alt="Pie Chart">
          <figcaption><strong>Pie chart</strong> — parts of a whole (percentage breakdown).</figcaption>
        </figure>
        <h3>Outcomes</h3>
        <ul class="outcome">
          <li>Quick composition view (avoid many slices).</li>
        </ul>
      </div>

      <div class="tb-card">
        <figure>
          <img class="tb-img" src="./images/histogram.png" alt="Histogram">
          <figcaption><strong>Histogram</strong> — frequency distribution of a numeric field.</figcaption>
        </figure>
        <h3>Outcomes</h3>
        <ul class="outcome">
          <li>Shows distribution shape, skewness and common ranges.</li>
        </ul>
      </div>

      <div class="tb-card">
        <figure>
          <img class="tb-img" src="./images/bar_chart.png" alt="Bar Chart">
          <figcaption><strong>Bar charts (stacked / clustered)</strong> — compare categories; stacked shows part-to-whole.</figcaption>
        </figure>
        <h3>Outcomes</h3>
        <ul class="outcome">
          <li>Compare categories and sub-categories easily.</li>
        </ul>
      </div>

      <div class="tb-card">
        <figure>
          <img class="tb-img" src="./images/scatter_plot.png" alt="Scatter Plot">
          <figcaption><strong>Scatter plot</strong> — correlation between two numeric fields; add size / color for more variables.</figcaption>
        </figure>
        <h3>Outcomes</h3>
        <ul class="outcome">
          <li>Reveal relationships, clusters and outliers.</li>
        </ul>
      </div>

      <div class="tb-card">
        <figure>
          <img class="tb-img" src="./images/packed_bubbles.png" alt="Packed Bubbles">
          <figcaption><strong>Packed bubbles</strong> — size-coded circles for comparing magnitudes.</figcaption>
        </figure>
        <h3>Outcomes</h3>
        <ul class="outcome">
          <li>High-level magnitude comparison (visual hierarchy).</li>
        </ul>
      </div>

      <div class="tb-card">
        <figure>
          <img class="tb-img" src="./images/tree_map.png" alt="Tree Map">
          <figcaption><strong>Tree map</strong> — nested rectangles for part-to-whole in hierarchical data.</figcaption>
        </figure>
        <h3>Outcomes</h3>
        <ul class="outcome">
          <li>See dominant categories and composition at a glance.</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- TIME SERIES -->
  <section>
    <h2>📈 Time Series</h2>
    <div class="tb-grid">
      <div class="tb-card">
        <figure>
          <img class="tb-img" src="./images/line_chart.png" alt="Line Chart">
          <figcaption><strong>Line chart</strong> — trends over time (single or multiple lines).</figcaption>
        </figure>
        <h3>Outcomes</h3>
        <ul class="outcome">
          <li>Track trends, seasonality and trend changes.</li>
        </ul>
      </div>

      <div class="tb-card">
        <figure>
          <img class="tb-img" src="./images/area_chart.png" alt="Area Chart">
          <figcaption><strong>Area chart</strong> — emphasize volume or cumulative totals over time.</figcaption>
        </figure>
        <h3>Outcomes</h3>
        <ul class="outcome">
          <li>Good for cumulative view (stacked area for components).</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- CIRCLES / FUNNEL / WORDCLOUD -->
  <section>
    <h2>🔵 Circles, Funnels & Word Clouds</h2>
    <div class="tb-grid">
      <div class="tb-card">
        <figure>
          <img class="tb-img" src="./images/circle_view.png" alt="Circle views">
          <figcaption><strong>Circle views / side-by-side circles</strong> — size-coded circles for category comparison.</figcaption>
        </figure>
        <h3>Outcomes</h3>
        <ul class="outcome">
          <li>Compare relative magnitudes in a compact layout.</li>
        </ul>
      </div>

      <div class="tb-card">
        <figure>
          <img class="tb-img" src="./images/funnel_chart.png" alt="Funnel Chart">
          <figcaption><strong>Funnel chart</strong> — stage-based conversion funnel (top to bottom narrowing).</figcaption>
        </figure>
        <h3>Outcomes</h3>
        <ul class="outcome">
          <li>Identify conversion drop-offs; optimize critical stages.</li>
        </ul>
      </div>

      <div class="tb-card">
        <figure>
          <img class="tb-img" src="./images/word_cloud.png" alt="Word Cloud">
          <figcaption><strong>Word cloud</strong> — high-frequency terms emphasized by size.</figcaption>
        </figure>
        <h3>Outcomes</h3>
        <ul class="outcome">
          <li>Quickly surface prominent keywords from text fields.</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- ANALYSIS TYPES -->
  <section>
    <h2>🔎 Analysis Types</h2>
    <div class="tb-card">
      <h3>Univariate</h3>
      <p>Analysis of a single variable (distribution, central tendency).</p>
      <h3>Bivariate</h3>
      <p>Two-variable analysis (correlation, relationship).</p>
      <h3>Multivariate</h3>
      <p>Three or more variables (use size, color, shape, or small multiples).</p>
      <h3>Outcomes</h3>
      <ul class="outcome">
        <li>Choose the chart type based on the number & type of variables and business question.</li>
      </ul>
    </div>
  </section>

  <!-- ADVANCED -->
  <section>
    <h2>🧩 Advanced Concepts</h2>
    <div class="tb-grid">
      <div class="tb-card">
        <h3>Custom Hierarchy</h3>
        <p>Create drill-down paths (e.g., Region → Country → State → City).</p>
        <h3>Outcomes</h3>
        <ul class="outcome">
          <li>Enable users to explore data from summary level to detail level.</li>
        </ul>
      </div>

      <div class="tb-card">
        <h3>Group By / Groups</h3>
        <p>Combine granular categories into higher-level groups for cleaner analysis.</p>
        <h3>Outcomes</h3>
        <ul class="outcome">
          <li>Simplify visualization by grouping minor categories into "Other".</li>
        </ul>
      </div>

      <div class="tb-card">
        <h3>Tableau Sets (Normal, Dynamic, Combined)</h3>
        <p><strong>Normal set:</strong> static selection. <strong>Dynamic set:</strong> updates with data. <strong>Combined set:</strong> union/intersection/difference of sets.</p>
        <h3>Outcomes</h3>
        <ul class="outcome">
          <li>Advanced segmentation and cohort analysis (e.g., Top N, repeat customers).</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- STORY, DASHBOARD, DOCUMENTATION -->
  <section>
    <h2>📚 Storytelling, Dashboards & Documentation</h2>
    <div class="tb-grid">
      <div class="tb-card">
        <h3>Story Points</h3>
        <p>Sequence of sheets/dashboards that narrate an insight-driven story.</p>
        <h3>Outcomes</h3>
        <ul class="outcome">
          <li>Guide stakeholders from high-level findings to root-cause evidence.</li>
        </ul>
      </div>

      <div class="tb-card">
        <figure>
          <img class="tb-img" src="./images/dashboard_placeholder.png" alt="Dashboard placeholder">
          <figcaption><strong>Dashboard</strong> — combined sheets with filters and actions.</figcaption>
        </figure>
        <h3>Outcomes</h3>
        <ul class="outcome">
          <li>Interactive single-pane view for monitoring KPIs.</li>
          <li>Actionable insights via filters, tooltips and dashboard actions.</li>
        </ul>
      </div>

      <div class="tb-card">
        <figure>
          <img class="tb-img" src="./images/documentation_placeholder.png" alt="Documentation placeholder">
          <figcaption><strong>Documentation</strong> — README, data dictionary, calculation notes and steps to reproduce.</figcaption>
        </figure>
        <h3>Outcomes</h3>
        <ul class="outcome">
          <li>Ensures reproducibility and hand-off readiness for other analysts.</li>
        </ul>
      </div>
    </div>
  </section>

  <hr style="margin:18px 0; border:none; border-top:1px solid #eee;">
  <p class="small">Tip: replace any <code>_placeholder</code> or missing images (e.g., <code>dashboard_placeholder.png</code>) with your exported Tableau PNGs. Keep filenames consistent and commit the `images/` folder with your README.</p>

</div>
