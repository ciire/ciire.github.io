# Hosting your Resume on Github Pages

## Purpose
The purpose is to provide steps on how to host and format your resume. The steps will reference and connect to the general principles of current technical writing as explained by Andrew Etter in “Modern Technical Writing”.

## Prerequisite
You must have a resume written in markdown. There is a markdown tutorial to help you get started in the More Resources section. Download 

## Instructions
### Creating a Github account
### Setting up a Repository
1. Search https://github.com.
2. Click sign up in the top right hand corner.
3. Type in your email.
4. Create a password.
5. Create a unique username.
6. Search https://github.com/yourUsername where yourUsername is the username of your github account
     * Login if you are not currently logged in
7. Click on Repositories
8. Click the green “new” button to create a new repository
9. Fill out the form
     * Write your repository name as the same name as your Github username.
     * Set as public so others can see your resume
10. Commit to the repository
     * By forking other repositories we are practicing features tied with Distributed Version Control mentioned in Etter's "Modern Technical Writing". Git provides features such as forking which incentivizes collaboration. Developers can contribute without needing direct access to the original repository. Multiple people can work on the same file effectively without there being constant issues about concurrency. People can create their own branches of code on the same project and work in parallel.
### Uploading your resume to github
4. Click “Add a file”
5. Click “upload files"
6. Choose your markdown resume file to add. 
     * The reason we use markdown is because it is a lightweight markup language. In Etter's "Modern Technical Writing", he advocates the use of lightweight markup language because of its simplicity. Compared to other alternatives such as Extensive Markup Language(XML), it is much more human readable. Lightweight markup serves as a way to produce XML in a simpler and easier manner. Lightweight markup still holds all the advantages of being a markup language. It is still very portable, being able to be opened on many different applications. 
7. commit changes. 
### Host resume on GitHub Pages (static site generator)
7. Click on your resume file
8. Click on the pencil icon “edit this file”
9. Rename your resume to index.md
10. Commit Changes
### Viewing your hosted resume in your user repository
11. Click on action
     * Wait until the website has been built before trying to access it
12. Enter the website username.github.io to view your resume


	
## More Resources
[Here](https://www.youtube.com/watch?v=qhoXn4bIE1s) is a resource to get you started with Markdown. It covers simple and useful Markdown syntax.

[Here](https://www.youtube.com/watch?v=g6AJ9qPPoyc) is a resource that expands on how to create a static site in GitHub Pages.



## Authors and Acknowledgment

## FAQs
### Why can I not fork a theme into my repository?

If you are having trouble forking a theme into your repository, it may be because you already have an existing repository of the same name. This can be resolved by deleting the existing repository that you have. Then you can fork the theme into your github account without having a duplicate repository already existing with the same name.

### Why is Markdown better than Word Processor
Markdown is better than word processor because it creates documentation in a flexible way, being able to be opened using any application compared to Word Processor that needs to be opened as a PDF. PDFs are more suited for short term use. Documentation is more suited towards living online and thus would use Markdown over PDF as Markdown is highly portable compared to Word. 


## License

[MIT](https://choosealicense.com/licenses/mit/)
