# Dynamic Partner Logo Carousel (Vue 3)

This Vue 3 component creates an engaging, responsive carousel to showcase partner logos. It's designed to display multiple columns of vertically scrolling logos, creating a dynamic and visually appealing presentation of trusted partners.

## Preview

![Sample Preview](https://github.com/AroshaRavishan/Vertical-logo-slider-Vue3/blob/main/sample%20preview.png?raw=true)


## Features

- **Responsive Design**: Adapts to different screen sizes, showing up to 4 columns on larger screens and fewer on smaller devices.
- **Vertical Scrolling**: Each column is a vertical carousel, creating a unique scrolling effect.
- **Dynamic Reshuffling**: Partner logos are randomly shuffled every 30 seconds, ensuring equal visibility for all partners.
- **Smooth Animations**: Utilizes Splide.js for smooth, continuous scrolling effects.
- **Customizable Speed**: Each column has a slightly different scrolling speed, creating an interesting visual rhythm.

## Component Structure

1. **Partner Data**: Includes a list of 22 partner logos with their image URLs and alt text.
2. **Splide Integration**: Uses the Splide library for creating the carousel effect.
3. **Responsive Columns**: Implements a grid layout that adjusts based on screen size.
4. **Dynamic Grouping**: Shuffles and groups partner logos for display in different columns.

## Functionality

- **Logo Shuffling**: Partners are randomly grouped and reshuffled periodically.
- **Interval Offsets**: Each column starts its animation at a slightly different time for visual variety.
- **Continuous Loop**: The carousel runs in a continuous loop for uninterrupted display.
- **Automatic Playback**: Logos scroll automatically without user interaction.

## Styling

- Tailwind CSS classes for responsive design and layout.
- Custom container and padding for optimal presentation.
- Consistent logo height for uniformity.

## Usage

This component is designed to be part of a larger Vue 3 application. To use:

1. Import the component into your Vue 3 project.
2. Ensure Splide.js and its CSS are properly imported.
3. Customize the partner list and scrolling options as needed.
4. Place the component within your desired section of the application.

Note: This component requires the Splide library and its CSS to function properly.

## Customization

- Easily modify the `partners` array to update the list of displayed logos.
- Adjust `splideOptions` to change scrolling behavior, speed, and other carousel properties.
- Modify the reshuffling interval (currently set to 30 seconds) to change how often logos are regrouped.
