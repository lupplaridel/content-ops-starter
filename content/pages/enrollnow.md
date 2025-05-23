---
type: PageLayout
title: Enrollment Form
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: Enrollment Form
      color: text-dark
    subtitle: Secure your child’s slot at Light Up Playhouse!
    text: "We're excited to welcome your little one to a space where learning is joyful, purposeful, and play-based. Please complete the form below to help us get to know your child and match them with the right program. Our team will be in touch within 24–48 hours after submission.\n\nLet’s light up your child’s learning journey together! \U0001F4A1\n"
    actions: []
    media:
      type: FormBlock
      fields:
        - type: TextFormControl
          name: Child's Full Name
          label: Child's Full Name
          hideLabel: true
          placeholder: Child's Full Name
          isRequired: true
          width: full
        - type: TextFormControl
          name: Child’s Birthdate
          label: Child’s Birthdate
          hideLabel: true
          placeholder: Child’s Birthdate
          isRequired: true
          width: full
        - type: TextFormControl
          name: Parent/Guardian Full Name
          label: Parent/Guardian Full Name
          hideLabel: true
          placeholder: Parent/Guardian Full Name
          isRequired: true
          width: full
        - type: TextFormControl
          name: Mobile Number
          label: Mobile Number
          hideLabel: true
          placeholder: Mobile Number
          isRequired: true
          width: full
        - type: EmailFormControl
          name: Email Address
          label: Email Address
          hideLabel: true
          placeholder: Email Address
          isRequired: true
          width: full
        - type: TextFormControl
          name: Facebook Messenger Name
          label: Facebook Messenger Name
          hideLabel: true
          placeholder: Facebook Messenger Name
          isRequired: true
          width: full
        - type: SelectFormControl
          name: Program You're Interested In
          label: Program You're Interested In
          hideLabel: false
          defaultValue: Please choose...
          options:
            - Playgroup (1-5 yo)
            - Kindergarten
            - Enrichment Classes
            - 'Intervention Programs (Speech, ABA, Daily Life Skills)'
          isRequired: true
          width: full
        - type: SelectFormControl
          name: Does your child have a diagnosed developmental concern?
          label: Does your child have a diagnosed developmental concern?
          hideLabel: false
          defaultValue: Please choose...
          options:
            - 'Yes'
            - 'No'
          isRequired: true
          width: full
        - type: TextareaFormControl
          name: Message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          isRequired: false
        - type: SelectFormControl
          name: 'How did you hear about us? '
          label: 'How did you hear about us? '
          hideLabel: false
          defaultValue: Please choose...
          options:
            - Referral
            - Facebook
            - Walk-in
            - Others
          isRequired: false
          width: full
        - type: CheckboxFormControl
          name: Agree
          label: >-
            Submitting this form means you consent to Light Up Playhouse
            contacting you regarding your child’s enrollment.
          isRequired: true
          width: full
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        icon: arrowRight
        iconPosition: right
        style: primary
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
    badge:
      type: Badge
      label: ENROLL NOW
      color: text-primary
    colors: bg-light-fg-dark
slug: enrollnow
isDraft: false
seo:
  type: Seo
  metaTitle: Enroll Now - Light Up Playhouse Plaridel Bulacan Branch
  metaDescription: >-
    Light Up Playhouse is a progressive learning center in Plaridel, Bulacan
    offering early education, intervention programs (Speech, OT, ABA),
    play-based learning, and after-school enrichment for children ages 1-15.
  addTitleSuffix: false
  socialImage: /images/PLAYHOUSE (1600 x 1040 px).jpg
  metaTags: []
---
