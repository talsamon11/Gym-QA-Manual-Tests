# 🧪 Sample Test Cases

## Overview
These are sample structured manual test cases created to demonstrate formal QA documentation, complementing the exploratory testing performed on the Mad Men Gym website.

---

| Test Case ID | Title                              | Precondition                     | Steps                                                                 | Expected Result                                               | Actual Result                           | Status |
|--------------|------------------------------------|----------------------------------|-----------------------------------------------------------------------|----------------------------------------------------------------|----------------------------------------|--------|
| TC001        | Contact form validation            | User is on 'Contact Us' page     | 1. Leave all fields empty  <br> 2. Click 'Send Message'              | Error messages should appear for required fields              | Redirects to homepage                   | Fail   |
| TC002        | Mobile - Schedule access           | Using Android phone              | 1. Open site on Android device <br> 2. Click 'Training Schedule'     | Subcategories should appear properly                         | Empty window appears                   | Fail   |
| TC003        | Home Page button functionality     | Site is loaded                   | Click on 'Home Page' from menu                                       | Should scroll to top of homepage                              | Nothing happens                         | Fail   |
| TC004        | Registration flow                  | User is on homepage              | 1. Click on Sign Up <br> 2. Fill in valid info <br> 3. Submit       | Account should be created, confirmation shown                  | No registration feature on site        | Fail   |
| TC005        | HTTPS check                        | Open browser                     | Visit site using "https://"                                           | Secure connection should be established                       | Not secured (no HTTPS)                 | Fail   |
| TC006        | Coach profile navigation           | User is on main page             | 1. Click "Coaching Team" <br> 2. Select a coach                      | Coach profile should open with full info                       | Redirects to main page again            | Fail   |
| TC007        | Contact form confirmation          | Fill all required fields         | Submit the form                                                     | Confirmation message or success indicator should appear       | No indication shown                    | Fail   |
| TC008        | Schedule a trial workout (mobile)  | Android/iOS device, site loaded  | Look for 'Schedule a Trial Workout' button on homepage             | Button should be visible and clickable                         | Not visible on mobile version          | Fail   |

---
