# My Professional Portfolio

Welcome to your new professional portfolio! This website is designed to be simple, clean, and easy to update, even if you have no experience with coding. You can use it to showcase your Jupyter Notebooks, videos, and other projects.

## How to Update Your Portfolio

You can manage your entire portfolio using just your web browser and the GitHub interface. Here’s how you can customize it with your own content.

### 1. Customizing Your Information

All the content of your portfolio is in the `index.html` file. To edit it:

1.  Navigate to the `index.html` file in your GitHub repository.
2.  Click the **pencil icon** (Edit this file) in the top right corner.
3.  You can now edit the file. Look for the placeholder text `[Your Name]`, `[Your Field]`, `[Your Hobbies]`, and `[your-email@example.com]` and replace it with your own information.
4.  Once you're done, scroll to the bottom of the page, add a short commit message (e.g., "Updated personal information"), and click **Commit changes**.

### 2. Adding a New Project

To add a new project to your portfolio, you'll need to copy and paste a block of code in the `index.html` file.

1.  Open `index.html` for editing as described above.
2.  Find the "My Projects" section. You'll see a comment that says: `<!-- To add a new project, copy the 'project' div above and paste it here. -->`.
3.  Copy the entire `div` block for a project. It looks like this:
    ```html
    <div class="project">
        <h3>Project Title</h3>
        <p>A short description of your project.</p>
        <!-- Link to a notebook -->
        <a href="projects/your-notebook.html" target="_blank">View Notebook</a>
        <!-- Or embed a video -->
        <video controls>
            <source src="videos/your-video.mp4" type="video/mp4">
        </video>
    </div>
    ```
4.  Paste this block below the existing projects and edit the content:
    *   Change the `<h3>` to your project's title.
    *   Update the `<p>` with your project's description.
    *   **Important**: Update the link (`href`) or video source (`src`) to point to your file.

### 3. Adding Jupyter Notebooks and Videos

#### How to Convert a Jupyter Notebook to HTML

Before you can add a Jupyter Notebook to your portfolio, you need to convert it to an HTML file.

1.  Open your notebook in Jupyter Notebook or JupyterLab.
2.  Go to **File** -> **Download as** (or **Export Notebook As...** in JupyterLab).
3.  Select **HTML (.html)**.
4.  This will download an HTML version of your notebook to your computer.

#### How to Upload Your Files

1.  In your GitHub repository, navigate to the directory where you want to upload the file (`projects/` for notebooks, `videos/` for videos).
2.  Click the **Add file** button and choose **Upload files**.
3.  Drag and drop your file(s) into the browser window or select them from your computer.
4.  Add a commit message (e.g., "Added new project notebook") and click **Commit changes**.

That's it! Your portfolio should now be updated with your new project.
