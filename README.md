# ARIN 310 Interactive Review

An interactive review of **ARIN 310: Introduction to Artificial Intelligence**, designed for students who want to revisit the course or prepare for the next course in the AI series. No coding or mathematics background is required.

Explore eight units through an expandable mind map, select concepts to read explanations, reflect on real-world examples, and answer practice questions with immediate feedback.

**[Open the interactive review](https://cynthialmcginnis.github.io/arin-310-mindmap/)**

## What is included

- Eight unit branches and 54 concept sections
- Expand and collapse controls, zoom controls, and keyword search
- Course explanations, timeline, comparison tables, and glossary
- Reflection notes for each concept
- 24 practice questions with answer explanations and opportunities to retry
- Separate tracking of concepts marked reviewed and quiz questions answered correctly
- Progress export and import for moving between devices or browsers

## Course units

| Unit | Topic |
| --- | --- |
| 1 | Background, Introduction, and Definition of AI |
| 2 | Machine Learning and Deep Learning |
| 3 | Natural Language Processing and Generative AI |
| 4 | Computer Vision and Reinforcement Learning |
| 5 | Recommender Systems |
| 6 | Robotics and Robotic Process Automation |
| 7 | Applications of AI |
| 8 | The Future of AI |

## How to use the review

1. Select a unit to open or close its branch.
2. Select a concept to read its explanation in the review panel.
3. Use **Make the connection** to explain the idea in your own words, give an example from work or daily life, and identify a limitation or question.
4. Select **Mark this concept reviewed** when you are ready to move on. Select it again to undo the mark.
5. Open **Unit overview** and select **Try unit quiz** to check your understanding. You can retry questions after reading the feedback.
6. Use **Search**, **Expand all**, **Collapse all**, the **+ / −** controls, or **Fit map** to explore. Scroll within the map to reach additional branches.
7. Select **Glossary** for definitions or **Overview** to see your progress across all units.

This is a self-study activity. Marking a concept reviewed records your own judgment; it does not certify mastery. Quiz results are practice feedback, not a course grade.

## Progress and privacy

The review attempts to save your notes, reviewed concepts, and latest quiz answers in your browser's local storage. The activity does not send these records to an instructor or a server.

- Progress is specific to the browser and website location. It does not automatically synchronize between devices or between the downloaded and hosted versions.
- Private browsing, browser settings, or clearing browser data may prevent saving or remove saved progress.
- Select **Export progress** to download an `ARIN310-review-progress.json` backup.
- On another device or browser, open the review and select **Import progress** to load that backup. Importing replaces the current review progress after confirmation.
- **Reset progress** clears the activity's notes, reviewed marks, and quiz answers after confirmation.

Exported progress files include your written reflections and answers. Share them only when you intend to share that information. GitHub's own hosting practices are separate from the activity's local progress storage.

## Run locally

Download the HTML file and open it in a modern browser. If it is named `index.html`, double-click that file.

The entire activity is contained in one HTML file. It requires no internet connection when opened locally, installation, account, API key, live LLM, or external JavaScript library. If browser storage is unavailable, use progress export and import to keep your work.

## Publish with GitHub Pages

For a dedicated repository, use these two files at the repository's top level:

| File | Purpose |
| --- | --- |
| `index.html` | The interactive review; rename `ARIN310_Interactive_Review.html` to this filename |
| `README.md` | This project description and usage guide |

1. Upload both files to your repository and commit them.
2. Open the repository's **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Select the branch containing your files, usually **main**, and select **/(root)**.
5. Select **Save**. After deployment, share the published link shown in the Pages settings with students.

See GitHub's official instructions for [creating a Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site) and [configuring its publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

If you add this review to an existing website, keep that site's current home page. Upload the review as `ARIN310_Interactive_Review.html` and link to that filename instead. Update the **Open the interactive review** link above accordingly.

## Classroom ideas

- **Before class:** Review one unit and write an example from your workplace.
- **During class:** Compare explanations with a partner and discuss a limitation of the technology.
- **Course transition:** Revisit the eight units before beginning the next ARIN course.
- **Retrieval practice:** Try a unit quiz before reading, revisit unfamiliar concepts, and try again.

## Content and implementation

Adapted from **ARIN 310 in Review: What You Learned and What You Carry Forward**. Practice questions and reflection prompts were added for this interactive version. The HTML and JavaScript were developed with assistance from ChatGPT.

The activity uses HTML, CSS, JavaScript, and SVG. All review content and questions are embedded in the HTML file; no build process or backend is required. It uses fixed content and answer feedback rather than generating responses with an AI model.

AI policy, products, and capabilities change over time. Treat the review as a course learning resource and consult current primary sources for time-sensitive claims.
