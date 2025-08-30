# Portfolio Website

This is a personal portfolio website showcasing my work as a front-end developer. The website is built with a focus on a clean, modern design and is fully responsive for all device sizes.

---

### 🚀 Technologies Used

* **HTML5**: For the fundamental structure of the web pages.
* **Tailwind CSS**: A utility-first CSS framework for rapid styling and responsive design.
* **Git**: For version control.
* **VS Code**: The code editor used for development.

---

### ✨ Features

* **Responsive Design**: The website is optimized to look great on desktop, tablet, and mobile devices.
* **Multi-Page Layout**: Includes dedicated sections for Home, About Me, Portfolio, and Contact.
* **Modern Styling**: Utilizes a dark theme with a vibrant accent color to create a polished, professional look.

---

### 📦 Project Structure

The project follows a simple, flat file structure for static web pages:
```bash
/
├── src/
│   ├── input.css
│   └── output.css
├── about.html
├── contact.html
├── index.html
├── portfolio.html
├── .gitignore
├── .gitattributes
├── package.json
├── package-lock.json
└── README.md
```
* `src/input.css`: The source file where Tailwind's directives are included.
* `src/output.css`: The generated CSS file with all the Tailwind styles.
* `.html` files: Each page of the website.

---

### 🛠️ Getting Started

#### Prerequisites

You need to have **Node.js** and **npm** installed on your machine to use Tailwind CSS.

#### Installation

Clone the repository:

```bash
git clone [Your Repository URL]
cd [Your Repository Folder]
```
Install dependencies:
```
npm install
```
### Running the Project
#### Generate Tailwind CSS:
Run the following command in your terminal to generate the output.css file from your Tailwind classes. The --watch flag will automatically re-generate the file on every save. This command should be kept running in your terminal while you are developing.
```
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```

#### Open the files:
Simply open the index.html file (or any other .html file) in your web browser to view the project.
#### 🤝 Git Workflow
The project uses a standard Git workflow for managing new features and changes. All development is done on a separate feature branch, which is then merged into the main branch after a pull request has been submitted and approved.

#### Creating a new feature branch
```
git checkout main
git checkout -b feat/your-feature-name
```

#### Committing and Pushing Changes
After making changes, add and commit your files to the new branch. Then push the branch to your remote repository.
```
git add .
git commit -m "feat: your descriptive message"
git push -u origin feat/your-feature-name
```

#### Submitting a Pull Request
* On the GitHub website, navigate to your repository.

* You will see a banner prompting you to create a new pull request from your recently pushed branch. Click the "Compare & pull request" button.

* Add a clear title and description for your changes, then click "Create pull request."

#### 📄 License
This project is licensed under the MIT License.