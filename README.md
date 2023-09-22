# html-access

## Description 

A marketing agency wanted their codebase to follow web accesibility standards to optimized in search engines. 

Starter code was provided to refactor the code.
[Visit the Deployed Site](https://azurek17.github.io/html-access/)

## Usage 

To improve Web Accessibility, and refactoring the code. Th following work was done to meet clients expectations.

Below are a couple areas revied in the index.html file

HTML: 

Alt tags where added to all imgage links.

HTML Code Example:

    No Alt Tags:

        ```html
         <img src="./assets/images/search-engine-optimization.jpg" class="float-left" />
     '''

    Alt Tags Provided:

        ```html
        <img src="./assets/images/search-engine-optimization.jpg" alt="search-engine-optimization"class="float-left" /> 



All non-semantic HTML Elements where converted to Semantic HTML Elements. 

Original Code:

    ```HTML

<body>
    <div class="header">
        .....
    </div>

'''
Refactored Code:

    '''HTML

<body>
    <!-- revised div to nav-->
    <nav class="header">
        .....
    </nav>

'''


CSS:
Removed all imgage link references in CSS and added to HTML and consolidated CSS Selectors to reduce code lines

Code Example:     

    '''CSS
            .benefit-lead, .benefit-brand, .benefit-cost {
                margin-bottom: 32px;
                color: #ffffff;
            }
    
'''

© 2023 github.com/AZurek17/html-access Confidential and Proprietary. All Rights Reserved.