# Testing

> [!NOTE]
> Return back to the [README.md](README.md) file.

---

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files using the deployed URLs.

| File                | URL                                                                                      | Screenshot                                                            | Notes           |
| ------------------- | ---------------------------------------------------------------------------------------- | --------------------------------------------------------------------- | --------------- |
| 404.html            | https://validator.w3.org/nu/?doc=https://raigonlab.github.io/sky-fly/404.html            | ![404 validation](documentation/testing/404-testing.png)             | No major errors |
| contact.html        | https://validator.w3.org/nu/?doc=https://raigonlab.github.io/sky-fly/contact.html        | ![contact validation](documentation/testing/contact-testing.png)     | No major errors |
| fly-experience.html | https://validator.w3.org/nu/?doc=https://raigonlab.github.io/sky-fly/fly-experience.html | ![fly validation](documentation/testing/about-good-testing.png)  | No major errors |
| gallery.html        | https://validator.w3.org/nu/?doc=https://raigonlab.github.io/sky-fly/gallery.html        | ![gallery validation](documentation/testing/gallery-testing.png)     | No major errors |
| index.html          | https://validator.w3.org/nu/?doc=https://raigonlab.github.io/sky-fly/index.html          | ![index validation](documentation/testing/home-testing.png)         | No major errors |
| thank-you.html      | https://validator.w3.org/nu/?doc=https://raigonlab.github.io/sky-fly/thank-you.html      | ![thank you validation](documentation/testing/thank-you-testing.png) | No major errors |

---

### CSS

I have used the recommended [CSS Jigsaw Validator](documentation/testing/css-testing.png) to validate my CSS file.

| File      | URL                                                                                   | Screenshot                                                       | Notes                                         |
| --------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | --------------------------------------------- |
| style.css | https://jigsaw.w3.org/css-validator/validator | ![css validation](documentation/testing/css-testing.png) | Minor warnings related to Bootstrap (ignored) |

---

## Responsiveness

The project was tested across multiple screen sizes using browser developer tools and real device simulation.

| Page      | Mobile                                                       | Tablet                                                       | Desktop                                                        | Notes                 |
| --------- | ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------------------------------------------------- | --------------------- |
| Home      | ![mobile](documentation/responsiveness/mobile-home.png)      | ![tablet](documentation/responsiveness/tablet-home.png)      | ![desktop](documentation/responsiveness/desktop-home.png)
| Fly Experience      | ![mobile](documentation/responsiveness/mobile-fly-experience.png)      | ![tablet](documentation/responsiveness/tablet-fly-experience.png)      | ![desktop](documentation/responsiveness/desktop-fly-experience.png)      | Works as expected     |
| Gallery   | ![mobile](documentation/responsiveness/mobile-gallery.png)   | ![tablet](documentation/responsiveness/tablet-gallery.png)   | ![desktop](documentation/responsiveness/desktop-gallery.png)   | Grid adapts correctly |
| Contact   | ![mobile](documentation/responsiveness/mobile-contact.png)   | ![tablet](documentation/responsiveness/tablet-contact.png)   | ![desktop](documentation/responsiveness/desktop-contact.png)   | Form remains usable   |
| Thank You | ![mobile](documentation/responsiveness/mobile-thank-you.png) | ![tablet](documentation/responsiveness/tablet-thank-you.png) | ![desktop](documentation/responsiveness/desktop-thank-you.png) | Layout consistent     |
| 404       | ![mobile](documentation/responsiveness/mobile-404.png)       | ![tablet](documentation/responsiveness/tablet-404.png)       | ![desktop](documentation/responsiveness/desktop-404.png)       | Clear error message   |

---

## Browser Compatibility

The project was tested across major browsers.

| Page    | Chrome                                               | Firefox                                                | Safari                                               | Notes           |
| ------- | ---------------------------------------------------- | ------------------------------------------------------ | ---------------------------------------------------- | --------------- |
| Home    | ![chrome](documentation/browsers/chrome-home.png)    | ![firefox](documentation/browsers/firefox-home.png)    | ![safari](documentation/browsers/safari-home.png)    | Works correctly |
| Gallery | ![chrome](documentation/browsers/chrome-gallery.png) | ![firefox](documentation/browsers/firefox-gallery.png) | ![safari](documentation/browsers/safari-gallery.png) | No issues       |
| Contact | ![chrome](documentation/browsers/chrome-contact.png) | ![firefox](documentation/browsers/firefox-contact.png) | ![safari](documentation/browsers/safari-contact.png) | Form works      |
| 404     | ![chrome](documentation/browsers/chrome-404.png)     | ![firefox](documentation/browsers/firefox-404.png)     | ![safari](documentation/browsers/safari-404.png)     | Works correctly |

---

## Lighthouse Audit

Lighthouse audits were performed on all pages.

| Page    | Mobile                                                 | Desktop                                                  |
| ------- | ------------------------------------------------------ | -------------------------------------------------------- |
| Home    | ![mobile](documentation/lighthouse/mobile-home.png)    | ![desktop](documentation/lighthouse/desktop-home.png)    |
| Gallery | ![mobile](documentation/lighthouse/mobile-gallery.png) | ![desktop](documentation/lighthouse/desktop-gallery.png) |
| Contact | ![mobile](documentation/lighthouse/mobile-contact.png) | ![desktop](documentation/lighthouse/desktop-contact.png) |
| 404     | ![mobile](documentation/lighthouse/mobile-404.png)     | ![desktop](documentation/lighthouse/desktop-404.png)     |

---

## Defensive Programming

Manual testing was conducted to ensure correct user interactions.

| Page       | Expectation                         | Test                        | Result                 |
| ---------- | ----------------------------------- | --------------------------- | ---------------------- |
| Contact    | Form should not submit empty fields | Tried submitting empty form | Blocked successfully   |
| Contact    | Email must be valid                 | Inserted invalid email      | Validation triggered   |
| Navigation | Links should work                   | Clicked all links           | All working            |
| Gallery    | Images should display correctly     | Tested resizing             | Responsive and correct |
| 404        | Invalid URL should show error page  | Accessed random URL         | 404 page displayed     |

---

## User Story Testing

| Target | Expectation           | Outcome                   |
| ------ | --------------------- | ------------------------- |
| User   | Understand experience | Clear content provided    |
| User   | View gallery          | Images displayed properly |
| User   | Contact easily        | Form accessible           |
| User   | Responsive design     | Works on all devices      |
| User   | Error handling        | 404 works                 |

---

## Bugs

### Fixed Bugs

* Navbar collapsing issue on mobile → fixed with Bootstrap classes
* Image stretching in gallery → fixed with CSS grid adjustments
* Prettier formatting issues → manually corrected

---

### Unfixed Bugs

There are no known unfixed bugs at the time of submission.

---

### Known Issues

| Issue                                   | Notes                                     |
| --------------------------------------- | ----------------------------------------- |
| Minor Lighthouse performance variations | Due to image sizes and external libraries |
| Bootstrap validation warnings           | Not related to custom code                |

---

> [!IMPORTANT]
> No critical issues remain after testing.
