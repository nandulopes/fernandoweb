---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Postdoctoral Researcher
          company: Laboratory of Evolutionary Genomics, State University of Campinas
          company_url: 'https://unicamp.br/en/'
          company_logo: UNICAMP
          location: Campinas, Brazil
          date_start: '2024-10-01'
          date_end: ''
          description: |2-
              Responsibilities:

              * Genomic Analyses of fur seals from South America
              * Population Genomics
              * Wet-lab protocols
              * Manuscript writting
              * Project Management
              * Supervision
    
        - title: Postdoctoral Researcher
          company: Finnish Museum of Natural History, University of Helsinki
          company_url: 'https://www.luomus.fi/en'
          company_logo: uh
          location: Helsinki, Finalnd
          date_start: '2022-01-24'
          date_end: '2024-08-31'
          description: |2-
              Responsibilities:

              * Genomic Analyses (Shotgun, UCE, aDNA & Metagenomics)
              * Molecular Systematics
              * Wet-lab protocols
              * Manuscript writting
              * Project Management
              * Supervision

        - title: Technical Support
          company: Pontifical Catholic University of Rio Grande do Sul
          company_url: 'https://www.pucrs.br/en/'
          company_logo: pucrs
          location: Porto Alegre, Brazil
          date_start: '2020-04-01'
          date_end: '2021-09-30'
          description: |2-
              Responsibilities:

              * Genomic Analyses (WGS & RADseq)
              * Phylogenomics
              * Population Genomics
              * Manuscript writting
              * Mentorship

        - title: Technical Support
          company: University of Vale do Rio dos Sinos
          company_url: 'https://www.unisinos.br'
          company_logo: uni
          location: São Leopoldo, Brazil
          date_start: '2019-10-01'
          date_end: '2020-03-31'
          description: |2-
              Responsibilities:

              * Phylogenetics
              * DNA Barcoding analyses
              * Population Genetics/Genomics
              * Manuscript writting

        - title: Ph.D. Ecology, Evolution & Biodiversity
          company: Pontifical Catholic University of Rio Grande do Sul
          company_url: 'https://www.pucrs.br/en/'
          company_logo: pucrs
          location: Porto Alegre, Brazil
          date_start: '2019-10-01'
          date_end: '2020-03-31'
          description: |2-
              Ph.D. Thesis:
              Phylogenomics of Otariidae and evolutinary history of fur seals of South America

        - title: Master's degree Zoology
          company: Pontifical Catholic University of Rio Grande do Sul
          company_url: 'https://www.pucrs.br/en/'
          company_logo: pucrs
          location: Porto Alegre, Brazil
          date_start: '2013-03-01'
          date_end: '2015-02-28'
          description: |2-
              Master's Thesis:
              Genetic diversity and population structure of the Galapagos fur seal, Arctocephalus galapagoensis
     
        - title: Bachelor degree Biological Sciences
          company: University of Vale do Rio dos Sinos
          company_url: 'https://www.unisinos.br'
          company_logo: uni
          location: São Leopoldo, Brazil
          date_start: '2006-03-01'
          date_end: '2012-12-31'
          description: |2-

 
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Prizes & Awards'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url:
          date_end: '2023-01-01'
          date_start: '2016-09-01'
          description: |2-
              2023: The São Paulo Research Foundation, Brazil - Postdoctoral Fellowship Grant <br>
              2023: ULAM-NAWA Programme, Poland - Postdoctoral Fellowship Grant (declined) <br>
              2020: Society for Marine Mammalogy - Small Grants in Aid of Research <br>
              2017: Society for Conservation Biology - Conservation Research Small Grants Program <br>
              2016: Society for Marine Mammalogy - Small Grants in Aid of Research 
          organization: 
          organization_url:
          title: Grants
          url:
        - certificate_url:
          date_end: '2023-01-01'
          date_start: '2012-09-01'
          description: |2-
              2018: International Conference: Best Oral Presentation - Robin Best Award, 12º SOLAMAC, Lima - Peru <br>
              2012: Approved with distinction - undergraduate dissertation, UNISINOS, São Leopoldo - Brazil <br>
              2012: Honorable Mention II Undergraduate Research and Post-graduate Conference & XIX Fair of Undergraduate Research, UNISINOS, São Leopoldo - Brazil
          organization: 
          organization_url:
          title: Awards
          url:
        - certificate_url:
          date_end: '2017-12-31'
          date_start: '2006-03-01'
          description: |2-
              2017: Sandwich Ph.D. in a host institution (Ludwig Maximilian University of Munich - Munich, Germany). Funding: Ministry of Education of Brazil - CAPES <br>
              2015: Ph.D. thesis Scholarship. Funding: Ministry of Education of Brazil - CAPES <br>
              2013: Master's degree Scholarship. First place in the selective process to perform a master’s degree dissertation. Funding: Ministry of Science and Technology of Brazil - CNPq <br>
              2006: PROUNI - Universidade para todos program. Scholarship to cover the course of Biological Sciences. Funding: Ministry of Education of Brazil 
          organization: 
          organization_url:
          title: Scholarships
          url:
    design:
      columns: '2'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Selected Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: features
    content:
      title: Skills
      items:
        - name: Field work
          #description: 100%
          icon: mountain
          icon_pack: fas
        - name: Wet-lab
          #description: 90%
          icon: dna
          icon_pack: fas
        - name: Genomic Analyses
          #description: 100%
          icon: computer
          icon_pack: fas
        - name: Maps
          #description: 100%
          icon: map
          icon_pack: fas 
        - name: Scientific writing
          #description: 100%
          icon: pen
          icon_pack: fas
        - name: Mentorship
          #description: 100%
          icon: person-chalkboard
          icon_pack: fas
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact me!
      subtitle:
      text: |-
        I will be happy to answer you!
      # Contact (add or remove contact options as necessary)
      email: lopesf@unicamp.br
      address:
        street: Rua Monteiro Lobato, 255
        city: Campinas - Brazil
        postcode: '13083-862'
        region: São Paulo
        country: Brazil
        country_code: BR
      coordinates:
        latitude: '-22.819543'
        longitude: '-47.06810'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/fernandorvlopes'
    design:
      columns: '2'    
---
