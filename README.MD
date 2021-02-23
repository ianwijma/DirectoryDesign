# HeroicGamesLauncher V2.0 document structure suggestion

ATM some items are in nonconventional folders. So I decided to design a new, more organised directory structure.
Below here I will explain each folder and sub folders with why I moved them to there.
To explore the file structure I have added to this repository.

## build

This contains the builded output.

## dist

This contains the compiled output (JS, CSS, Images, etc)

## scripts

This contains all kinds of scripts, like build scripts or development scripts.

## static

This folder contains static files like images, html file or binary files.

## src

This contains editable files like locales, source files and other common editable files.

### src/backend

This folder contains the backend source files. This is the Electron side of the application.

#### src/backend/libs

This folder contains backend libs.

### src/frontend

This folder contains the frontend source files. This is the React side of the application.

#### src/frontend/components

This folder contains the simple components like buttons, modals, inputs etc.

#### src/frontend/contexts

This folder contains React contexts.

#### src/frontend/hooks

This folder contains React hooks.

#### src/frontend/libs

This folder contains frontend libs.

#### src/frontend/pages

This folder contains full screen pages like the library, login and application settings.

## src/common

This folder contains source files that are being used by the backend and frontend. This mainly contains shared types and libs.

## src/locales

This folder contains the locales.
