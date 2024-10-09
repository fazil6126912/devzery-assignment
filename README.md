# Devzery Frontend Technical Assignment: API Chaining Dashboard

## Setup Instructions

To set up the project locally, follow these steps:

1. **Clone the Repository or Download the ZIP File**
   ```bash
   git clone https://github.com/fazil6126912/devzery-assignment.git
   ```
   or extract the downloaded ZIP file.

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Run the Application**
   ```bash
   npm run dev
   ```

4. **View the Live Website**
   Open your browser and navigate to [localhost:5173](http://localhost:5173/).

## Approach Overview

1. **API Workflow Understanding**
   - I began by analyzing the provided APIs using Postman to understand their workflows.

2. **UI Design**
   - After gaining insights into the API functionalities, I designed the user interface utilizing **React.js** and **Tailwind CSS** for a modern look.

3. **API Integration**
   - Axios was employed to handle API calls, with each API having its own custom React hook for efficient management.

## Assumptions and Decisions Made

- Only three specified APIs were provided for this assignment.

## Expected UI

![Expected UI](./public/1.png)

## Completed Features

- **Header Functionality:** The headers are fully operational.
- **API Sequence:** The API sequence is functioning as intended.
- **Get Users API:** Successfully implemented and working.
- **Get Comments API:** Partially implemented.
- **Post Posts API:** Set up for future functionality.
- **Expected Results:** Validated results for **Get Users API** and **Get Comments API** (for `postId=1`).
- **User Interactions:** The UI offers elegant interactions for a smooth user experience.

## Known Issues

- **Responsiveness:** The website is currently not responsive across all device sizes.
- **Post Posts API:** The setup exists, but it is not yet functional.
- **Get Comments API Limitation:** Currently restricted to work only for `postId = 1`.
- **API Chaining Modal:** This feature is in the works and needs to be implemented.

## Video Demo Link

- [Demo Video](https://drive.google.com/file/d/1ZGovi3gp35Av0CJRoJbENb_62Szk_mP9/view?usp=sharing)
