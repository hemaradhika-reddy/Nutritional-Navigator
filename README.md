# Nutritional Navigator
This project focuses on optimizing dietary plans to support healthier living by analyzing nutritional data and using optimization techniques. The aim is to maximize nutrient intake while adhering to caloric and other dietary constraints.

---

## **Project Overview**

Balanced nutrition is essential for maintaining health and preventing chronic diseases. Despite available dietary guidelines, individuals often struggle to create meal plans that align with their personal health goals like weight management, nutrient optimization, and disease prevention.

### **Key Features**
- **Nutritional Analysis:** Analyzes macronutrient and micronutrient compositions of food items.
- **Optimization Models:** Uses Linear Programming (LP) to recommend diet plans tailored to individual health goals.
- **Dietary Constraints:** Ensures adherence to calorie limits and specific nutrient requirements.
- **Personalization:** Customizable for specific populations and dietary preferences.

---

## **Dataset Description**

The dataset contains detailed nutritional information for various food items, including:

- **Nutrients:** Protein, Fat, Carbs, Fiber, Calcium, Sodium, Vitamins (A, C, D, K), etc.
- **Metadata:** Food names and unique identifiers.

### **Sample Columns**
| Column         | Description                               |
|----------------|-------------------------------------------|
| ID             | Unique identifier for each food item      |
| Food           | Name or description of the food item      |
| Calories       | Total caloric content per serving (kcal)  |
| Protein        | Protein content per serving (grams)       |
| Fiber          | Dietary fiber per serving (grams)         |

---

## **Optimization Techniques**

The project uses various optimization methods, including:

1. **Linear Optimization (OR-Tools):**
   - Goal: Maximize nutrient intake within calorie constraints.
   - Constraints: Calorie limits, minimum protein intake, etc.

2. **SciPy Linear Programming:**
   - Objective: Optimize the intake of Vitamin D, Vitamin C, and Calcium.
   - Constraints: Protein and calorie thresholds.

3. **Weighted Multi-Objective Optimization:**
   - Focus: Balance between protein, fiber, and calcium intake.
   - Constraints: Calorie and sodium limits.

4. **Penalty-Based Optimization:**
   - Goal: Minimize penalties for excessive calorie, sodium, and fat intakes.
   - Constraints: Minimum nutritional requirements.

---




## **Results**
- Successfully created nutrient-dense diet plans while adhering to caloric and other constraints.
- The optimization model can be adapted to specific populations and dietary goals.
- Enhanced nutritional recommendations for health-conscious individuals.

---

## **Team Members**
- **Suda Haripriya** (CB.EN.U4AIE21067)
- **Sykam Sumanjali** (CB.EN.U4AIE21068)
- **Hema Radhika Reddy** (CB.EN.U4AIE21050)
- **Likhitha Shree S** (CB.EN.U4AIE21052)

---

## **Guidance**
This project was conducted under the supervision of **Dr. Shyam A V**, School of AI.

---

## **Future Scope**
- Include more nutrients and dietary factors like fats and cholesterol.
- Extend the model to support real-time dietary recommendations.
- Develop a user-friendly web or mobile application for personalized diet planning.

---

## **Technologies Used**
- **Python Libraries:** OR-Tools, SciPy, Pandas, NumPy, Matplotlib, Seaborn
- **Visualization Tools:** Correlation Heatmaps, Boxplots
- **Optimization:** Google OR-Tools, SciPy Linear Programming

---

## **How to Run the Project**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/nutritional-navigator.git
   cd nutritional-navigator
