<div>
<div id="badges">
  <a href="your-linkedin-URL">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="your-youtube-URL">
    <img src="https://img.shields.io/badge/YouTube-red?style=for-the-badge&logo=youtube&logoColor=white" alt="Youtube Badge"/>
  </a>
  <a href="your-twitter-URL">
    <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
  </a>
</div>

<img src="https://komarev.com/ghpvc/?username=your-github-username&style=flat-square&color=blue" alt=""/>
</div>
<div align="center">
  <img src="https://media.giphy.com/media/dWesBcTLavkZuG35MI/giphy.gif" width="600" height="300"/>
</div>

---

### :woman_technologist: About Me :
- :telescope: I’m working as a Software Engineer and contributing to frontend and backend for building web applications.

- :seedling: Exploring Technical Content Writing.

- :zap: In my free time, I solve problems on GeeksforGeeks and read tech articles.

- :mailbox:How to reach me: [![Linkedin Badge](https://img.shields.io/badge/-kakbar-blue?style=flat&logo=Linkedin&logoColor=white)](your-linkedin-url)

Note that in the last line, the inner ![]() syntax is to display the LinkedIn badge image. The outer []() is Markdown hyperlink syntax to make the badge point to the LinkedIn profile URL. We’ve used Shields.io here for displaying a customized LinkedIn badge. You can also add any other links where people can reach out to you.

See the output in the picture below.
About yourself description preview
Coding Assessments
Adding Languages and Tools

Here’s a picture of the content that we’ll add in this section.
Languages and tools section

For the heading, add the following code to README.md:

---

### :hammer_and_wrench: Languages and Tools :

We’ll add images representing technologies and skills one holds. You can find several free logos for many languages and tools in the DevIcons GitHub Repository.

Go to the icons folder and search and open the react folder. You’ll find images in SVG and EPS format. Click on any image and copy the URL shown in the browser’s address bar.
DevIcons react logo

We’ll use this URL in the <img> tag and specify the height and width attribute accordingly. Similarly, you can search for other skills and add them in separate <img> tags.

Append the below code to README.md. Add/remove the necessary skills you want in your profile:

<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/java/java-original-wordmark.svg" title="Java" alt="Java" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original-wordmark.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/spring/spring-original-wordmark.svg" title="Spring" alt="Spring" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/materialui/materialui-original.svg" title="Material UI" alt="Material UI" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/flutter/flutter-original.svg" title="Flutter" alt="Flutter" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/redux/redux-original.svg" title="Redux" alt="Redux " width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain-wordmark.svg"  title="CSS3" alt="CSS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/firebase/firebase-plain-wordmark.svg" title="Firebase" alt="Firebase" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/gatsby/gatsby-original.svg" title="Gatsby"  alt="Gatsby" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/mysql/mysql-original-wordmark.svg" title="MySQL"  alt="MySQL" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/nodejs/nodejs-original-wordmark.svg" title="NodeJS" alt="NodeJS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" title="AWS" alt="AWS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" title="Git" **alt="Git" width="40" height="40"/>
</div>

The results are pictured below.
Languages and tools preview
Adding GitHub Stats

Here’s an image of what we’ll add in this section.
GitHub stats section

For heading, add the following code to README.md:

---

### :fire: My Stats :

We’ll add some stats about the user’s GitHub activity like the number of commits, number of PRs, etc., to this section. There are many open-source projects on GitHub that offer different stats for the GitHub profile. In this tutorial, we’ll see how to use two such open-source projects.

The first open-source project that offers GitHub stats is GitHub Streak Stats. This project provides the following three stats:

    total number of contributions by a user
    longest streak of contributions for a user
    current streak stat for a user

Access the stats using the following URL:

https://github-readme-streak-stats.herokuapp.com/?user=your-github-username

We can add customizations like theme, background color, and so on, by adding query parameters to the above URL. Add the following code to README.md. Replace the github-username with your GitHub username:

[![GitHub Streak](http://github-readme-streak-stats.herokuapp.com?user=your-github-username&theme=dark&background=000000)](https://git.io/streak-stats)

Here’s a preview with itsZed0 as the username.
Streak stats preview

We can also use the Streak Stats Website to generate the URL. To do so, follow these steps:

    Go to the Streak Stats Website. In the Username field, enter your GitHub username. Change the other fields as needed.
    Once you’ve customized all the fields, click on the Submit button.
    After the Markdown is generated, click on the Copy To Clipboard button and add the copied Markdown to README.md.
    Streak Stats Tool

The next open-source project that provides some more GitHub stats of a user is GitHub Readme Stats by Anurag Hazra. This project provides many stats, but for this tutorial, we’ll only use the one which displays the top languages used by the GitHub user. If you want to explore and use more stats from this project, you can go through the detailed documentation available in their repository.

Below is the Markdown to display the top languages of a user:

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=your-github-username)](https://github.com/anuraghazra/github-readme-stats)

We can customize it to give a different color, limit the maximum number of languages to show, and so on. For customization details, refer to the GitHub Readme Stats repository.

Add the following code to README.md. Replace the your-github-username with your username:

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=your-github-username&layout=compact&theme=vision-friendly-dark)](https://github.com/anuraghazra/github-readme-stats)

Pictured below is the preview for my itsZed0 account.
GitHub readme stats preview
Build Your Own Developer Portfolio - Free
Adding Recent Blogs to Your GitHub Profile README

The picture below shows what we’re aiming for in this section.
Blog posts

For the heading, add the following code to your GitHub profile README.md:

---

### :writing_hand: Blog Posts :

This section will show the recent blog posts published by a GitHub user at different blogging platforms. To achieve this, we’ll create a GitHub workflow, which is an automated process to execute jobs. Each job in a workflow will have one or more actions. A GitHub action is a set of executable commands combined into steps. We can either create our own GitHub action or use an action created by some other user.

To fetch the blog posts, we’ll use two already existing actions:

    Checkout: used to check out all the files in the current repository to a Git workspace where our workflow can access it.
    Blog Post Workflow: used to fetch recent blog posts published by a user on various websites.

The workflow can be run on a specific schedule or an event trigger. For this tutorial, we’ll execute the workflow every one hour, to fetch the recent blog post. You can read more about GitHub actions from the official documentation.

To configure the GitHub workflow, follow these steps:

    Add the following code to your README.md. The workflow will replace the comment below with the list of published blog posts:

    <!-- BLOG-POST-LIST:START -->
    <!-- BLOG-POST-LIST:END -->

    Save the changes by clicking on the Commit changes button.
    The configuration of GitHub workflow is defined in a .yml file, which follows a YAML syntax. In your repository, in the Add File dropdown, select Create New file.
    Create new file in GitHub

    In Name your file.. field, enter .github/workflows/blog-post-workflow.yml. All GitHub workflow’s .yml configuration files reside under the .github/workflows directory.
    Create blog post yml file

    Add the following code in the Edit new file tab:

    name: Latest blog post workflow
    on:
      schedule:
        # Runs every hour
        - cron: '0 * * * *'
      workflow_dispatch:

    jobs:
      update-readme-with-blog:
        name: Update this repos README with latest blog posts
        runs-on: ubuntu-latest
        steps:
          - uses: actions/checkout@v2
          - uses: gautamkrishnar/blog-post-workflow@master
            with:
              max_post_count: "4"
              feed_list: "https://dev.to/feed/itszed0"

In the above code, we’ve defined a workflow with name as “Latest blog post workflow”, which runs on a schedule mentioned in the cron field. 0 * * * * is a POSIX cron syntax, meaning that the schedule is to run at the 0th minute every hour.

workflow_dispatch: allows the user to trigger the workflow manually. jobs let us define one or more jobs that will run when the workflow is executed. In our case, we have one job — that is, update-readme-with-blog — which runs-on an Ubuntu environment machine hosted by GitHub.

steps define a set of actions or commands to be executed. We’ve defined two actions under steps: actions/checkout@v2 and gautamkrishnar/blog-post-workflow@master. The latter takes two input parameters defined under the with field. max_post_count defines the maximum number of posts to show in the README, feed_list is a comma-separated RSS feed of URLs for different blogging platforms.

In this tutorial, we’ve fetched blogs from the dev.to platform. For the list of all supported platforms, check this documentation.

To learn more about GitHub workflow syntax, check out this Workflow Syntax documentation.

Replace the feed_list with your RSS feed URLs and click on the Commit new file button. This will successfully create the workflow. It will fetch new blog posts from dev.to and add them to your README.md file every hour.

To trigger the workflow manually, follow these steps:

    In your repository, go to the Actions tab.
    Under All workflows, click on Latest blog post workflow.
    In the Run workflow dropdown, click on the Run workflow button. The workflow will start executing.
    Run Blog post workflow

    Go to your GitHub profile page, and under the “Blog Posts” section you’ll see a list of all the blog posts from the blogging platforms defined in the blog-post-workflow.yml file. Below is the output for "https://dev.to/feed/itszed0" in the feed_list.
    Blog posts

Note that the user itsZed0 has one article titled “Test Post” at dev.to, which can be found here. Hence, the workflow fetches that one article and displays it in the GitHub profile README.

The final GitHub profile is pictured below.
GitHub profile readme GIF
Conclusion

In this tutorial, we’ve learned what a GitHub profile README is and how to:

    create a GitHub profile README
    add GIFs, descriptions, skills
    add GitHub Streak Stats and GitHub Readme Stats
    create a GitHub workflow to fetch the latest published blog posts

I hope this tutorial inspires you to create an amazing GitHub profile README. Also, you can go through these open-source projects that’ll let you add some more cool features to your GitHub profile README:

    Display weekly Dev metrics
    Display Spotify recently played song card
    Show a new programming joke every day

Share This Article
Nida Khan
Nida Khan

I am a full stack developer from India. I am a hands-on learner, hence prefer learning new technologies through development. In my free time, I explore new technologies, read tech blogs and solve problems on Data Structures and Algorithms.

career
career-advancement
git tutorial
github
The Unix Bible
The Unix Bible
The DevOps Toolkit: Catalogue, Patterns and Blueprints

