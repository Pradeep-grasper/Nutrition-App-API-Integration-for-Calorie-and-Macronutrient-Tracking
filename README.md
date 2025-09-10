# Flutter Nutrition Tracker 🍎

A **Flutter-based application** designed to help users track their daily nutritional intake.  
It integrates with the **OpenFoodFacts API** to provide detailed food information, enabling users to log meals and monitor calories, protein, carbs, and fat.  

---

## ✨ Core Functionalities

The application is packed with features to make nutrition tracking **simple and insightful**:

### 🔗 API Integration
- Uses the **OpenFoodFacts API** to fetch nutritional details for foods.  
- Supports **live searching** for food items by name.  
- UI prepared for **barcode scanning** (logic is currently a placeholder for future integration).  

### 🍽️ Dynamic Meal Logging
- Users can add foods to **four meal categories**: Breakfast, Lunch, Snack, and Dinner.  
- Nutritional info (protein, carbs, fat per 100g) is pulled directly from the API.  

### 📊 Dashboard Calculations & Visualization
- Automatically calculates and displays **daily totals** for calories and macros.  
- Includes **progress bars** and **metric cards** for progress tracking.  
- **Water intake tracker** for hydration monitoring.  

### 🎨 UI/UX
- Clean, **modern design** with an intuitive user experience.  
- Fast data entry through searching and adding foods.  
- Each meal category lists logged foods with their nutritional info for **quick reference**.  

---

## 🏗 Project Structure
/lib
main.dart
/screens
nutrition_screen.dart
[other screens/components]

/assets
[icons, mock images]


## 🧪 Testing

The application has been tested to ensure **accuracy and reliability**:

- ✅ Calorie and macronutrient calculations verified for accuracy.  
- ✅ API-based food search and logging tested for speed.  
- ✅ UI responsiveness checked across multiple device sizes.  
- ✅ Live demo with real meals confirmed **dynamic calculations** work correctly.  

---

## 🚀 Next Steps & Future Improvements

Planned enhancements include:  
- 💾 **Persistence**: Local or cloud database to save meal logs and user history.  
- 📷 **Barcode Integration**: Connect barcode scanning UI to the food search workflow.  
- ⚡ **Custom Macro Goals**: Let users set their own daily macronutrient targets.  
- 🥦 **Expanded Nutrition Tracking**: Add fiber, sugar, sodium, and other micronutrients.  

---

## 📚 Sources
- [OpenFoodFacts API](https://world.openfoodfacts.org/data)

---

The project follows a standard **Flutter app structure**:

