# Clone

Cloning means to download a project from a remote repository to your local machine. This allows you to access the full project history, make changes, and work on it offline.

## How to Clone a Repository

To clone a repository using Git, follow these steps:

1. **Get the repository URL**  
   Go to the repository page (e.g., on GitHub) and copy the HTTPS or SSH URL.

2. **Open your terminal**  
   Navigate to the directory where you want to store the project.

3. **Run the clone command**  
   ```git clone <repository-url>```

Replace `<repository-url>` with the URL you copied.

4. **Access the cloned project**

   ```<repository-name>```

   This will take you into the project's folder.

## Example

```
git clone https://github.com/username/project.git
cd project
```

## Notes

* Cloning downloads the full history of the project, not just the latest version.
* After cloning, you can create new branches, commit changes, and push them back to the remote repository.
