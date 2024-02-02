# document
# User Management Screen UI Specification

## Overview

This document outlines the specifications for the User Management screen of our web application. The purpose of this screen is to allow users to register on the website and manage their account settings.

## Requirements

1. **User Registration:**
   - Users should be able to register on the website by providing a username, email address, and password.
   - Email validation should be performed to ensure the provided email is valid.

2. **User Account Management:**
   - Users should be able to view and update their account information, including changing their username and password.

3. **User List:**
   - Admin users should have access to a list of all registered users, displaying their usernames and email addresses.

## UI Components

### Registration Form
   - Input fields:
     - Username
     - Email
     - Password
   - Submit button: "Register"

### Account Management Form
   - Display user's current information:
     - Username
     - Email
   - Editable fields:
     - Username
     - Email
     - Password
   - Submit button: "Save Changes"

### User List
   - Table displaying:
     - Username
     - Email

## Page Behavior

1. **User Registration Page:**
   - Display the registration form.
   - Upon successful registration, redirect the user to the login page.
   - Show appropriate error messages for validation failures.

2. **User Account Management Page:**
   - Display the account management form with the user's current information pre-filled.
   - Allow the user to update their information.
   - Show success or error messages upon updating.

3. **User List Page (Admin Only):**
   - Display a list of all registered users.
   - Provide sorting and filtering options.
   - Admin users can click on a user to view and edit their details.

## Initial Display

1. **User Registration Page:**
   - Display the registration form with empty fields.

2. **User Account Management Page:**
   - Display the account management form with the user's current information.

3. **User List Page (Admin Only):**
   - Display a table with usernames and email addresses of registered users.

