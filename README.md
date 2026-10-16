# Content Effort Evaluator

Evaluate content effort, originality and information gain using Google Gemini 2.5 Flash.

Content Effort Evaluator is a browser based tool designed to help SEO specialists, content writers and website owners assess the quality and usefulness of their content. It generates an effort score out of 100 and provides actionable recommendations for improvement.

## Features

- Evaluate content using a target URL, plain text or HTML source.
- Upload HTML, HTM and TXT files for analysis.
- Assess research depth and information value.
- Evaluate originality and unique insights.
- Review content structure and readability of the page layout.
- Measure alignment with search intent and context.
- Generate a score out of 100 with an effort category.
- Receive actionable content improvement suggestions.
- Use a responsive interface for desktop and mobile devices.
- Demo- https://selvaarchunan.github.io/content-effort-evaluator/

## Evaluation Dimensions

1. Research Depth: Thoroughness, supporting data and citations.
2. Original Thought: Unique perspectives and value beyond generic summaries.
3. Structural Utility: Content hierarchy, formatting and scanability.
4. Context and Intent Fit: Alignment with expected user intent.

## How to Use

1. Download or clone this repository.
2. Open `Content Effort Evaluator Score.html` in a modern web browser.
3. Obtain a Google Gemini API key.
4. Enter your API key in the tool.
5. Provide a target URL, article text or HTML source.
6. Click **Calculate Effort Score**.
7. Review your score, evaluation breakdown and recommendations.

You only need to provide a URL or content. You do not need to supply both.

## Technology Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Google Gemini API
- Gemini 2.5 Flash

## Run Locally

No build tools or package installation are required.

Open the HTML file directly in your browser. An internet connection is required for Google Fonts and Gemini API requests.

## Deployment

You can deploy this project using GitHub Pages.

1. Upload the project files to a public GitHub repository.
2. Open repository Settings.
3. Navigate to Pages.
4. Select the deployment branch and root folder.
5. Save the configuration and use the published URL.

## API Key and Security

This tool requests a Google Gemini API key in the browser and sends it to Google's Gemini API.

- Never share your API key or commit it to the repository.
- Avoid using this approach for a public production service, because visitors can inspect browser code and API requests.
- For a production deployment, use a backend to protect the API key.
- Review Google's API pricing, quotas and applicable terms before use.

## Limitations

The score is an AI generated assessment, not an objective measurement of editorial effort or a guarantee of search rankings. URL only assessments may lack the actual page content, depending on the information supplied to the model. Recommendations should be reviewed by a human editor.

## Contributing

Contributions, bug reports and feature suggestions are welcome. Fork the repository, create a branch, make your changes and submit a pull request.

## Licence

This project is available under the MIT Licence once the repository owner adds an MIT `LICENSE` file.

---

Built for SEO specialists, content strategists and website owners who want to improve content quality and information gain.
