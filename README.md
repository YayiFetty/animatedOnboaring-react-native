# Animated Onboarding for React Native

This project implements an animated onboarding experience for React Native applications. It features a smooth, paginated introduction with customizable slides, animated progress indicators, and a sleek next button.

## Features

- Smooth horizontal pagination
- Customizable onboarding slides
- Animated dot indicators
- Circular progress next button
- Responsive design adapting to different screen sizes

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js installed
- React Native development environment set up
- Expo CLI (if using Expo)

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/YayiFetty/animatedOnboaring-react-native.git
   ```

2. Navigate to the project directory:
   ```
   cd animatedOnboaring-react-native
   ```

3. Install the dependencies:
   ```
   npm install
   ```

## Usage

1. Import the `Onboarding` component into your main app file.

2. Use the component in your app:
   ```jsx
   import Onboarding from './components/Onboarding';

   function App() {
     return (
       <Onboarding />
     );
   }
   ```

3. Customize the slides by modifying the `slides` array in `utils/slider.js`.

## Components

### Onboarding

The main component that orchestrates the onboarding experience.

### OnboardingItem

Renders individual slide items with image, title, and description.

### Paginator

Displays animated dot indicators to show the current slide position.

### NextButton

A circular button with progress animation to navigate through slides.

## Customization

- Modify the `slides` array in `utils/slider.js` to change the content of the onboarding slides.
- Adjust styles in each component file to match your app's design.

## Contributing

Contributions to improve the animated onboarding experience are welcome. Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request



## Contact

YayiFetty - [@YayiFetty](https://github.com/YayiFetty)

Project Link: [https://github.com/YayiFetty/animatedOnboaring-react-native](https://github.com/YayiFetty/animatedOnboaring-react-native)
