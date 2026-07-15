<style>
  /* This changes the background of the live GitHub Page */
  body {
    background: linear-gradient(135deg, #d4fc79 0%, #ffffff 100%) !important;
    background-attachment: fixed !important;
  }
  
  /* This ensures your text stays readable over the gradient */
  .markdown-body {
    background-color: transparent !important;
  }
</style>

<div align="center">
  <h1>🌲 OAP 2021 Revisited</h1>
  <p><em>Correcting Graduate School Statistics with Python</em></p>

  <a href="OAP_2021_Revisited.ipynb">
    <img src="https://img.shields.io/badge/Python-View_Code-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="View Python Code" />
  </a>
  &nbsp;&nbsp;
  <a href="oap_data.csv">
    <img src="https://img.shields.io/badge/Data-View_Dataset-2ea44f?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="View Dataset" />
  </a>
</div>

<br>

In 2021, my graduate school team adapted the Family Leisure Activity Profile to build an Outdoor Activities Profile (OAP) for Liberty University students. While we successfully gathered survey data via Qualtrics, I always felt our original statistical methodology failed to tell the true story of the data.

Our original presentation relied on unsupported One-Way ANOVAs to claim there were no differences between sexes, and we drew questionable conclusions about satisfaction vs. involvement. I built this repository to revisit that data and apply the mature analytical skills I have today.

### 🛠️ The Revision Project

* **Data Cleaning:** Rebuilt the messy Qualtrics dataset using **Pandas** and **NumPy**.
* **Statistical Correction:** Replaced the flawed ANOVAs with an **Independent T-Test** via **SciPy** for accurate gender comparisons.
* **Bivariate Analysis:** Shifted from purely descriptive claims to a formal **Pearson correlation** to prove the relationship between student involvement and satisfaction.
* **Visualization:** Upgraded the visual storytelling using **Seaborn** and **Matplotlib**.

<br>

<div align="center">
  <img src="name_of_your_image_file.png" alt="Bivariate Scatter Plot of Involvement vs Satisfaction" width="750"/>
</div>


