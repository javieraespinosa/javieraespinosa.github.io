---
# Leave the homepage title empty to use the site title
title: 'About'
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:



  - block: markdown
    id: about
    content:
      title: 'About me'
      subtitle: ''
      text: |-
        I am a *Maître de Conférences* (Associate Professor with tenure) in the Department of Informatics at [Université Claude Bernard Lyon&nbsp;1](https://www.univ-lyon1.fr), and a member of the Information Systems group at the [ERIC](https://eric.univ-lyon2.fr) research laboratory.

        Prior to joining Lyon 1, I was a Lecturer–Researcher at [CPE Lyon](https://www.cpe.fr), a French *Grande École* of engineering, and a member of the Database Group at the [LIRIS](https://liris.cnrs.fr/) CNRS laboratory.

        I have held research positions at the Barcelona Supercomputing Center ([BSC](http://bsc.es)), Delft University of Technology ([TU Delft](http://tudelft.nl)), the CONACyT–CNRS French–Mexican Laboratory of Informatics and Automatic Control ([LAFMIA](http://lafmia.imag.fr/)), and the Computer Science Laboratory of Grenoble ([LIG](https://www.liglab.fr)). 

        I received my PhD in Computer Science from [Université Grenoble Alpes](https://www.univ-grenoble-alpes.fr) and hold both an MSc and a BS in Computer Science and Computer Systems Engineering from [Universidad de las Américas Puebla](https://www.udlap.mx).

        My research lies at the intersection of databases and distributed systems, with a focus on designing scalable, efficient, and robust data management solutions.
    design:
      columns: '1'



  - block: hero
    content:
      title: ""
      text: ""
    design:
      background:
        image:
          filename: tampere.jpeg      
          parallax: false
          size: contain        # cover | contain | 32px | etc.
          position: center   # center | top | repeat          
          filters:
            brightness: 1.4
            grayscale: 1
        text_color_light: true



  # - block: markdown
  #   id: teaching
  #   content:
  #     title: 'Teaching'
  #     subtitle: ''
  #     text: |-
  #       |   |    |    |    |
  #       |----|----|----|----|
  #       `2026` | ⭐️[Cloud Computing](http://espinosa-oviedo.com/cloud-cci/)	| M2 CCI	| Univ. Lyon 1 | 
  #       `2026` | ⭐️Cloud, Storage & Virtualization	| M2 TIW	| Univ. Lyon 1 | 
  #       `2025` | [Big Data Engineering](https://espinosa-oviedo.com/big-data/)	| M2 TIW	| Univ. Lyon 1 | 
  #       `2025` | [Service & Cloud Computing](https://espinosa-oviedo.com/cloud/)	| M2 DISS	| Univ. Lyon 1 | 


  #       <div class="container mx-auto max-w-screen-lg px-8 xl:px-5 pb-5 lg:pb-8">
  #         <div class="mt-10 flex justify-center">
  #           <a class="relative inline-flex items-center gap-1 rounded-md border border-gray-300 bg-white px-3 py-2 pl-4 text-sm font-medium text-gray-500 hover:bg-gray-50 focus:z-20 dark:border-gray-500 dark:bg-gray-800 dark:text-gray-300" href="/courses/">
  #               <span>See past courses</span>
  #           </a>
  #         </div>
  #       </div>
  #   design:
  #     columns: '1'







  # - block: markdown
  #   id: publications
  #   content:
  #     title: 'Publications'
  #     subtitle: ''
  #     text: |-
  #       Available in my digital footprint: 
  #       * [Google Scholar](https://scholar.google.com/citations?user=RkXsr4YAAAAJ&amp;hl=en)
  #       * [DBLP](https://dblp.org/pid/11/1137)
  #       * [ResearchGate](https://www.researchgate.net/profile/Javier_Espinosa-Oviedo)
  #       * [ORCID](https://orcid.org/0000-0002-4015-195X)
  #   design:
  #     columns: '1'





  # - block: markdown
  #   id: contact
  #   content:
  #     title: 'Contact'
  #     subtitle: ''
  #     text: |-
      
  #       <span id="mail" style="" class="text-primary-600 dark:text-primary-400 font-mono mb-4"></span>
        
  #       <script>
  #         const el = document.getElementById("mail");
  #         const parts = ["amF2aWVyLmVzcGlub3Nh", "dW5pdi1seW9uMS5mcg=="]; 
  #         el.textContent = atob(parts[0]) + "@" + atob(parts[1]);
  #       </script>      

  #       **Department of Informatics**    
  #       Université Claude Bernard Lyon 1     
  #       Bât. Nautibus, Campus la DOUA   
  #       25 av. Pierre de Coubertin     
  #       69622 Villeurbanne     
  #       France         

  #       {{< icon name="hero/map" >}} [View on map](https://maps.app.goo.gl/dXC3Ljru6CD79CbcA)

        


  #   design:
  #     columns: '1'





  # - block: myblox
  #   content:
  #     title: 'Visited Places'
  #     subtitle: ''
  #     text: # |-



  # - block: hero
  #   content:
  #     title: ""
  #     text: ""
  #   design:
  #     background:
  #       image:
  #         filename: unam.jpeg      
  #         parallax: false
  #         size: cover        # cover | contain | 32px | etc.
  #         position: center   # center | top | repeat          
  #         filters:
  #           brightness: 0.8          
  #           grayscale: 1
  #       text_color_light: true




  # - block: resume-experience
  #   content:
  #     username: espinosa
  #   design:
  #     # Hugo date format
  #     date_format: '2006'
  #     # Education or Experience section first?
  #     is_education_first: true
  # - block: resume-skills
  #   content:
  #     title: Skills & Hobbies
  #     username: me
  # - block: resume-awards
  #   content:
  #     title: Awards
  #     username: me
  # - block: resume-languages
  #   content:
  #     title: Languages
  #     username: me


---
