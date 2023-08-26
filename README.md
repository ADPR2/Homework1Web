# Hello 👋, I'm Adrián Pérez 👍

## About Me
I live in Mexico City. Currently, I'm working in software development while continuing my studies. I'm planning to graduate in a year. I went to the Taylor Swift concert and I like french fries. 🥔

![Guindo](image.png)

- 👨💻 I have a website that I created using Wordpress, and it's about to expire. [My Website](https://adrianpf.me)


## Technologies I Use
> select * from TechSkills

| ID | TechSkills                      |
|----|---------------------------------|
| 1  | HTML                            |
| 2  | C++                             |
| 3  | C#                              |
| 4  | PHP                             |
| 5  | .NET Core                       |
| 6  | .NET Framework                  |
| 7  | VB.NET                          |
| 8  | UNIX Commands                   |
| 9  | MySQL                           |
| 10 | SQL Server                      |
| 11 | Git                             |
| 12 | Wordpress                       |

## Technologies you are learning
> select * from LearningTechnologies

| ID |LearningTechnologies             |
|----|---------------------------------|
| 1  | Oracle DB                       |
| 2  | Android Studio                  |
| 3  | Docker                          |
| 4  | CSS                             |
| 5  | Bootstrap                       |
| 6  | Unity                           |
| 7  | Go                              |
| 8  | Blazor                          |
| 9  | Laravel                         |
| 10 | Node.js                         |

## Goals at the end of my degree

- **Advance in the company I work for:** I aim to progress within the company where I am employed, taking on higher roles and responsibilities.

- **Achieve satisfying personal projects:** My goal is to complete personal projects that I find fulfilling and rewarding.

- **Gain a comprehensive understanding of software development processes:** I aspire to comprehend and master all aspects of software development processes.

- **Cultivate a mindset for innovation and solution creation:** I strive to develop a mindset that fosters innovation and the ability to create effective solutions.

- **Strike a balance between projects, work, and leisure:** I aim to find equilibrium between managing projects and work responsibilities while maintaining a healthy work-life balance.

## Creating a Local Repository and Uploading to GitHub

1. **Install Git:** If you haven't already, download and install Git on your computer.

2. **Create a Folder:** Create a folder on your local computer where you want to set up your project.

3. **Open Git Program:** Open your terminal or command prompt.

4. **Create a GitHub Account:** If you don't have one, create a GitHub account at [github.com](https://github.com).

5. **Create a Repository on GitHub:**
   - Log in to your GitHub account.
   - Click the "+" button in the top-right corner and choose "New repository."
   - Provide a repository name, description, and other settings.
   - Click "Create repository."

6. **Navigate to Your Project Directory:** In the Git program, navigate to the directory of your project where you want to initialize the Git repository.

7. **Initial Commits:**
   - Run the following commands in your terminal:
   
     ```sh
     git init
     git branch -M main
     git add .
     git commit -m "Initial commit"
     ```

8. **Link Local Repository to GitHub:**
   - Run the following command in the terminal, replacing `yourusername` with your GitHub username and `your-repo-name` with the repository name:
   
     ```sh
     git remote add origin (copy the link in point 5)
     ```

9. **Push to GitHub:**
   - Push your local repository to GitHub using the following command:
   
     ```sh
     git push -u origin main
     ```

and that's it :)

## Git Commands

1. **Check Repository Status:**
   - To check the status of your local repository:
     ```sh
     git status
     ```

2. **Add Files to Staging:**
   - To add individual files to the staging area:
     ```sh
     git add filename
     ```
   - To add all changed files to the staging area:
     ```sh
     git add .
     ```

3. **Commit with Comments:**
   - To commit staged changes with comments:
     ```sh
     git commit -m "comment"
     ```

4. **Upload Changes to Remote:**
   - To upload your committed changes to the remote repository:
     ```sh
     git push origin branch-name
     ```

5. **Manage Branches:**
   - To create a new branch, use:
     ```sh
     git branch new
     ```
   - To switch to a branch, use:
     ```sh
     git checkout branch
     ```
   - To delete a branch, use:
     ```sh
     git branch -d branch
     ```

6. **Rollback to Specific Commit:**
   - To reset your repository to a specific commit, use:
     ```sh
     git reset commit-hash
     ```
   - To discard changes and revert to the last commit, use:
     ```sh
     git reset --hard HEAD
     ```
