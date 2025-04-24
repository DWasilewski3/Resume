# Professional Resume Template

This repository contains a professional resume template that automatically generates both Markdown and PDF versions of your resume. The template is designed to be easily customizable while maintaining a clean, professional appearance.

## Features

- **Markdown-based**: Write your resume in simple Markdown format
- **Automatic PDF Generation**: GitHub Actions workflow automatically converts your resume to PDF
- **Responsive Design**: Clean, professional layout that works well in both digital and print formats
- **Easy Customization**: Simple to modify and personalize for your needs

## Getting Started

### Prerequisites

- A GitHub account
- Basic knowledge of Markdown syntax
- Git installed on your local machine (optional)

### Installation

1. Fork this repository to your GitHub account
2. Clone your forked repository to your local machine:
   ```bash
   git clone https://github.com/YOUR-USERNAME/Resume.git
   ```

## Customizing Your Resume

### Basic Customization

1. Edit `resume.md` with your personal information:
   - Replace the name, contact information, and links
   - Update the education section with your details
   - Add your professional experience
   - List your skills and projects
   - Include your extracurricular activities and volunteer work

2. The file uses standard Markdown syntax:
   ```markdown
   # Heading 1
   ## Heading 2
   **Bold text**
   *Italic text*
   [Link text](URL)
   - Bullet points
   ```

### Advanced Customization

#### Styling

The PDF generation uses a clean, professional style. If you want to modify the styling:

1. Edit the CSS in the GitHub Actions workflow file (`.github/workflows/rename-resume.yaml`)
2. The current styling includes:
   - Professional fonts (Arial)
   - Consistent spacing and margins
   - Clear hierarchy with different heading sizes
   - Proper link formatting
   - Clean list styling

#### PDF Generation

The PDF is automatically generated using GitHub Actions. The workflow:
1. Triggers on pushes to main branch
2. Converts Markdown to HTML
3. Applies custom styling
4. Generates a PDF using Puppeteer
5. Commits the PDF back to the repository

## Usage

### Local Development

1. Make changes to `resume.md`
2. Preview your changes using a Markdown viewer
3. Commit and push your changes:
   ```bash
   git add resume.md
   git commit -m "Update resume content"
   git push origin main
   ```

### Automatic PDF Generation

The PDF will be automatically generated when you:
- Push changes to the main branch
- Create a pull request to the main branch
- Manually trigger the workflow

You can find the generated PDF in:
1. The repository as `David_Wasilewski_Resume.pdf`
2. The GitHub Actions artifacts section

## Best Practices

1. **Keep it Professional**
   - Use clear, concise language
   - Focus on achievements and impact
   - Maintain consistent formatting

2. **Content Organization**
   - Start with most recent experiences
   - Use bullet points for clarity
   - Include relevant metrics and achievements

3. **Formatting Tips**
   - Use proper heading hierarchy
   - Keep line lengths reasonable
   - Use consistent date formats
   - Include relevant links to projects

4. **Version Control**
   - Make atomic commits
   - Write clear commit messages
   - Keep sensitive information out of the repository

## Troubleshooting

### Common Issues

1. **PDF Generation Fails**
   - Check GitHub Actions logs for errors
   - Ensure all Markdown syntax is valid
   - Verify links are properly formatted

2. **Formatting Issues**
   - Check for proper Markdown syntax
   - Ensure consistent spacing
   - Verify heading hierarchy

3. **Workflow Not Triggering**
   - Check repository permissions
   - Verify branch protection rules
   - Ensure workflow file is in correct location

## Contributing

Feel free to:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- GitHub Actions for automation
- Markdown for simple formatting
- Puppeteer for PDF generation
- All contributors who have helped improve this template 