# 🎨 Art Perception Analysis

## 🧪 Project Overview

This project explores how three visual factors—**brightness**, **size**, and **colourfulness**—influence the number of people attracted to different paintings. Using a synthetic dataset collected from controlled observations, we examine patterns and anomalies in visual preferences using various plots and statistical visualizations.

---

## 🧠 Key Findings

📈 When analysed individually, all three factors—brightness, size, and colourfulness—show an **increasing pattern** in the number of people attracted as the **intensity increases**.

![Size BarPlot](./images/size_plot.png)

![Brightness BarPlot](./images/brightness_plot.png)

![Colourfulness BarPlot](./images/colourfulness_plot.png)

🔥 According to the heatmaps, the **most attention** was drawn to:

  - **Moderately bright + large** sized paintings.

  - **Low colourfulness + large** sized paintings.  

  This is a bit unexpected, isn’t it?

  ![Brightness + Size Heatmap](./images/brightness+size_plot.png)  

  ![Colourfulness + Size Heatmap](./images/colourfulness+size_plot.png)  

The reason behind this can be seen using box plots for brightness and colourfulness as it shows outliers:

![Brightness + Size Boxplot](./images/brightness+size_boxplot.png)

![Colourfulness + Size Boxplot](./images/colourfulness+size_boxplot.png)

As seen, there are outliers in both the boxplots resulting in the strange results from the heatmaps!!

---

## 💡 Conclusions

- **Size matters most**—larger paintings consistently attracted more viewers.
- **Brightness has a sweet spot**—extremely bright or dim artworks were less appealing.
- **Colourfulness** isn’t always linear—sometimes low-colour paintings performed better, possibly due to minimalism or contrast.
