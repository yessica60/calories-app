# My Food Management App

This food management application allows you to administer your daily meals, log foods, and track consumed calories.

### Developer:

- [Yessica60](https://github.com/yessica60). 2019-1056
- [edwardb11](https://github.com/Edwardb11). 2019-0823

## Overview

![image](https://github.com/yessica60/calories-app/assets/37183622/4c69b139-a610-4164-858f-633ea6aaa693)
![image](https://github.com/yessica60/calories-app/assets/37183622/e567607e-b9d1-49ac-be92-a860a07f3b93)
![image](https://github.com/yessica60/calories-app/assets/37183622/15eab3ca-cbdd-43a6-a934-439b7fa35eba)
![image](https://github.com/yessica60/calories-app/assets/37183622/9a0e8c8a-3ca8-466c-91f0-1c8eaf9bc043)

## Installation

1. Clone this repository: `git clone https://github.com/yessica60/calories-app`
2. Navigate to the directory: `cd calories-app`
3. Install dependencies: `npm install` or `yarn install`

## Usage

The application consists of multiple components and functionalities:

### 1. `AddFoodModal`

This component is a modal used to add foods. It's utilized to input details like calories, name, and portions of the food.

### 2. `Header`

The header contains user information and a representative image. Additionally, it provides a back navigation if needed.

### 3. `TodayCaloriesAnimated`

This component visualizes consumed calories in a day. It displays total calories, consumed, and remaining, with an animated percentage.

### 4. `TodayMeals`

Offers a list of meals for the current day. It doesn't allow addition or deletion of elements, only visualization.

### 5. `ViewFoods`

Represents each meal in a list, showing its name, portion, and calories. It includes an icon for addition or removal based on functionality.

### 6. `AddFood`

A primary screen showing the list of foods and allowing the addition of new foods to the list.

### 7. `Home`

Another primary screen displaying the summary of daily calorie intake and meals of the day.

## Reusable Components

The project contains various reusable atoms:

### - `AtomButton`

A customizable button with the ability to modify its styles.

### - `AtomText`

A text component also allowing style adjustments.

### - `AtomInput`

A text input component with adaptable styles.

## Customization

Each component can be customized through styles provided as props.

## Contribution

If you wish to contribute, please:

1. Open an issue to discuss enhancements.
2. Fork the repository.
3. Create a branch with your changes: `git checkout -b my-feature`
4. Commit your changes: `git commit -am 'Add my feature'`
5. Push the branch: `git push origin my-feature`
6. Open a Pull Request on GitHub.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
