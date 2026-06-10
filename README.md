# Restful-Booker API Automation Framework 🚀

[![Postman API Testing CI](https://github.com/SahanRathnaweera/restful-booker-postman-automation/actions/workflows/postman-ci.yml/badge.svg)](https://github.com/SahanRathnaweera/restful-booker-postman-automation/actions/workflows/postman-ci.yml)


This repository contains a fully automated API testing framework built using Postman and JavaScript for the Restful-Booker platform.

## 🛠️ Tech Stack & Tools
- Tool: Postman
- Scripting Language: JavaScript (ES6)
- Assertion Library: Chai Assertion Library (Built-in Postman)
- Validation tool: tv4 (Tiny Validator for JSON Schema)

## 🔍 Features & Test Coverage
- Token Generation (Auth): Handles automated authentication token generation and injection.
- Dynamic Variable Sharing: Automatically captures `booking_id` and tokens from responses and shares them across subsequent requests.
- Positive & Negative Testing: Validates successful scenarios as well as missing fields (handling 500/400 errors).
- Advanced Data Validation: Verifies precise response objects, correct status codes, data values, and data types.
- Schema Validation: Ensures the response structure adheres strictly to the required data models.

## 🏃‍♂️ How to Run the Project
1. Clone or download the files in this repository.
2. Open Postman.
3. Click on Import and select the exported Collection and Environment JSON files.
4. Select the `Restful-Booker-Staging` environment.
5. Open the Collection Runner and click Run Restful-Booker Framework.
