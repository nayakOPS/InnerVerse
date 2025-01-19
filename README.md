# Nayak Blog

Welcome to the **Nayak Blog** repository! This is a personal blog built using the Hugo static site generator with the FixIt theme. The blog is designed to share insights, tutorials, and experiences in a clean and responsive layout.

## 🚀 Features
- Modern and responsive design using the **FixIt** theme.
- Easy to customize and extend.
- Lightning-fast build times with Hugo.

## 🛠️ Technologies Used
- **Hugo**: A fast static site generator.
- **FixIt Theme**: A feature-rich and responsive theme for Hugo blogs.
- **Markdown**: For content creation.
- **Git**: For version control and theme integration.

---

## 📥 Installation

Follow these steps to set up the project on your local machine:

### 1. Clone the Repository
```bash
git clone <repository-url> nayakblog
cd nayakblog
```

### 2. Initialize Git Submodules
Add the **FixIt** theme as a submodule:
```bash
git submodule add https://github.com/hugo-fixit/FixIt.git themes/FixIt
```

### 3. Install Hugo
Ensure you have the extended version of Hugo (0.140.0 or later). Verify installation:
```bash
hugo version
```
Refer to the [Hugo installation guide](https://gohugo.io/getting-started/installing/) if you need assistance.

### 4. Configure the Project
Update your `hugo.toml` configuration file to include:
```toml
theme = "FixIt"

[markup]
  _merge = "shallow"

[outputs]
  _merge = "shallow"

[taxonomies]
  _merge = "shallow"
```

---

## ▶️ Starting the Development Server
Run the Hugo development server to preview your site locally:
```bash
hugo server --disableFastRender
```

### Access the Blog
Once the server starts, visit [http://localhost:1313](http://localhost:1313) in your browser to see your blog.

---

## 📝 Creating New Content
To add a new post, use the following command:
```bash
hugo new content/posts/my-new-post.md
```
Edit the generated Markdown file in the `content/posts/` directory to write your content.

---

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).

---

## 👥 Contributors
- **Your Name**

Feel free to fork this repository and contribute to its development!

---

## 🙋‍♂️ Questions?
If you have any questions or need help, please feel free to contact me or raise an issue in this repository.
