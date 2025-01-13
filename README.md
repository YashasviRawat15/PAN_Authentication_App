# React Native PAN Card Authentication

This project is a React Native application that implements **Login** and **Registration** screens with **PAN Card authentication**. The app provides options for scanning or uploading PAN cards, extracting user details for seamless onboarding.

---

## Table of Contents

1. [Overview](#overview)  
2. [Features](#features)  
3. [Setup and Installation](#setup-and-installation)  
4. [Usage](#usage)  
5. [Technical Approach](#technical-approach)  
6. [Error Handling and Validation](#error-handling-and-validation)  
7. [Contributing](#contributing)  
8. [License](#license)  

---

## Overview

The **React Native PAN Card Authentication** app simplifies user onboarding by enabling PAN card scanning or image upload. The app extracts PAN details automatically, ensuring quick and accurate registration while minimizing manual input.

---

## Features

- **Registration with PAN Card Authentication**:
  - **Scan PAN Card**:
    - Live viewfinder with a rectangle bar for alignment.
    - Automatic extraction of details (e.g., PAN number, name).
  - **Upload PAN Image**:
    - Supports JPEG, PNG, and PDF formats.
    - Extracts PAN details from uploaded files.
  - Validation for password, email, mobile number, and address.
  
- **Error Handling**:
  - Real-time feedback for invalid inputs and errors.

- **Login Functionality**:
  - Users can log in with their registered PAN details and password.

- **User Feedback**:
  - Progress indicators for PAN verification.
  - Success messages on successful registration and login.

---

## Setup and Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Gapur/react-native-scanner.git
   cd react-native-scanner
