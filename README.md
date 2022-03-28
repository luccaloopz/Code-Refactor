# Code-Refactor

## **Description**

The purpose of this homework was to refactor the already existing code to ensure that it meets a certain set of acceptance criteria. Remember, refactoring does not mean changing the code itself, but simply making improvements to the code so that you may meet these acceptance criteria.

## **Acceptance Criteria**

See below:

![screenshot](./assets/images/acceptance-criteria.png "Acceptance Criteria")

## **Languages Used**

The programming languages used in this homework were html and css. 

## **Important Code Snippets**

This block of code I thought important to mention because it gave me a better understanding of how to create hyperlinks on a webpage by using the `a` anchor tag with an href attribute:

```html
    <ul>
        <li>
            <a href="#search-engine-optimization">Search Engine Optimization</a>
        </li>
        <li>
            <a href="#online-reputation-management">Online Reputation Management</a>
        </li>
        <li>
            <a href="#social-media-marketing">Social Media Marketing</a>
        </li>
    </ul>
``` 

This element I thought important to mention as well because it helped me further grasp the concept of semantic html elements. By adding in an `aside` element, the code is better organized to mimick how the webpage is intended to look instead of using a simple `div` element. See below:

```html
    <aside class="benefits">
        <div class="benefit-lead">
            <h3>Lead Generation</h3>
            <img src="./assets/images/lead-generation.png" alt="icon representing lead generation"/>
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>
        </div>
        <div class="benefit-brand">
            <h3>Brand Awareness</h3>
            <img src="./assets/images/brand-awareness.png" alt="icon representing brand awareness"/>
            <p>
                Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
            </p>
        </div>
        <div class="benefit-cost">
            <h3>Cost Management</h3>
            <img src="./assets/images/cost-management.png" alt="icon representing cost management"/>
            <p>
                As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
            </p>
        </div>
    </aside>
```