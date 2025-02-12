---
type: PageLayout
title: Home
colors: colors-b
sections:
  - elementId: ''
    colors: colors-b
    backgroundSize: full
    title: ROCH ANTHONY
    subtitle: ''
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
    text: >+
      Ancien routier, j'ai acquis rigueur, gestion du stress et autonomie.


      Passionné d'informatique, j'ai obtenu un diplôme TSSR pour maîtriser les
      systèmes et réseaux.


      Désireux de renforcer mes compétences, j'ai entamé une formation
      Administrateur d'Infrastructures 


      Sécurisées (AIS) afin de me spécialiser en cybersécurité et répondre aux
      enjeux de la sécurité informatique.
          



  - type: LabelsSection
    title: COMPÉTENCES INFORMATIQUES
    subtitle: ''
    items:
      - type: Label
        label: Administration des systèmes
        url: ''
      - type: Label
        label: Label title
        url: ''
      - type: Label
        label: Gestion des réseaux
        url: ''
      - type: Label
        label: Sécurité informatique
        url: ''
      - type: Label
        label: Virtualisation et Cloud
        url: ''
      - type: Label
        label: Supervision et Maintenance
        url: ''
      - type: Label
        label: Développement et automatisation
        url: ''
    colors: colors-f
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - type: ContactSection
    title: Contact Me
    text: I'm look forward to hearing from you.
    form:
      type: FormBlock
      title: Title of the form
      fields:
        - type: TextFormControl
          name: name
          label: name
          hideLabel: true
          placeholder: Votre nom
          width: 1/2
          isRequired: 'true'
        - type: EmailFormControl
          name: email
          label: Name
          hideLabel: true
          placeholder: email
          width: 1/2
          isRequired: 'true'
        - type: TextareaFormControl
          name: message
          label: Tell me about your project
          hideLabel: true
          placeholder: 'Dites m''en plus '
          width: full
          isRequired: true
        - type: CheckboxFormControl
          name: updates
          label: Coche pour recevoir les mises a jours
          width: full
          isRequired: 'false'
      submitLabel: Envoie du message
      elementId: contact-form
      styles:
        submitLabel:
          textAlign: left
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: center
      text:
        textAlign: center
---
