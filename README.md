# PixelPioneers
Design System By the People For People
# Repository Structure Guide

This README provides instructions for structuring your repository, where each component has its own folder containing relevant assets and code files. Additionally, a main `README.md` will include links to Figma pages for the overall UI designs.

---

## Folder Structure

```plaintext
repo-root/
|-- components/
|   |-- ComponentName1/
|   |   |-- assets/
|   |   |   |-- ui-preview.png
|   |   |   |-- demo-video.mp4
|   |   |-- ComponentName1.js
|   |   |-- ComponentName1.css
|   |-- ComponentName2/
|       |-- assets/
|       |   |-- ui-preview.png
|       |   |-- demo-video.mp4
|       |-- ComponentName2.js
|       |-- ComponentName2.css
|-- README.md
|-- package.json
|-- .gitignore
```

---

## Instructions for Structuring the Repository

### 1. **Create a `components` Folder**
This folder will hold individual subfolders for each component in your project.

### 2. **Structure Each Component Folder**
Each component folder should include:

- **Assets Folder**: This folder contains:
  - `ui-preview.png` (a screenshot of the component's UI).
  - `demo-video.mp4` (an optional video demonstrating the component in action).

- **Code Files**: Include all relevant code files for the component, such as:
  - `ComponentName.js` (JavaScript/TypeScript code).
  - `ComponentName.css` (styling specific to the component).

Example for a component named `Button`:

```plaintext
components/Button/
|-- assets/
|   |-- ui-preview.png
|   |-- demo-video.mp4
|-- Button.js
|-- Button.css
```

### 3. **Main `README.md`**
# This ReadMe contains link fo the figma page/pages where we shall be pasting the components after designing. 


- **Overview**: Brief description of the project.
- **Figma Links**: The links to Figma designs for pages containing various elements/components will be below.
- Specific contributors can create ReadMe to specific components if it require extra documentation at the folder level.

## Figma Links
Below are the Figma links for the Main pages:

```Will be listed here
- [Homepage](https://figma.com/link-to-homepage)
- [Dashboard Design](https://figma.com/link-to-dashboard)
- [Profile Page Design](https://figma.com/link-to-profile-page)
```

## Components
# Each component has its own folder under the `components/` directory, containing code files and assets like UI previews and videos.
# Stylised components to be created within the same folder i.e `buttons` and `buttons_glassmorphism` within the same `components/buttons`.

### The Components

```Examples of how every component will be listed is shown below.
#### Button Component
- **Location**: `components/Button/`
- **Description**: A reusable button component for various UI actions.
- **Preview**:
  ![Button UI](components/Button/assets/ui-preview.png)

#### Card Component
- **Location**: `components/Card/`
- **Description**: A card component for displaying grouped information.
- **Preview**:
  ![Card UI](components/Card/assets/ui-preview.png)

#### Input Field Component
- **Location**: `components/InputField/`
- **Description**: A text input field with validation.
- **Preview**:
  ![Input Field UI](components/InputField/assets/ui-preview.png)
```

Refer to the `components/` folder for detailed implementations and demos.

## How to Contribute
1. Clone the repository.
2. Create a new branch for your feature or bugfix.
3. Follow the structure guidelines when adding new components.
4. Submit a pull request with a description of your changes.


---

## Additional Notes
- Make sure the asset filenames are consistent (`ui-preview.png` and `demo-video.mp4`).
- Figma links should be up-to-date and accessible to the team.
- Ensure all components are well-documented with inline comments in code files.

---

Follow this structure to keep the repository organized and maintainable!
