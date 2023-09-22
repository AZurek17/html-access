# html-access

## Description 

A marketing agency wanted their codebase to meet web accesibility standards to optimized in search engines. 

The following code was revised to meet clients expectations meet Web Accessibility Standards, and refactored all non-seimatic elements into seimatic elements. 

Starter code was provided to refactor the code.
[Visit the Deployed Site](https://azurek17.github.io/html-access/)

## Usage 

Added Alt tags to all imgage links to meet Web Accessibility Standards.

    Original code: No Alt Tags:

        ```html

         <img src="./assets/images/search-engine-optimization.jpg" class="float-left" />

     '''

    Revised code: Added Alt Tags:

        ```html

        <img src="./assets/images/search-engine-optimization.jpg" alt="search-engine-optimization"class="float-left" /> 

    '''

Non-semantic HTML Elements <div>, where converted to Semantic HTML Elements. Semantic elements used: <nav>, <section>, <article>, <aside>, <footer>.

    Original Code: non-semantic Elements:

    ```HTML

<body>
    <div class="header">
        .....
    </div>

'''

    Refactored Code: semantic Elements:

    '''HTML

<body>
    <!-- revised div to nav-->
    <nav class="header">
        .... <!-- omitted body code for clarity-->
    </nav>

'''

    '''HTML
    <section class="content">
        <article id="search-engine-optimization"> 
            ..... <!-- omitted body code for clarity-->
        </article>

        <article id="online-reputation-management" class="online-reputation-management">
            ...... <!-- omitted body code for clarity-->
        </article>
             ..... <!-- omitted body code for clarity-->
    </section>


    <aside class="benefits">
        <article class="benefit-lead">
            ...... <!-- omitted body code for clarity-->
        </article>
        
        <article class="benefit-brand">
            ...... <!-- omitted body code for clarity-->
        </article>
        
    </aside>

'''


CSS:

Removed imgage link references in CSS and added to HTML to meet web accessiblity standands. Consolidated CSS Selectors to reduce code lines

Code Example:     

    '''CSS

            .benefit-lead, .benefit-brand, .benefit-cost {
                margin-bottom: 32px;
                color: #ffffff;
            }
    
'''


© 2023 github.com/AZurek17/html-access Confidential and Proprietary. All Rights Reserved.