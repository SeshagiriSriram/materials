## Lab 02: DevOps Workflow

### Prerequisites
- [Git](https://git-scm.com/) installed
- GitHub account
- [Docker](https://www.docker.com/) installed
- Docker Hub account

### Steps

1. **Fork the Repository**  
   Fork [Sriram's Sample App](https://github.com/seshagirisriram/bmiapp) to your GitHub account.

2. **Clone Your Fork Locally**  
   ```sh
   git clone https://github.com/<your-username>/bmiapp.git
   ```

3. **Make a Change**  
   Edit any file in the `src` folder.
   > **Note:**  
   > Before pushing your changes, review your workflow file and ensure:
   > - Repository names referenced in the workflow are correct.
   > - Your repository contains all required secrets as specified in the workflow file.

4. **Push Your Changes**  
   ```sh
   git add .
   git commit -m "Describe your change"
   git push
   ```

5. **Check GitHub Actions**  
   Go to the **Actions** tab in your repository to observe the workflow.

---

*Feel free to ask questions or raise issues if you get stuck!*