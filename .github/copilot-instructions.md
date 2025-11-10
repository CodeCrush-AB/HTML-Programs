# AI Agent Instructions for HTML-Programs

This repository contains HTML experiments demonstrating various web development concepts. Here's what you need to know to work effectively with this codebase:

## Project Structure

- `Experiments/` - Main directory containing numbered experiment folders
  - Each numbered folder (e.g., `6/`, `7/`) represents a distinct learning concept
  - Files within each folder are self-contained examples for that concept

## Key Patterns and Conventions

### Experiment 6: Frame-based Layout
- Uses classic HTML frames for layout structure (`frameset.html` is the entry point)
- Components are split into:
  - `header.html` - Top banner
  - `navigation.html` - Left sidebar navigation
  - `content.html` - Main content area
- Navigation links use `target="content"` to load pages in the content frame

### Experiment 7: CSS Styling Approaches
Demonstrates three CSS implementation methods:
1. Inline CSS (`7.1.html`) - Style attributes directly in HTML elements
2. Internal CSS (`7.2.html`) - Styles in `<style>` tag within `<head>`
3. External CSS (`7.3.html`) - Styles in separate `styles.css` file

## File Organization Conventions
1. Each experiment has a clear objective commented at the top of main files
2. Files are named numerically to indicate progression (e.g., `7.1.html`, `7.2.html`)
3. Shared resources (like `styles.css`) are placed in the experiment's root directory

## Development Guidelines
- Follow the established naming convention for new experiments: `{experimentNumber}/{experimentNumber}.{subNumber}.html`
- Place shared resources (CSS, images) at the experiment folder level
- Include an objective comment at the top of each main HTML file
- Maintain self-contained examples within each experiment folder

## Example Usage
```html
<!-- Example of proper objective documentation -->
<!-- Objective: Write an HTML code to demonstrate the usage of Inline CSS -->
<!DOCTYPE html>
<html>
...
```

Changes and additions should maintain these organizational patterns and documentation standards.