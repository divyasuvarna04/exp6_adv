# Animal Information Dashboard

## About the Dataset
[Animal Information Dataset](https://www.kaggle.com/datasets/iamsouravbanerjee/animal-information-dataset)

### Context
Animals are multicellular, eukaryotic organisms in the biological kingdom Animalia. With few exceptions, animals consume organic material, breathe oxygen, have myocytes and are able to move, can reproduce sexually, and grow from a hollow sphere of cells, the blastula, during embryonic development. As of 2022, 2.16 million living animal species have been described—of which around 1.05 million are insects, over 85,000 are mollusks, and around 65,000 are vertebrates. It has been estimated there are around 7.77 million animal species. Animals range in length from 8.5 micrometers (0.00033 in) to 33.6 meters (110 ft). They have complex interactions with each other and their environments, forming intricate food webs. The scientific study of animals is known as zoology.

### Content
This dataset encompasses a diverse array of attributes pertaining to various animal species worldwide. The dataset prominently includes fields such as Animal, Height (cm), Weight (kg), Color, Lifespan (years), Diet, Habitat, Predators, Average Speed (km/h), Countries Found, Conservation Status, Family, Gestation Period (days), Top Speed (km/h), Social Structure, and Offspring per Birth. These columns collectively offer a comprehensive understanding of animal characteristics, habitats, behaviors, and conservation statuses. Researchers and enthusiasts can utilize this dataset to analyze animal traits, study their habitats, explore dietary patterns, assess conservation needs, and conduct a wide range of ecological research and wildlife studies.

### Dataset Glossary (Column-wise)
- **Animal**: Name of the animal.
- **Height (cm)**: Height range in centimeters for the animal.
- **Weight (kg)**: Weight range in kilograms for the animal.
- **Color**: Common colors associated with the animal's appearance.
- **Lifespan (years)**: Average lifespan of the animal in years.
- **Diet**: Type of diet the animal primarily follows (e.g., Carnivore, Herbivore).
- **Habitat**: Typical habitat or environment where the animal is found.
- **Predators**: Natural enemies or organisms that prey on the animal.
- **Average Speed (km/h)**: The average speed range the animal can achieve in kilometers per hour.
- **Countries Found**: Countries or regions where the animal is commonly found.
- **Conservation Status**: The conservation status of the animal as per relevant conservation organizations.
- **Family**: Taxonomic family the animal belongs to.
- **Gestation Period (days)**: Range of days representing the gestation or pregnancy period of the animal.
- **Top Speed (km/h)**: The maximum speed the animal can achieve in kilometers per hour.
- **Social Structure**: Information about the social behavior or structure of the animal (e.g., Solitary, Group-based).
- **Offspring per Birth**: The typical number of offspring born per birth or reproduction event for the animal.

---

## Dashboard Overview

### PAGE 1

- **Count of Animal (Card)**:
  - **Chart Type**: Summary Card
  - **Description**: This card shows the total count of unique animal species in the dataset, which is 196. It provides a high-level overview of the animal diversity being analyzed.

- **Count of Countries Found (Card)**:
  - **Chart Type**: Summary Card
  - **Description**: This card represents the number of countries from which the animals in the dataset originate, totaling 104. It highlights the geographical spread of species across various regions.

- **Average of Average Social Structure (Card)**:
  - **Chart Type**: Summary Card
  - **Description**: This card shows the average value for "social structure" characteristics of the animals, with a mean of 33.48. It provides a numerical insight into how animals organize themselves socially.

- **Average of Height (cm) (Card)**:
  - **Chart Type**: Summary Card
  - **Description**: This card indicates the average height of animals in the dataset, which is 193.93 cm. It offers an overview of the general size range of the species being studied.

- **Average of Lifespan (years) (Gauge Chart)**:
  - **Chart Type**: Gauge Chart
  - **Description**: This gauge chart shows the average lifespan of animals in years, ranging from 0 to 51.73 years. The current average lifespan across the dataset is around 25.86 years.

- **Average of Gestation Period (days) (Gauge Chart)**:
  - **Chart Type**: Gauge Chart
  - **Description**: This chart represents the average gestation period in days, with a range from 0 to 285.07 days. The current average is around 142.53 days, providing insight into the reproductive cycles of the animals.

- **Main Country and Habitat (Map)**:
  - **Chart Type**: World Map
  - **Description**: This map visualizes the geographic distribution of the animals based on their main countries and habitats. Dots represent locations where different species are found, giving an understanding of their global spread.

- **Count of Animal by Predator_1 (Treemap)**:
  - **Chart Type**: Treemap
  - **Description**: This treemap shows the count of animals by their predators. Predators are color-coded and sized according to the number of animals they prey on. Larger blocks, like "Birds," "Leopards," "Lions," and "Tigers," suggest those predators have a larger impact on the animal population.

- **Social Structure (Word Cloud)**:
  - **Chart Type**: Word Cloud
  - **Description**: This word cloud visualizes the different types of social structures animals exhibit, such as "Group based," "Solitary," "Colony," and "Pack." It represents the diversity of social organization among the animals.

- **Height (cm) (Box Plot)**:
  - **Chart Type**: Box Plot
  - **Description**: This section is likely meant to show the distribution of heights of animals in a box plot, highlighting the median, range, and outliers of animal heights in centimeters.

- **Average of Lifespan (years) by Conservation Status (Funnel Chart)**:
  - **Chart Type**: Bar Chart
  - **Description**: This funnel chart shows the average lifespan of animals categorized by their conservation status, such as Vulnerable, Endangered, Critically Endangered, and Extinct. Each bar represents the average lifespan in years for animals within each conservation status.

---

### PAGE 2

- **Average of Height (cm) and Average of Average Speed (km/h) by Family (Bar and line chart)**:
  - **Description**: This bar and line chart compares the average height of different animal families (represented by bars) with their average speed (represented by a line). Each family has its height on the left Y-axis, while the average speed is on the right Y-axis. Families include various animals like elephants, rhinos, and dolphins.

- **Count of Animal by Diet (Horizontal bar chart)**:
  - **Description**: This horizontal bar chart shows the distribution of animals based on their diet. Different diets like carnivore, herbivore, omnivore, and insectivore are represented, with the length of the bar showing the count of animals in each category.

- **Social Structure, Weight (kg) and Height (cm) (Scatter plot)**:
  - **Description**: A scatter plot chart that displays the relationship between animals' social structures, weight, and height. Each point represents an animal, with weight on the X-axis and height on the Y-axis. Different colors might represent different social structures.

- **Average of Weight (kg) and Average of Average Speed (km/h) by Diet (Stacked Column chart)**:
  - **Description**: This stacked column chart visualizes the average weight of animals (represented by bars) and their average speed (represented by a line) across different diets such as carnivore, herbivore, and omnivore. The left Y-axis shows weight and the right Y-axis shows speed, demonstrating if the animal has more weight then the speed might be less.

- **Count of Animal by Color (Donut chart)**:
  - **Description**: A donut chart that shows the count of animals based on their color. Different segments of the chart represent different animal colors, with each segment's size corresponding to the number of animals with that color.
