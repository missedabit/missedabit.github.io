# BT Email Messaging bundle overview:
Downloadable email messaging bundle for BT customers and internal departments;
This bundle provides the basic scaffold for building email templates based on the current BT style framework;
It can be extended / customised to suit the users needs;
All current components have been tested in Litmus for a variety of email clients (Outlook/Gmail/Lotus Notes etc);
Mobile first, responsive approach. As a fallback for older email clients, graceful degradation applies.

# Bundle breakdown:
1.    emailDocumentation.doc - "How to use" documentation;
2.    componentLibrary.html - Component library with common html snippets;
3.    emailTemplate.html - Basic email template, with html commented placeholders;
4.    images/fonts - Example images and fonts folders;

# Notes for HTML developers:
1.    The documentation provides a step by step approach to get up and running;  All code is fully customisable;
2.    Adjustments to guttering/padding can be made to content wrappers depending on where they appear in the stack;
3.    Tabulated content (e.g. order details) appears twice in the code (for desktop/mobile) using responsive show/hide css;
4.    Where required, conditional statements are used to ensure all content renders correctly in Outlook:

            <!--[if !mso]><!-->
                  Lorem Ipsum Lorem Ipsum Lorem Ipsum 
            <!--<![endif]-->
      
# Useful references:
1.    Litmus: https://litmus.com/sessions/new
2.    Litmus email forum:  https://litmus.com/community
3.    HTML encoding:  https://www.opinionatedgeek.com/Codecs/HtmlEncoder
4.    Github html preview:  http://htmlpreview.github.io
5.    ICS link generator:  https://jennamolby.com/tools/ics-link-generator
