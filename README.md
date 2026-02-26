# Open-Food-Facts-Products-Prediction 🍞

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Library](https://img.shields.io/badge/Library-Scikit_Learn%20%7C%20RandomForest-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

[🇬🇧 English](#english) | [🇹🇷 Türkçe](#türkçe)

<a name="english"></a>
## 🇬🇧 English

# Open Food Facts Products Dataset Analysis

This repository contains analyses and findings based on the [Open Food Facts](https://world.openfoodfacts.org/data) dataset. The dataset includes information about food products worldwide and is used to evaluate various parameters such as product variety, quality, processing level, and environmental impact.

## Dataset Content

The dataset includes the following main attributes:

A description of the parts used in the project of the dataset.

- **code**: sequence number ID
- **product_name**: product name
- **brands**: which brand's product it is
- **main_category**: product's primary category
- **countries_tags**: country where the product is sold
- **additives_n**: number of additives in the product's content
- **nutriscore_grade**: indicates the value received by the products between A-E, showing the quality of nutrition of the products (degree of processing is not considered here; it is determined per 100g)
  - *A* = highest
  - *B* = good quality
  - *C* = average quality
  - *D* = low quality
  - *E* = lowest nutritional quality
 - **nova_group**: shows how natural or minimally processed the product is
   - *1* = unprocessed or minimally processed
   - *2* = processed
   - *3* = well processed
   - *4* = ultra-processed foods
 - **enviromental_score_score**: represents the environmental footprint of the product from production to packaging and delivery. It ranges from 0-100. A higher value indicates better environmental performance.
 - **energy-kcal_100g**: energy released as a result of the digestion of 100 grams of the product, measured in a commonly used energy unit.
 - **energy-kj_100g**: represents the total thermodynamic energy provided by 100 grams of the product.
 - **fat_100g**: describes how much fat is contained in 100 grams of the product.
 - **saturated-fat_100g**: indicates how many grams of saturated fat are contained in 100 grams of the product.
 - **sugars_100g**: describes how much sugar is contained in 100 grams of the product.
 - **fiber_100g**: describes how much fiber is contained in 100 grams of the product.
 - **proteins_100g**: describes how much protein is contained in 100 grams of the product.
 - **salt_100g**: describes how much salt is contained in 100 grams of the product.
 - **sodium_100g**: indicates how many grams of sodium mineral are contained in 100 grams of the product.

## Visualizations

The following visualizations are included in this repository:

### Treemap
A treemap visualization of the dataset, highlighting product variety, quality, processing level, and environmental impact.

![Treemap](https://github.com/fizmr/Open-Food-Facts-Products-Prediction/blob/main/images/country_treemap.png)

### Column Graph
A column graph illustrating various parameters of the dataset.

![Column Graph](path/to/column_graph.png)

### Interactive Visualization
An interactive visualization of categories within the dataset. You can access it by clicking [here](link/to/interactive_visualization).

## Analysis Highlights

- **United Kingdom (UK)**: The UK has a medium-high product volume. The Nutri-Score is around 3, indicating a slightly more balanced diet compared to other countries. Processing and environmental scores are similar to the European average.
  
- **Polonya**: Polonya has a lower nutritional quality score (2.78) but maintains a balanced profile with moderate processing levels and an environmentally friendly score of 53.08.
  
- **Netherlands**: Although the product volume is relatively low, the processing level is quite high (NOVA: 3.31). The diet quality is slightly below average, indicating a market dominated by industrialized foods.

## Usage

To use this repository, clone it and explore the visualizations included. You can modify and expand upon the existing analyses to suit your needs.
