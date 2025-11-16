# Starter Stylesheet

A comprehensive CSS starter kit with modern styling patterns, CSS custom properties, and ready-to-use components for rapid web development.

## Features

### Typography System
- **Google Fonts Integration**: Poppins, Raleway, Playfair Display, and Outfit
- **Font Variables**: Organized font family variables for consistent typography
- **Responsive Typography**: Scalable font sizes using rem units
- **Semantic Heading Styles**: h1-h3 with proper hierarchy and spacing

#### Typography Variables

| Variable | Value | Description |
|----------|-------|-------------|
| `--font-playfair-display` | `'Playfair Display', serif` | Display font for headings |
| `--font-georgia` | `Georgia, 'Times New Roman', Times, serif` | Body text font |
| `--font-raleway` | `'Raleway', sans-serif` | UI elements font |
| `--font-poppins` | `'Poppins', sans-serif` | Alternative sans-serif |
| `--font-outfit` | `'Outfit', sans-serif` | Modern sans-serif |

### Color System
- **Comprehensive Color Palette**: 
  - Grayscale variations (gray-100 to gray-300)
  - Orange accent colors (orange-100 to orange-300)
  - Blue variations (blue-100 to blue-300)
  - Purple variations (purple-100 to purple-300)
- **Semantic Colors**: Error, success, and warning states
- **CSS Custom Properties**: Easy theming and customization

#### Color Variables

| Variable | Value | Description |
|----------|-------|-------------|
| `--white` | `#FFFFFF` | Pure white |
| `--black` | `#000000` | Pure black |
| `--gray-100` | `#EAECEF` | Light gray |
| `--gray-200` | `#3E4147` | Medium gray |
| `--gray-300` | `#161819` | Dark gray |
| `--orange-100` | `#E36E40` | Light orange |
| `--orange-200` | `#CC4425` | Medium orange |
| `--orange-300` | `#9E2E15` | Dark orange |
| `--blue-100` | `#8EF2FF` | Light blue |
| `--blue-200` | `#407899` | Medium blue |
| `--blue-300` | `#204051` | Dark blue |
| `--purple-100` | `#9B7AA0` | Light purple |
| `--purple-200` | `#694D75` | Medium purple |
| `--purple-300` | `#4B3652` | Dark purple |
| `--error` | `#DC3545` | Error red |
| `--success` | `#28A745` | Success green |
| `--warning` | `#FFC107` | Warning yellow |
| `--accent` | `rgba(0, 214, 170, 0.8)` | Primary accent color |

#### Color Variables

| Variable | Value | Description |
|----------|-------|-----------|
| `--white` | `#FFFFFF` | Pure white |
| `--black` | `#000000` | Pure black |
| `--gray-100` | `#EAECEF` | Light gray |
| `--gray-200` | `#3E4147` | Medium gray |
| `--gray-300` | `#161819` | Dark gray |
| `--orange-100` | `#E36E40` | Light orange |
| `--orange-200` | `#CC4425` | Medium orange |
| `--orange-300` | `#9E2E15` | Dark orange |
| `--blue-100` | `#8EF2FF` | Light blue |
| `--blue-200` | `#407899` | Medium blue |
| `--blue-300` | `#204051` | Dark blue |
| `--purple-100` | `#9B7AA0` | Light purple |
| `--purple-200` | `#694D75` | Medium purple |
| `--purple-300` | `#4B3652` | Dark purple |
| `--error` | `#DC3545` | Error red |
| `--success` | `#28A745` | Success green |
| `--warning` | `#FFC107` | Warning yellow |
| `--accent` | `rgba(0, 214, 170, 0.8)` | Primary accent color |

### Components

#### Navigation
- **Responsive Header**: Clean header with accent background
- **Logo Component**: Interactive logo with hover effects
- **Navigation Menu**: Uppercase styling with hover animations
- **Link Animations**: Smooth underline effects on hover

#### Buttons
- **Base Button Styles**: Consistent padding and typography
- **Button Variants**:
  - `.btn-orange`: Solid orange button
  - `.btn-orange-outline`: Outlined orange button
- **Interactive States**: Smooth hover transitions
- **Button Container**: `.buttons-place` for proper spacing

#### Forms
- **Styled Inputs**: Clean input and select styling
- **Focus States**: Blue outline on focus
- **Error States**: Red outline for validation errors
- **Form Layout**: `.form-item` for consistent form structure
- **Validation Messages**: `.validation-error` for error display

#### Layout
- **Container System**: Responsive container with max-width and centering
- **Box Model Reset**: Universal box-sizing reset
- **Consistent Spacing**: Standardized padding and margins

## Usage

### Basic Implementation

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="starter-styles.css">
</head>
<body>
    <header>
        <div class="logo">Your Logo</div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <div class="container">
        <h1>Main Heading</h1>
        <p>Your content here...</p>
        
        <div class="buttons-place">
            <button class="btn btn-orange">Primary Action</button>
            <button class="btn btn-orange-outline">Secondary Action</button>
        </div>
    </div>
</body>
</html>
```

### Form Example

```html
<form>
    <div class="form-item">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name">
    </div>
    <div class="validation-error">Please enter a valid name</div>
    
    <div class="form-item">
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" class="error">
    </div>
</form>
```

## Development

The starter includes both CSS and SCSS versions:
- **CSS Version**: Ready to use, includes CSS custom properties
- **SCSS Version**: Advanced features with variables, mixins, and nesting

## Contributing

Feel free to submit issues and enhancement requests!
