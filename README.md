# Single hash is used to create heading 1 H1
## Double hashes for heading 2 H2
### Triple hashes for heading 3 H3 (up to H6)
- Dash (-) sign is used to create a bullet point
- **To write anything in BOLD** (** **)
```python
print("hello world")
```
- `print("for single line of code")`
- To add a link or URL - `[]()`

[GitHub Markdown Documentation Repo](https://github.com/RayWLMo/Eng_89_Markdown_Documentation)
- To add an image
- ![](https://logos-world.net/wp-content/uploads/2020/11/GitHub-Logo-700x394.png)

## Pushing to GitHub
Initialise a repo using PyCharm
- Use `git status` to ensure only the correct files are being added
- To add `git add .` for all files in folder, or `git add name_of_file` for a single file
- To save changes `git commit -m "message goes here"`
If you have not set remote branch to main
- You need to run `git branch -M main` after running the commit command
- To push changes to GitHub `git push -u origin main`
- Adding remote to connect localhost with GitHub repo
- `git remote add origin git@github.com:RayWLMo/Eng_89_Markdown_Documentation.git`

**Setting the branch to -M main and adding the remote is only to be done first time**