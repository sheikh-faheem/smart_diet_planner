<img width="1918" height="717" alt="image" src="https://github.com/user-attachments/assets/4db2030c-4c02-406c-8ecb-9315d0ccbf49" /># Smart Health Planner - Diet & Workout Companion

## Overview

Smart Health Planner is a comprehensive web application designed to help users manage their fitness and nutrition goals. This interactive tool provides personalized meal plans, workout routines, and progress tracking based on individual user profiles.

## Key Features

1. **Personalized User Profile**
   - Collects essential health metrics (age, weight, height, gender)
   - Accounts for activity level and fitness goals
   - Supports various dietary preferences (Vegetarian, Vegan, Keto, etc.)

2. **Nutrition Planning**
   - Calculates BMI and recommended daily calorie intake
   - Provides macronutrient breakdown (proteins, carbs, fats)
   - Meal planning with calorie tracking for breakfast, lunch, dinner, and snacks
   - Water intake tracker

3. **Workout Planning**
   - Custom workout suggestions based on focus area (Full Body, Upper/Lower, Cardio)
   - Tailored routines for different fitness goals (Weight Loss, Muscle Gain, Maintenance)

4. **Progress Tracking**
   - Weight tracking with visualization
   - Progress chart with target weight indicator
   - Data persistence using local storage

5. **Export Functionality**
   - Generate PDF reports of your health plan

## Technical Implementation

- **Frontend**: HTML5, CSS3, JavaScript
- **UI Framework**: Tailwind CSS
- **Charts**: Chart.js for data visualization
- **PDF Generation**: html2pdf.js
- **Icons**: Font Awesome
- **Font**: Poppins from Google Fonts

## Installation & Usage

No installation required! Simply open the HTML file in any modern web browser.

To use:
1. Fill in your personal details in the User Profile section
2. The app will automatically calculate your health metrics
3. Use the "Suggest" buttons to generate meal and workout plans
4. Track your progress over time
5. Save your data or export as PDF

## Data Storage

All user data is stored locally in the browser using localStorage, meaning:
- Your data persists between sessions
- No server-side storage (works completely offline)
- You can reset all data with the "Reset" button

## Customization

The application can be easily customized by:
- Modifying the meal suggestions in the `suggestMeal()` and `suggestPlan()` functions
- Adjusting workout routines in the `suggestWorkout()` function
- Changing the color scheme via Tailwind CSS classes
- Updating the nutritional calculations in `calculateHealthStats()`

## Screenshot

<img width="1918" height="717" alt="Screenshot 2025-07-28 155705" src="https://github.com/user-attachments/assets/0cd7b797-a1f6-4956-8916-3016ab0582a6" />


## Future Enhancements

1. Integration with fitness APIs (Google Fit, Apple Health)
2. Recipe database with nutritional information
3. Exercise video demonstrations
4. Mobile app version
5. Social sharing features

## License

This project is open-source and available under the MIT License.

---

For any questions or contributions, please open an issue or submit a pull request.
