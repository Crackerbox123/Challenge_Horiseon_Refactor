# Code Refactor for Horiseon

# TODO

GIVEN a webpage that meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN I find that they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title


# HTML Changes

    - Retitled

    - Changed <div class="header"> to the <header> semantic element

    - Changed div containing navigation links to the <nav> semantic element

    - changed <div class="footer"> to the <footer> semantic element

    - Replaced div with <section> semantic element

    - Replaced <article> semantic element to the Benefits content

    - Simplifed HTML to reduce number of unecesscary amount of IDs and Classes in all body content

    - Added <alt> attributes to all images 



# CSS Changes

    - Updated selectors to the new <header>, <nav>, <footer>, <section>, and <article> elements changed in the HTML

    - Greatly Reduced amount of CSS by reworking the Class + IDs in HTML

    - Commented and organized selectors

# GitHub Repository URL


    https://github.com/Crackerbox123/Challenge_Horiseon_Refactor


# Deployment ScreenShot + URL

    https://crackerbox123.github.io/Challenge_Horiseon_Refactor/


![deployed_img](https://user-images.githubusercontent.com/61638208/171347916-69c037cc-a706-4753-8f86-85bebd248a49.jpg)










    