# iDeaThings UI/UX Color Scheme

## Primary Colors
- Primary: `#9ACD32` (Yellow-Green)
  - This vibrant green from the logo background serves as the primary brand color.
- Primary Dark: `#7BA428` (Darker shade of the primary for hover states)
- Primary Light: `#B8E255` (Lighter shade for backgrounds or accents)

## Secondary Colors
- Secondary: `#FFD700` (Gold)
  - Derived from the yellow in the lightbulb, for call-to-action elements.
- Secondary Dark: `#CCAC00` (Darker gold for hover states)
- Secondary Light: `#FFE147` (Lighter gold for backgrounds or accents)

## Accent Colors
- Accent 1: `#FF4500` (Red-Orange)
  - From the 'i' in the logo, for highlighting or warnings.
- Accent 2: `#1E90FF` (Dodger Blue)
  - From the 'gs' in the logo, for information or links.

## Neutral Colors
- Text Dark: `#333333` (Dark Gray for primary text)
- Text Light: `#FFFFFF` (White for text on dark backgrounds)
- Background: `#F5F5F5` (Light Gray for general backgrounds)
- Border: `#E0E0E0` (Lighter Gray for borders and dividers)

## Semantic Colors
- Success: `#28A745` (Green for positive actions or messages)
- Warning: `#FFA500` (Orange for cautions)
- Error: `#DC3545` (Red for errors or critical actions)
- Info: `#17A2B8` (Blue for informational messages)

## CSS Variables

```css
:root {
  --color-primary: #9ACD32;
  --color-primary-dark: #7BA428;
  --color-primary-light: #B8E255;
  
  --color-secondary: #FFD700;
  --color-secondary-dark: #CCAC00;
  --color-secondary-light: #FFE147;
  
  --color-accent-1: #FF4500;
  --color-accent-2: #1E90FF;
  
  --color-text-dark: #333333;
  --color-text-light: #FFFFFF;
  --color-background: #F5F5F5;
  --color-border: #E0E0E0;
  
  --color-success: #28A745;
  --color-warning: #FFA500;
  --color-error: #DC3545;
  --color-info: #17A2B8;
}
```

Use these CSS variables throughout your stylesheets for consistent theming:

```css
body {
  background-color: var(--color-background);
  color: var(--color-text-dark);
}

.button-primary {
  background-color: var(--color-primary);
  color: var(--color-text-light);
}

.button-primary:hover {
  background-color: var(--color-primary-dark);
}
```
