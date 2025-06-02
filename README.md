https://colab.research.google.com/drive/1A3U4wZ-V-XarzDSL7Lim_782zMM5xG_r

source
seaborn.pydata.org

# Seaborn
Seaborn sample
## s1
# Import seaborn
import seaborn as sns

# Apply the default theme
sns.set_theme()

# Load an example dataset
tips = sns.load_dataset("tips")

# Create a visualization
sns.relplot(
    data=tips,
    x="total_bill", y="tip", col="time",
    hue="smoker", style="smoker", size="size",
)
/////////////////
