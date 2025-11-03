# Multi-Language Support Implementation TODO

## Step 1: Create Translation Files
- [x] Create `locales/` directory
- [x] Create `locales/en.json` with English translations
- [x] Create `locales/hi.json` with Hindi translations

## Step 2: Create Internationalization Script
- [x] Create `js/i18n.js` for language loading, switching, and text replacement

## Step 3: Modify HTML Files
- [x] Update `html/index.html`: Add data-i18n attributes and language selector
- [x] Update `html/menu.html`: Add data-i18n attributes and language selector
- [x] Update translation files with menu-specific keys
- [ ] Update `html/checkout.html`: Add data-i18n attributes and language selector
- [ ] Update `html/aboutUs.html`: Add data-i18n attributes and language selector
- [ ] Update `html/contactUs.html`: Add data-i18n attributes and language selector
- [ ] Update `html/feedback.html`: Add data-i18n attributes and language selector
- [ ] Update `html/forgot-password.html`: Add data-i18n attributes and language selector
- [ ] Update `html/nearbyres.html`: Add data-i18n attributes and language selector
- [ ] Update `html/PartnerWithUs.html`: Add data-i18n attributes and language selector
- [ ] Update `html/signup.html`: Add data-i18n attributes and language selector
- [ ] Update `html/supportCenter.html`: Add data-i18n attributes and language selector

## Step 4: Update JavaScript Files
- [ ] Update `js/app.js`: Replace hardcoded strings with translation keys
- [ ] Update other JS files if needed (e.g., checkout.js, etc.)

## Step 5: Add Language Selector to Navbar
- [ ] Ensure language selector is added to all HTML files' navbars
- [ ] Style the language selector in CSS if necessary

## Step 6: Testing and Followup
- [ ] Test language switching on different pages
- [ ] Verify all text is properly translated and displayed
- [ ] Ensure cart and other functionalities work in both languages
- [ ] Check localStorage persistence of language preference
