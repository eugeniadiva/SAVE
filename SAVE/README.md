# Project 0

Web Programming with Python and JavaScript
-------
My name is Eugenia Diva Widodo and for my project0, I decided to make a website of one of my school CAS (Creativity Action Service) project called SAVE. SAVE stands for Students for Animal Choices and Ethics. As a leader, I've been leading my fellow members to help raise awareness about the issue concerning animals.

The main or home part of my website is the 'main.html'.
~> viewport
~> style @Media for the biggest headline
~> connected to stylesheet file -> size.css
~> bootstrap
  - component (breadcrumb)
      -> hyperlinked to several .html pages
        1. about.html -> containing informations about SAVE
            - connected to stylesheet file -> styleabout.css
            - bootstrap's grid model columns (Nesting)
            - image
        2. join.html -> input data to join and contribute with SAVE
            - connected to stylesheet file -> styles.css
            - bootstrap's component (form)
            - bootstrap's component (button)
            ~> hyperlinked to success.html -> thank you related information for filling up the form
                - connected to stylesheet file -> stylesuccess.css
                  -> using stylesuccess.scss compiled to stylesuccess.css (using scss inheritance)
        3. leaders.html -> table data list of SAVE executives
            - connected to stylesheet file -> styletable.css
            - table
        4. stages.html -> stages that SAVE follows
            - connected to stylesheet file -> stages.css
            - bootstrap's grid model columns (Equal-width)
        5. objectives.html -> SAVE's aim and learning outcomes
            - connected to stylesheet file -> objective.css
                -> using objective.scss compiled to objective.css (using both scss variables and nesting)
            - ordered list -> objectives
            - unordered list -> learning outcomes
      -> each of the hyperlinked .html pages have a button (from bootstrap's component) to go back to the main or home page
~> image (SAVE logo)
~> link to SAVE's instagram account using href (for contact info)
