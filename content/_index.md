---
title: "Home"
date: 2023-10-24
type: landing

design:
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Psicologa del Sonno
      text: "La Dott.ssa Vincenza Castronovo è specializzata in disturbi del sonno e CBT-I"
      primary_action:
        text: Scopri la CBT-I
        url: /cbti/
        icon: moon
      secondary_action:
        text: Contattami
        url: /contatti/
      announcement:
        text: "Centro di Medicina del Sonno - Ospedale San Raffaele"
        link:
          text: "Vai al sito"
          url: "[https://www.hsr.it/](https://sonnomed.it/ospedale-san-raffaele-sede-san-raffaele-turro/)"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      css_class: "dark"
      background:
        color: "navy"
        image:
          filename: bg-triangles.svg
          filters:
            brightness: 0.5

  - block: features
    id: features
    content:
      title: Disturbi trattati
      text: Approccio clinico basato sull'evidenza
      items:
        - name: Insonnia cronica
          icon: bed-double
          description: Terapia cognitivo-comportamentale per l'insonnia
        - name: Disturbi circadiani
          icon: clock
          description: Interventi sul ritmo sonno-veglia (es. jet lag, turni)
        - name: Ansia e sonno
          icon: heart
          description: Strategie CBT per migliorare la qualità del sonno
        - name: Sonno e menopausa
          icon: sun
          description: Supporto clinico per difficoltà legate alla menopausa

  - block: cta-image-paragraph
    id: studio
    content:
      items:
        - title: Dove ricevo
          text: Presso il Centro di Medicina del Sonno, Ospedale San Raffaele, Milano
          feature_icon: map
          features:
            - "Valutazione clinica specialistica"
            - "Trattamenti personalizzati"
            - "Ambiente multidisciplinare"
          image: build-website.png
          button:
            text: Prenota un colloquio
            url: /contatti/
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"

  - block: testimonials
    content:
      title: "Cosa dicono pazienti e colleghi"
      items:
        - name: "Nome Cognome"
          role: "Professione o città"
          image: "testimonial-1.jpg"
          text: "Testimonianza generica che valorizza il servizio ricevuto."

  - block: cta-card
    content:
      title: Contatta la Dott.ssa Castronovo
      text: Compila il modulo o scrivi per ricevere informazioni
      button:
        text: Contattami ora
        url: /contatti/
    design:
      card:
        css_class: "bg-primary-700"
---
