# Cyber-security-password-ch4ecker
 # Password Strength Checker

## Overview
This Python script is a simple command-line tool that allows users to check the strength of their passwords. It evaluates the password based on several criteria, including the presence of lowercase letters, uppercase letters, numbers, whitespace, and special characters. Depending on the strength of the password, the script provides feedback and a recommendation on whether to change it.

## Features
- **Password Input**: The password is entered securely without displaying it on the screen.
- **Strength Evaluation**: The script evaluates the password on five different criteria:
  - Presence of lowercase letters
  - Presence of uppercase letters
  - Presence of numeric digits
  - Presence of whitespace characters
  - Presence of special characters
- **Feedback**: The script provides feedback on the password's strength with a recommendation.
- **User Interaction**: The script allows the user to check multiple passwords in a single session.

## Password Strength Criteria
The script assigns a score to the password based on the following criteria:
- **1 point** for at least one lowercase character
- **1 point** for at least one uppercase character
- **1 point** for at least one numeric digit
- **1 point** for at least one whitespace character
- **1 point** for at least one special character

### Feedback Based on Strength
- **1 point**: "Very Bad Password!!! Change ASAP"
- **2 points**: "Not A Good Password!!! Change ASAP"
- **3 points**: "It's a weak password, consider changing"
- **4 points**: "It's a hard password, but can be better"
- **5 points**: "A very strong password"

## Installation
1. **Clone the repository**: 
   ```sh
   git clone <repository-url>
   cd <repository-directory>

