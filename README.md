# Accessible Form UI

Project URL: https://roadmap.sh/projects/accessible-form-ui

## Project Overview

In this project, you are required to create a form UI using only HTML and CSS. The form includes fields for a full name, email, password, and confirm password, along with a button to toggle the visibility of the password text.

Additionally, the form features a completeness progress bar and a checklist of requirements that must be met for the form to reach 100% completeness. While this version of the form is not fully functional, it is a static UI component that can be enhanced with JavaScript in the future.

The goal of this project is to practice HTML and CSS while focusing on accessibility so the form is easy to use for all users, including users with disabilities.

## Form Requirements

- Full Name field
- Email field
- Password field
- Confirm Password field
- Show/Hide password button
- Completeness progress bar
- Checklist for requirements toward 100% completeness

## Accessibility Guidelines

When building the form UI, keep these accessibility best practices in mind:

- Labeling: Ensure each form field has a corresponding `<label>` associated using the `for` attribute.
- Focus State: Style the focus state of each input so keyboard users can clearly see the active field.
- Error Messaging: Include space for error messages and associate each message with the relevant field.
- ARIA Attributes: Use ARIA attributes where needed, such as `aria-required` for required fields and `aria-invalid` for invalid fields.
- Color Contrast: Ensure text and background colors meet WCAG contrast recommendations.
- Interactive Elements: Make sure the show/hide password button is keyboard accessible and provides screen reader feedback (for example: "Password is hidden" or "Password is visible").

## Accessibility Testing

After implementation, test the form with:

- A screen reader
- Axe browser extension
- Lighthouse accessibility audit

Then resolve any issues found and re-test.

## Tech Stack

- HTML
- CSS

## Notes

This project currently focuses on static UI and accessibility structure. Behavioral features can be expanded with JavaScript over time.
