# Menu Example with Glow Effects

## Overview
This project creates a customizable navigation menu with hover and active state effects, featuring a glowing light beam and shadow effect for each icon. The menu is designed with a modern dark theme and includes five icons: home, heart, plus, user, and bell. Each icon glows in a unique color when hovered over or activated.

## Features
- Responsive navigation bar with a curved design.
- Hover and click (active) states trigger a glowing effect with a rectangular light source and a shadow-like beam.
- Unique colors for each icon's glow effect:
  - Home: Skyblue (`#87CEEB`)
  - Heart: Red (`#FF0000`)
  - Plus: Light Green (`#90EE90`)
  - User: Pink (`#FF69B4`)
  - Bell: Yellow (`#FFFF00`)
- Smooth transitions for all glow effects.

## Technologies Used
- **HTML**: Structure of the navigation menu.
- **CSS**: Styling, including flexbox for layout, gradients for glow effects, and transitions for interactivity.
- **JavaScript**: Handles click events to set the active state.
- **Font Awesome**: Provides the icons.

## Installation
1. Clone the repository from [GitHub](https://github.com/isgameliel/glowing-menu) or copy the code into a new directory.
2. Ensure you have a web browser to view the output.
3. Open the `index.html` file in a browser.

## Preview
Check out the live preview of the menu at [https://isgameliel.github.io/glowing-menu/](https://isgameliel.github.io/glowing-menu/).

## Usage
- Hover over any icon to see the glow effect in its respective color.
- Click an icon to set it as the active state, which maintains the glow effect.
- The second icon (heart) is set as active by default.

## Output Description
The output is a horizontal navigation bar centered on a dark background. Here’s a textual representation of the expected visual:

### Default State
- A dark gray bar (`#2a2a2a`) with a slight shadow, 300px wide and 60px high, with rounded edges.
- Five icons (home, heart, plus, user, bell) in gray (`#666`) are evenly spaced.
- No glow effects are visible until hover or active.

### Hover/Active State (Per Icon)
- **Home (1st Icon)**:
  - Icon turns skyblue (`#87CEEB`).
  - A thin skyblue rectangular light (`#87CEEB`) appears above the icon.
  - A soft skyblue shadow beam extends downward from the light, fading to transparent.
  - A subtle skyblue radial glow surrounds the icon.
- **Heart (2nd Icon)**:
  - Icon turns red (`#FF0000`).
  - A thin red rectangular light (`#FF0000`) appears above the icon.
  - A soft red shadow beam extends downward from the light, fading to transparent.
  - A subtle red radial glow surrounds the icon (active by default).
- **Plus (3rd Icon)**:
  - Icon turns light green (`#90EE90`).
  - A thin light green rectangular light (`#90EE90`) appears above the icon.
  - A soft light green shadow beam extends downward from the light, fading to transparent.
  - A subtle light green radial glow surrounds the icon.
- **User (4th Icon)**:
  - Icon turns pink (`#FF69B4`).
  - A thin pink rectangular light (`#FF69B4`) appears above the icon.
  - A soft pink shadow beam extends downward from the light, fading to transparent.
  - A subtle pink radial glow surrounds the icon.
- **Bell (5th Icon)**:
  - Icon turns yellow (`#FFFF00`).
  - A thin yellow rectangular light (`#FFFF00`) appears above the icon.
  - A soft yellow shadow beam extends downward from the light, fading to transparent.
  - A subtle yellow radial glow surrounds the icon.

### Visual Layout

- Each icon is 40px wide, with a 25px wide light rectangle and a 20px wide shadow beam extending 30px downward.
- The glow effect is blurred (5px) for a soft shadow appearance.

## Code Structure
- `index.html`: Contains the HTML structure with `nav` and `nav-link` elements.
- `<style>`: Defines the CSS for layout, colors, and effects.
- `<script>`: JavaScript to manage the active state on click.
- GitHub Repository: [https://github.com/isgameliel/glowing-menu](https://github.com/isgameliel/glowing-menu)

## Future Improvements
- Add animation for the glow effect to enhance interactivity.
- Make the menu responsive for mobile devices.
- Allow color customization via a configuration file or user input.

## License
This project is open-source and available under the MIT License.

## Acknowledgments
- Icons provided by Font Awesome.
- Inspiration from modern UI design trends.
- Designed by codewitheugene.