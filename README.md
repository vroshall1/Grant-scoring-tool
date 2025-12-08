# Grant Scoring GPT

AI-Powered Grant Proposal Analysis & Rubric Alignment Tool

## Overview

Grant Scoring GPT is a web-based tool designed to help agencies and vendors improve their grant proposals by analyzing them against scoring rubrics. The tool provides detailed feedback, identifies strengths and weaknesses, and offers actionable recommendations to increase grant success rates.

## Features

- **Multi-Criteria Analysis**: Evaluates proposals across 4 key criteria:
  - Program Design & Innovation (30%)
  - Organizational Capacity (20%)
  - Budget & Sustainability (25%)
  - Impact & Evaluation (25%)

- **Detailed Feedback**: Provides comprehensive analysis including:
  - Overall weighted score (0-100)
  - Criterion-by-criterion breakdown
  - Identified strengths
  - Areas for improvement
  - Specific recommendations
  - Missing elements checklist

- **Export Capabilities**: Download detailed analysis reports in text format

- **Analysis History**: Track multiple proposals and compare scores over time

## Demo

Visit the live demo: `https://yourusername.github.io/grant-scoring-tool`

## Installation

### Option 1: GitHub Pages (Recommended)

1. Fork this repository
2. Go to Settings → Pages
3. Enable GitHub Pages from the `main` branch
4. Your site will be available at `https://yourusername.github.io/grant-scoring-tool`

### Option 2: Local Development

1. Clone the repository:
```bash
git clone https://github.com/yourusername/grant-scoring-tool.git
```

2. Open `index.html` in your web browser

No build process or dependencies required!

## Usage

1. **Upload Documents**:
   - Upload your grant proposal (PDF, Word, or text format)
   - Upload the grantor's rubric OR use the sample rubric provided

2. **Analyze**:
   - Click "Analyze Proposal" to generate comprehensive feedback
   - Analysis takes approximately 3-4 seconds

3. **Review Results**:
   - View overall score and detailed breakdown by criteria
   - Read key insights and critical gaps
   - Review specific recommendations for each section

4. **Export & Iterate**:
   - Export detailed report for reference
   - Revise your proposal based on feedback
   - Re-analyze to track improvements

## Technical Details

- **Frontend**: React 18 (loaded via CDN)
- **Styling**: Custom CSS (no framework dependencies)
- **Build**: None required - single HTML file
- **Browser Support**: Modern browsers (Chrome, Firefox, Safari, Edge)

## Current Limitations

- Uses simulated AI analysis (not connected to live AI API)
- Scores are generated randomly within realistic ranges
- Does not actually parse rubric content (uses standardized criteria)
- For demonstration and training purposes

## Future Enhancements

- Real AI integration (Claude API or OpenAI GPT-4)
- Dynamic rubric parsing
- User authentication and data persistence
- Team collaboration features
- Custom rubric templates
- Integration with grant management systems

## Integration with TalentLMS

### Free Plan Compatible Options:

1. **External Link**: Add as a unit with link to GitHub Pages URL
2. **iFrame Embed**: Use the GitHub Pages URL in an iFrame unit
3. **Direct Link**: Add button/link in course content pointing to the tool

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is part of the Skills of Success Training Platform.

## Support

For questions or support, please contact: [your-email@example.com]

## Acknowledgments

- Built for workforce development agencies and grant writers
- Designed to improve grant success rates through AI-powered analysis
- Part of the Skills of Success Training Platform initiative

---

**Note**: This is a demonstration tool. For production use with real AI analysis, API integration is required.
