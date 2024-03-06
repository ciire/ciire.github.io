# Hosting your Resume on Github Pages

## Purpose
The purpose is to provide steps on how to host and format your resume. The steps will reference and connect to the general principles of current technical writing as explained by Andrew Etter in “Modern Technical Writing”.

## Prerequisite
You must have a resume written in markdown. There is a markdown tutorial to help you get started in the More Resources section. Download 

## Instructions
### Creating a Github account
1. Search https://github.com.
2. Click sign up in the top right hand corner.
3. Type in your email.
4. Create a password.
5. Create a unique username.
6. Click the green continue button on the bottom left.
7. Click the green verify button to answer the captcha.
8. Answer the captcha.
9. Click submit.
10. Go to the email that you used to create this new account.
11. Find the code sent to you by github.
12. Enter the code in github.com.
13. Click "skip personalization" in the bottom center of the page.
### Getting a Theme and Setting up Repository
14. Search https://github.com/daattail/beautiful-jekyll.
15. Click fork on the top right beside watch.
16. Rename the repository name to your github username.github.io.
17. Click the green Create Fork button in the bottom right corner.
     * By forking other repositories we are practicing features tied with Distributed Version Control mentioned in Etter's "Modern Technical Writing". Git provides features such as forking which incentivizes collaboration. Developers can contribute without needing direct access to the original repository. Multiple people can work on the same file effectively without there being constant issues about concurrency. People can create their own branches of code on the same project and work in parallel.
### Uploading your resume to github
18. Click “Add a file".
19. Click “upload files" from the drop down menu.
20. Choose your markdown resume file to add. 
     * The reason we use markdown is because it is a lightweight markup language. In Etter's "Modern Technical Writing", he advocates the use of lightweight markup language because of its simplicity. Compared to other alternatives such as Extensive Markup Language(XML), it is much more human readable. Lightweight markup serves as a way to produce XML in a simpler and easier manner. Lightweight markup still holds all the advantages of being a markup language. It is still very portable, being able to be opened on many different applications.
21. Click the green commit changes in the bottom left. 
### Host resume on GitHub Pages (static site generator)
22. Click on your resume file.
23. Click on the pencil icon “edit this file” on the right.
24. Rename your resume to index.md.
25. Click on commit changes on the top right.
### Viewing your hosted resume in your user repository
26. Click on action
     * Wait until the "pages build and delpoyment" yellow circle turns into a green checkmark.
27. Enter the website username.github.io to view your resume.
     * By creating this website, we are making use of a static site generator. Etter is a huge advocate for static site generators in his "Modern Technical Writing". Static site generators are quick to use as they don't have much to set up. There is nothing to install and no server side dependencies required. All you need to create a website with static site generators is lightweight markup for the main content and some HTML and CSS for the theme and asethetics.
### Posting a GIF
28. 


	
## More Resources
[Here](https://www.youtube.com/watch?v=qhoXn4bIE1s) is a resource to get you started with Markdown. It covers simple and useful Markdown syntax.

[Here](https://www.youtube.com/watch?v=g6AJ9qPPoyc) is a resource that expands on how to create a static site in GitHub Pages.

[Here](https://www.youtube.com/watch?v=Gn3w1UvTx0A) is a resource that walksthrough creating an account if you are still having difficulties with it. 

[Here](https://www.youtube.com/watch?v=CTqqvaVKAJU&t=4s) is a resource that explores how to use the built in Jekyll themes in Github.



## Authors and Acknowledgment
Special thanks to dattail for the theme and Ryan Mack and Barbara Guzman Romero for peer reviewing the readme.

## FAQs
### Why can I not fork a theme into my repository?

If you are having trouble forking a theme into your repository, it may be because you already have an existing repository of the same name. This can be resolved by deleting the existing repository that you have. Then you can fork the theme into your github account without having a duplicate repository already existing with the same name.

### Why is Markdown better than Word Processor
Markdown is better than word processor because it creates documentation in a flexible way, being able to be opened using any application compared to Word Processor that needs to be opened as a PDF. PDFs are more suited for short term use. Documentation is more suited towards living online and thus would use Markdown over PDF as Markdown is highly portable compared to Word. 


## License

[MIT](https://choosealicense.com/licenses/mit/)
