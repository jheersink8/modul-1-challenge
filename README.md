# module-1-challenge
Challenge 1 of coding boot camp (due date 12.21.2023)

## Description
**WHAT WAS YOUR MOTIVATION?** The 'client' had requested that their HTML and CSS code get refactored to (1) abide by accessibility practices, (2) follow the Scout Rule by leaving the code cleaner than it was originally presented, and (3) leave the functionality of the page as originally presented. 

**WHY DID YOU BUILD THIS PROJECT?** The client recognized shortcomings in their code and they wanted a junior developer to refactor it.

**WHAT PROBLEM DOES IT SOLVE?** The aesthetic presentation of the final deliverable is identical to the original content (as per the client's request). However, the HTLM and CSS code has been streamlined and cleaned up when possible. This will help accomplish two things. One, this is futureproofing the webpage, making modifications and expansions easier. Two, the coded content is now more presentable for human consumption. 

**WHAT DID YOU LEARN?** There are many ways to code a webpage and get the same result. Even though the originally presented content "worked," the code wasn't at an optimal standard. Although you can code different ways and get the same result, some ways appear to be "more correct" than others. 

## Usage
The live final product can be viewed at: https://jheersink8.github.io/module-1-challenge/ 

The parameters of this challenge were to serve as a refactor for the client. Some of the change orders include:

**HTML:**
- A meaningful title was given in the *head* element.
- All *div* elements were replaced with semantic elements *header*, *nav*, *section*, and *footer* for the sake of accessibility. 
- Added a *header* instead of a *div* with a class of header. 
- Added *main* for ease of partitioning and following HTML elements.
- Moved digital-marketing-meeting.jpg from CSS to HTML for consistency. 
- Added alt text to all images for accessibility.
- Removed redundant id attributes from images and created a single class for all three images. 
- Added a *footer* instead of a *div* with a class of footer. 

**CSS:**
- Used the selector of header instead of .header. 
- Removed irrelevant selectors from multiple CSS rules. 
- Changed out all div selectors with respective new selector from HTML. 
- Removed irrelevant CSS rules completely. 
- Consolidated several ID attributes to class attributes in HTML which led to fewer CSS rules. 
- Used the selector of footer instead of .footer.

**PERSONAL DEVELOPER NOTE:** 
- There is a git commit with all of the comments of changes listed in the code. However, the code doesn't look cleaner than when I left it, so the final commit does not include these comments. 

An image of the final product (which is idential to the product provided by the client) can be viewed here: 

![alt text](assets\images\image-final-product.png)

## Credits 
The original code was presented by Denver University in the Bootcamp course ID DU-VIRT-FSF-PT-12-2023-U-LOLC-MWTH under Module 1 Challenge. All code was modified and submitted by Jordan R. Heersink. 

## License
MIT License

Copyright (c) 2023 Jordan Heersink

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
