# 💜 GymByCollin

A sleek black-and-purple fitness app, built for your phone.

Enter your height, weight, age, lifting experience and goal (**bulk**, **cut** or **maintain**), and GymByCollin builds your plan:

- **Home**: daily calories and macros, today's workout, and water, sleep and step rings
- **Goal**: weekly weight-change target, a timeline to your goal weight, and a step-by-step plan for getting there
- **Train**: a workout split for **mass** or an **aesthetic** physique, built around your experience and days per week
- **Fuel**: a sample day of eating plus the best foods for bulking or cutting
- **Recover**: water, sleep and steps targets with daily trackers
- **📸 Food scanner**: snap a photo and AI identifies each food, estimates its weight, and shows the calories and protein. Adjust the grams with a slider
- **▥ Barcode scanner**: scan any packaged food and pull its nutrition from [Open Food Facts](https://world.openfoodfacts.org)
- **🏋️ Workout tracker**: log sets and reps with a rest timer. It shows what you lifted last time and automatically detects **personal records** (heaviest weight, rep PRs, estimated 1RM) with progress charts
- **🎨 Themes**: pick any accent color and background in Settings

## Setting up the food scanner (free)

The photo scanner uses Google Gemini:
1. Go to [aistudio.google.com/apikey](https://aistudio.google.com/apikey) and create a free API key
2. In GymByCollin, open ⚙️ **Settings → Food scanner AI key** and paste it in

The key is stored only on your phone. Barcode scanning needs no key.

> Photo calorie estimates are typically within about 20–30% of the true value, because weight is hard to judge from a photo. For best accuracy, shoot from slightly above with a fork or your hand in the frame for scale, and adjust the grams if a portion looks off. Packaged foods are most accurate when you use the barcode scanner.

## Use it on your phone

1. Open the GitHub Pages link: **https://consis300.github.io/GymByCollin/**
2. **iPhone:** tap Share → **Add to Home Screen**. **Android:** tap ⋮ → **Add to Home screen**.
3. It opens full-screen with its own icon, like a real app. Your profile, workouts and logs are saved on your phone. Use **Settings → Back up my data** now and then so you don't lose your PRs.

## How the numbers work

- Calories use the Mifflin-St Jeor formula × an activity multiplier based on your lifestyle and training days, then a surplus (bulk) or deficit (cut) sized to your experience
- Protein is 0.8–1 g per lb of body weight, fat is about 25% of calories, and carbs make up the rest
- Water is ½ oz per lb of body weight + 16 oz for training. Sleep is 7–9 h for adults, 8–10 h for teens. Steps are 7.5k–10k depending on your goal

These are science-based estimates, not medical advice.
