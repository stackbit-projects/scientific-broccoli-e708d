---
title: Contact
sections:
- type: section_contact
  template: section_contact
  section_id: contact
  title: I hope we can keep in touch :)
  content: 'I''m looking for new opportunities! If you are interested in my works
    or blog posts, please contact me at [kangyeon.lee.alicia@gmail.com](mailto:example@example.com)

'
  background: white
  form_id: contactForm
  form_fields:
  - type: form_field
    template: form_field
    input_type: text
    name: name
    label: NAME
    is_required: true
    default_value: Your name
    options: []
  - type: form_field
    template: form_field
    input_type: email
    name: email
    label: EMAIL
    is_required: true
    default_value: Your email
    options: []
  - type: form_field
    template: form_field
    input_type: text
    name: subject
    label: SUBJECT
    default_value: Your subject
    options:
    - Error on the site
    - Sponsorship
    - Other
    is_required: false
  - type: form_field
    template: form_field
    input_type: textarea
    name: message
    label: MESSAGE
    default_value: Your message
    options: []
    is_required: false
  submit_label: Send Message to Gangyeon!
  subtitle: ''
  form_action: "/thank-you"
  hide_labels: false
seo:
  type: stackbit_page_meta
  template: stackbit_page_meta
  title: Contact
  description: This is the contact page
  extra:
  - name: og:type
    value: website
    keyName: property
    relativeUrl: false
  - name: og:title
    value: Contact
    keyName: property
    relativeUrl: false
  - name: og:description
    value: This is the contact page
    keyName: property
    relativeUrl: false
  - name: twitter:card
    value: summary_large_image
    keyName: ''
    relativeUrl: false
  - name: twitter:title
    value: Contact
    keyName: ''
    relativeUrl: false
  - name: twitter:description
    value: This is the contact page
    keyName: ''
    relativeUrl: false
  robots: []
template: landing

---
