# resumecard

I have analyzed and made modifications to [ddbullfrog's resumecard](https://github.com/ddbullfrog/resumecard).

# Demo

## Desktop

![desktop](https://github.com/NoviceCodeVoyager/NoviceCodeVoyager.github.io/blob/main/_assets/normal.jpg?raw=true)

## Mobile

<p float="left">
  <img src="https://github.com/NoviceCodeVoyager/NoviceCodeVoyager.github.io/blob/main/_assets/mobile1.jpg?raw=true" width="300" height="500">
  <img src="https://github.com/NoviceCodeVoyager/NoviceCodeVoyager.github.io/blob/main/_assets/mobile2.jpg?raw=true" width="300" height="500">
  <img src="https://github.com/NoviceCodeVoyager/NoviceCodeVoyager.github.io/blob/main/_assets/mobile3.jpg?raw=true" width="300" height="500">
</p>

# Review

  > **Difference between fork and clone**:

  Forking involves creating a personal copy of someone else's repository on GitHub, allowing you to freely experiment with changes. On the other hand, cloning is the process of creating a local copy of a remote repository on your computer.

  > **Changing GitHub username and email in VSCode**:

  In the context of VSCode, you can update your local Git configuration for the username and email. Open the terminal in VSCode and use the following commands. By using the command 'git config user.name,' you can determine your current username configured in your VSCode. To change the username, simply use the command 'git config user.name "name"' and replace 'name' with the desired new name. The process is the same for changing your email. By using the 'git config user.email' command, you can find out your current email configured in your VSCode. To update the email, use the command 'git config user.email "email"' and replace 'email' with the new email address you want. If you don't change the information, the commit history associated with your existing GitHub account will persist, and your contributions to the project will be attributed to your original GitHub account.

  > **Creating a GitHub repository and configuring a page using GitHub theme**:

  To create a repository on GitHub, click on the "New" button, provide the necessary details, and click "Create repository." To set up a GitHub Pages site using a theme, go to the repository settings, scroll down to the GitHub Pages section, and choose a theme. After choosing a theme and downloading the files, you can check the local execution screen by entering the 'bundle install' command and then 'bundle exec jekyll serve' command.

  > **Using Google Maps API**:

  To utilize the Google Maps API, you need to obtain an API key from the Google Cloud Console. Once you have the key, you can integrate it into your application to access various Google Maps services.

  > **Using Kakao Maps API**:

  To integrate the Kakao Maps API, you first need to create a Kakao Developer account and register your application. After obtaining the API key, integrate it into your project. Then, go to your applications in Kakao Developers, click on the app you created, enter the website address you will use in the "Domains" section on the left menu, and you can start utilizing the Kakao Maps service

# Aspects that proved unsuccessful during the modification

When I ran the existing code repository, I found that the Google Maps API key had expired.
In an attempt to address this issue, I tried to switch to the Kakao Maps API, but encountered difficulties and was unsuccessful.

# License

Open sourced under the [MIT license](LICENSE.md).
