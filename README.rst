My Resume Repository
====================

This repository contains my `Resume PDF file <Dipin_KN_Resume.pdf>`_  and its LaTeX format. I have used GitHub Actions workflow to generate a PDF and display it using GitHub Pages.

Instructions
------------

1. **Fork the Repository:** Click on the "Fork" button at the top right corner of this repository to create your own copy.

2. **Set up GitHub Pages:** In your forked repository, go to the "Settings" tab and scroll down to the "GitHub Pages" section. Select the `main` branch as the source and click "Save". GitHub Pages will now host your page which is basically index.html ( embedded pdf).Change the page url -> your github.io/resume . For more infor please see the picture below

   .. image:: github_page_setup.jpg
      :alt: GitHub Page Setup

3. **Configure Actions Environment:** In your forked repository, go to the "Settings" tab and click on "Secrets" in the left sidebar. Add the following secrets:

   - `ACTOR`: The name of the PDF file. It will be in the format `name_Resume.pdf`.
   - `USERNAME`: Your GitHub username.
   - `EMAIL`: Your GitHub email address.

4. **Grant Repo Permission:** Go to the "Settings" tab of your forked repository and click on "Manage access" in the left sidebar. Add the appropriate permissions to the "GitHub Actions" user, such as "Read" and "Write" access.

5. **Modify Main.latex:** Open the `main.tex` file in your forked repository and make any desired changes to your resume content.

6. **Trigger GitHub Actions Workflow:** Once you have made changes to `main.tex`, commit and push the changes to the `main` branch. This will trigger the GitHub Actions workflow, which will compile the LaTeX document and push the generated PDF to the repository.


Contributing
------------

Feel free to contribute to this repository by submitting pull requests. If you have any suggestions or issues, please open an issue in the issue tracker.

License
-------

This project is licensed under the MIT License. See the LICENSE file for more details.
