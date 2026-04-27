---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:

  # Developer Hero - Gradient background with name, role, social, and CTAs
  - block: dev-hero
    id: hero
    content:
      username: espinosa
      greeting: "PhD, MSc, Eng"
      show_status: true
      show_scroll_indicator: true
      typewriter:
        enable: true
        # prefix: "Interested in "
        strings:
          - "Associate Professor in Data Systems"
          - "Mâitre de Conférences en Systèmes de Données"
          # - "I ❤️ Large-Scale Data Analytics"
          # - "I teach Cloud Computing & Big Data"  
        type_speed: 70
        delete_speed: 30
        pause_time: 2500
      cta_buttons:
        # - text: Biography
        #   url:  "#about"
        #   icon: arrow-down
        # - text: Resume
        #   url: "/resume"
        #   icon: bars-4          
        # - text: Get In Touch
        #   url: "#contact"
        #   icon: envelope      
    design:
      style: centered  # centered, split
      avatar_shape: circle # circle, rounded
      animations: true
      background:
        color:
          # light: "#fafafa"
          # dark: "#0a0a0f"
      spacing:
        padding: ["6rem", "0", "4rem", "0"]

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


  - block: markdown
    id: about
    content:
      title: 'About me'
      subtitle: ''
      text: |-
        I am a *Maître de Conférences* (Associate Professor with tenure) in the Department of Computer Science at [Lyon&nbsp;1 Université](https://www.univ-lyon1.fr), and a member of the Information Systems group at the [ERIC](https://eric.univ-lyon2.fr) research laboratory.

        Prior to joining Lyon 1, I was a Lecturer–Researcher at [CPE Lyon](https://www.cpe.fr), a French *Grande École* of engineering, and a member of the Database Group at the [LIRIS](https://liris.cnrs.fr/) CNRS laboratory.

        I have held research positions at the Barcelona Supercomputing Center ([BSC](http://bsc.es)), Delft University of Technology ([TU Delft](http://tudelft.nl)), the CONACyT–CNRS French–Mexican Laboratory of Informatics and Automatic Control ([LAFMIA](http://lafmia.imag.fr/)), and the Computer Science Laboratory of Grenoble ([LIG](https://www.liglab.fr)).

        I received my PhD in Computer Science from [Université Grenoble Alpes](https://www.univ-grenoble-alpes.fr) in France, and hold both an MSc and a BS in Computer Science and Computer Systems Engineering from [Universidad de las Américas Puebla](https://www.udlap.mx) in Mexico.

        My research lies at the intersection of databases and distributed systems, with a focus on designing scalable, efficient, and robust data management solutions.
    design:
      columns: '1'


  - block: markdown
    id: teaching
    content:
      title: 'Teaching'
      subtitle: ''
      text: |-
        |   |    |    |    |
        |----|----|----|----|
        `2026` | ⭐️[Cloud Computing](http://espinosa-oviedo.com/cloud-cci/)	| M2 CCI	| Univ. Lyon 1 | 
        `2026` | ⭐️Cloud, Storage & Virtualization	| M2 TIW	| Univ. Lyon 1 | 
        `2025` | [Big Data Engineering](https://espinosa-oviedo.com/big-data/)	| M2 TIW	| Univ. Lyon 1 | 
        `2025` | [Service & Cloud Computing](https://espinosa-oviedo.com/cloud/)	| M2 DISS	| Univ. Lyon 1 | 

        {{< button url="/courses" icon="academic-cap" style="ghost" align="center">}}see past courses{{< /button >}}
    design:
      columns: '1'


  - block: markdown
    id: publications
    content:
      title: 'Publications'
      subtitle: ''
      text: |-
        Available in my digital footprint: 
        * [Google Scholar](https://scholar.google.com/citations?user=RkXsr4YAAAAJ&amp;hl=en)
        * [DBLP](https://dblp.org/pid/11/1137)
        * [ResearchGate](https://www.researchgate.net/profile/Javier_Espinosa-Oviedo)
        * [ORCID](https://orcid.org/0000-0002-4015-195X)
    design:
      columns: '1'


  - block: markdown
    id: contact
    content:
      title: 'Contact'
      subtitle: ''
      text: |-
        <span id="mail" style="" class="text-primary-600 dark:text-primary-400 font-mono mb-4"></span>  
        <script>
          const el = document.getElementById("mail");
          const parts = ["amF2aWVyLmVzcGlub3Nh", "dW5pdi1seW9uMS5mcg=="]; 
          el.textContent = atob(parts[0]) + "@" + atob(parts[1]);
        </script>      

        **Département d'Informatique**    
        Université Lyon 1         
        Bâtiment Nautibus - Campus La Doua    
        25 avenue Pierre de Coubertin     
        69622 Villeurbanne  
        {{< button url="https://maps.app.goo.gl/dXC3Ljru6CD79CbcA" icon="map-pin" style="ghost">}}View on map{{< /button >}}

        **Postal address**    
        43 boulevard du 11 Novembre 1918    
        69222 Villeurbanne CEDEX    
        France                 
    design:
      columns: '1'


  - block: my-map
    content:
      title: 'Around the Globe'
      subtitle: ''
      text: |-
        Places I have visited over the years
        <br><br>


---
