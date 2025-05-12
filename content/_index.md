---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: static/uploads/jansen_cv.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
sections:
  - block: markdown
    content:
      title: "Published Papers"
      text: |-
        - **The effects of gender stereotypes on citizens’ perceptions of corruption: evidence from a conjoint survey experiment in Malaysia**  
          [Read it here](https://www.elgaronline.com/edcollchap/book/9781803923246/book-part-9781803923246-31.xml?tab_body=abstract-copy1)  
          *Abstract:*  
          Do gender stereotypes influence citizens’ perceptions of government corruption? Gender stereotypes of female politicians generally cast an image of higher ethical behavior when compared to their male counterparts. While recent research has established a causal relationship between women’s involvement in politics and reduced concerns about political corruption, the results are limited exclusively to a western sample—where there are more female politicians and generally more gender equity. As such, we cannot ascertain (1) whether the purported effects of gender stereotypes are more pronounced because non-western women are seen as even more ethical, honest, and trustworthy; and if so, (2) whether this difference is driven more by men or women—or both. To examine this, I employed a conjoint survey experiment in Malaysia—home to one of the largest government corruption scandals globally to date (N = 2000). The results suggest men are perceived to be more likely to engage in corruption than women at a higher rate than what the existing literature suggests—and that much of this finding is driven by male respondents.

  - block: markdown
    content:
      title: "Working Papers"
      text: |-
        - **Natural Disasters and the Electability of Women: Evidence from Philippine Mayoral Elections**  
          *Abstract:*  
          Do natural disasters influence electoral outcomes, and does this effect vary by candidate gender? While retrospective voting theory suggests that voters can rationally assess leader performance during crises, it often overlooks how candidate identity may shape evaluations in ways that depart from competence-based logics under conditions of threat. I argue that natural disasters intensify the role of gender in electoral decision-making, activating latent biases that disadvantage female candidates. Using panel data from 1,632 Philippine municipalities (2001–2010), I analyze mayoral elections merged with a geospatial typhoon exposure index to examine how disaster severity affects three electoral outcomes: candidate entry, candidate electoral success, and incumbent vote share. I find no evidence that disasters increase the supply of female candidates. However, typhoon exposure significantly reduces win rates for female challengers and erodes vote shares for female incumbents under repeated shocks. These findings suggest that climate crises amplify the political salience of gender, distorting voter evaluations and reinforcing patterns of under-representation of women in political office.

  - block: markdown
    content:
      title: "Other Publications"
      text: |-
        - **Breaking barriers or reinforcing bias? Climate crises and the gender divide in political leadership**  
          Blog post for Kleinman Center (2024).  
          [Read it here](https://kleinmanenergy.upenn.edu/commentary/blog/insights-from-the-the-political-economy-of-climate-change-and-the-environment-2024-mini-conference/)
sections:
  - block: markdown
    content:
      title: "My Approach to Teaching"
      text: |-
        My teaching philosophy is grounded in adaptability, intentional design, and care. I view each classroom as a dynamic space shaped by the diverse experiences, identities, and commitments students bring with them—including those navigating higher education as first-generation college students, working professionals, or members of historically excluded communities.

        I design my courses using a backward planning framework, centering clarity and accessibility from the outset. I prioritize well-structured materials, transparent learning outcomes, and assessments that offer flexibility and choice. Whether through asynchronous modules or “choose-your-own-adventure” assignments, my goal is to support different modes of engagement while maintaining academic rigor.

        I believe that fostering student agency is essential not only for learning but also for integrity. In an era where artificial intelligence and generative tools are reshaping how students interact with knowledge, I encourage critical reflection and collaborative inquiry over surveillance. When students feel trusted and supported, they respond with curiosity and accountability.

  - block: markdown
    content:
      title: "Teaching Experience"
      text: |-
        ### Section Leader
        - **Bending/Curve: Climate Change**  
          Summer 2024

        ### Teaching Assistant
        - **Politics of Multiculturalism**  
          Spring 2024
        - **Comparative Politics: Race & Ethnicity in Africa**  
          Winter 2023, 2024
        - **Corruption in Developing Countries**  
          Spring 2023
        - **Japanese Politics**  
          Fall 2023
        - **International Organizations**  
          Fall 2022
          
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
