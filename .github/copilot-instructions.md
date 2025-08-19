# GitHub Profile Repository - Spencer Marcu

This is a GitHub profile repository that displays on Spencer Marcu's GitHub profile page. It contains profile information and personal branding content, not software applications or code that needs building or testing.

Always reference these instructions first and fallback to search or bash commands only when you encounter unexpected information that does not match the info here.

## Repository Structure and Purpose

This repository serves as Spencer Marcu's GitHub profile display. When users visit `github.com/spencermarcu`, the README.md content automatically appears on the profile page.

### File Structure
```
/
├── README.md          # Main profile content (displays on GitHub profile)
├── Spencer-Marcu      # Additional profile content/bio
└── .github/
    └── copilot-instructions.md  # This file
```

## Working Effectively

### Initial Setup and Validation
- Clone the repository: `git clone https://github.com/spencermarcu/SpencerMarcu.git`
- Navigate to directory: `cd SpencerMarcu`
- Verify file structure: `ls -la`
- Check file contents: `cat README.md && echo "---" && cat Spencer-Marcu`
- Validate file encoding: `file README.md Spencer-Marcu`

### No Build Process Required
- **CRITICAL**: This repository contains NO code to build, compile, or execute
- **DO NOT** attempt to run `npm install`, `make`, or any build commands
- **DO NOT** look for package.json, Makefile, or build scripts - they do not exist
- This is a content-only repository for GitHub profile display

### Content Editing and Maintenance
- Edit README.md for main profile content that displays on GitHub
- Edit Spencer-Marcu for additional biographical information
- Always use UTF-8 encoding for all files
- Keep content concise and professional
- Use proper Markdown formatting in README.md

### Content Validation Steps
After making content changes, ALWAYS validate:

1. **File Structure Validation**:
   ```bash
   ls -la
   # Should show: README.md, Spencer-Marcu, .git/, .github/
   ```

2. **Content Integrity Check**:
   ```bash
   wc -l README.md Spencer-Marcu
   # Verify reasonable line counts (README: ~20 lines, Spencer-Marcu: ~13 lines)
   ```

3. **File Encoding Validation**:
   ```bash
   file README.md Spencer-Marcu
   # Should show: UTF-8 text or ASCII text
   ```

4. **Markdown Syntax Validation**:
   ```bash
   # Manually review README.md for proper Markdown syntax
   # Check for: proper headers (##), bullet points (-), emphasis (*text*)
   cat README.md
   ```

5. **Git Status Check**:
   ```bash
   git --no-pager status
   # Verify changes are detected correctly
   ```

### GitHub Profile Display Testing
- **MANUAL VALIDATION REQUIREMENT**: After content changes, verify the profile displays correctly
- The README.md content will appear automatically on `github.com/spencermarcu`
- Check that Markdown renders properly (headers, lists, links, emphasis)
- Ensure content is professional and represents the intended personal brand

## Common Tasks

### Repository Root Contents
```bash
ls -la
```
Expected output:
```
.
..
.git/
.github/
README.md
Spencer-Marcu
```

### View Current Profile Content
```bash
cat README.md
```
Current content includes:
- Header: "# Spencer Marcu"
- Welcome message with wave emoji
- About Me section
- Skills & Technologies section
- Connect with Me section
- Footer note about repository purpose

### View Additional Bio Content
```bash
cat Spencer-Marcu
```
Contains professional identity statement and current focus areas.

### Check File Statistics
```bash
wc -l README.md Spencer-Marcu
```
Typical output: `20 README.md`, `13 Spencer-Marcu`

## Git Workflow for Profile Updates

### Making Content Changes
1. Edit files: `README.md` and/or `Spencer-Marcu`
2. Validate content as described above
3. Stage changes: `git add README.md Spencer-Marcu`
4. Commit: `git commit -m "Update profile content"`
5. Push: `git push origin main`

### Content Guidelines
- Keep README.md as the primary profile content
- Use Spencer-Marcu for supplementary biographical information
- Maintain professional tone throughout
- Use proper Markdown formatting for readability
- Keep content updated and relevant

## Important Notes

- **NO BUILD TIMES**: This repository has no build or compilation steps
- **NO TESTS**: No test suites exist or are needed for content-only repository
- **NO DEPENDENCIES**: No package managers, dependencies, or external tools required
- **NO APPLICATIONS**: No servers, CLIs, or applications to run or debug
- **CONTENT FOCUS**: All work involves editing and maintaining text content
- **GITHUB INTEGRATION**: Changes to README.md automatically update the profile page display

## Troubleshooting

### Common Issues
- **File encoding problems**: Always save files as UTF-8
- **Markdown not rendering**: Check for syntax errors in README.md
- **Content not updating on GitHub**: Ensure changes are committed and pushed to main branch
- **File permissions**: All content files should be readable (644 permissions)

### Validation Commands That Always Work
```bash
# Check repository status
git --no-pager status

# View file contents
cat README.md
cat Spencer-Marcu

# Verify file integrity
file README.md Spencer-Marcu
wc -l README.md Spencer-Marcu

# Check file permissions
ls -la README.md Spencer-Marcu
```

## What NOT to Do
- **DO NOT** look for or create package.json, Makefile, or build scripts
- **DO NOT** attempt to install dependencies or run build commands
- **DO NOT** search for application code, servers, or executables
- **DO NOT** try to run tests or linting tools that don't exist
- **DO NOT** create development environments or local servers
- **DO NOT** add complexity to this simple content repository

This repository is intentionally simple and serves a specific purpose as a GitHub profile display. Focus on content quality and proper Git workflow rather than software development practices.
