# Contributing to Awesome Native macOS Apps

First off, thank you for considering contributing to this list! It's people like you that make this resource valuable for the macOS community.

## Table of Contents

- [How Can I Contribute?](#how-can-i-contribute)
- [Submission Guidelines](#submission-guidelines)
- [App Requirements](#app-requirements)
- [Formatting Guidelines](#formatting-guidelines)
- [Pull Request Process](#pull-request-process)

## How Can I Contribute?

### Suggesting an App

1. **Search first**: Check if the app is already listed or has been suggested
2. **Create an issue**: Use the "App Suggestion" template
3. **Or submit directly**: Create a pull request with your addition

### Improving Descriptions

Found a typo or want to improve an app description? Feel free to submit a PR!

### Reporting Issues

- Broken links
- Apps that are no longer maintained
- Apps that don't meet the native criteria
- Outdated information

## Submission Guidelines

### What We're Looking For

Apps that are:
- ✅ **Native** - Built with Swift, SwiftUI, AppKit, or Objective-C
- ✅ **Lightweight** - Resource-efficient and fast
- ✅ **Well-designed** - Follow macOS Human Interface Guidelines
- ✅ **Actively maintained** - Updated within the last 2 years
- ✅ **Functional** - Actually useful and works well

### What We Don't Accept

- ❌ Electron apps (with rare exceptions for exceptional apps)
- ❌ Web wrappers
- ❌ Abandoned projects (no updates in 2+ years)
- ❌ Apps with malware, adware, or suspicious behavior
- ❌ Poorly designed apps
- ❌ Your own app (unless it's truly exceptional) - we value third-party recommendations

## App Requirements

Before submitting an app, ensure it meets these criteria:

1. **Native Technology**: Built with macOS-native frameworks
   - Swift, SwiftUI, AppKit, Objective-C
   - May use native web views (WebKit) for specific features
   - Should feel native, not like a web page

2. **Performance**: 
   - Lightweight (< 200MB typical)
   - Low resource usage
   - Fast startup and response times

3. **Availability**:
   - Downloadable and installable
   - Works on currently supported macOS versions
   - Has a stable release (not just alpha/beta)

4. **Maintenance**:
   - Updated within the last 2 years
   - Active development or maintenance
   - Responsive to critical bugs

5. **Quality**:
   - Stable and reliable
   - Good user reviews/reputation
   - Proper macOS integration

## Formatting Guidelines

### App Entry Format

```markdown
[App Name](https://app-website.com) - Brief one-line description. `Pricing`
```

**Examples:**
```markdown
[Bear](https://bear.app/) - Beautiful, flexible writing app. `Freemium`
[Things](https://culturedcode.com/things/) - Award-winning task manager. `Paid`
[Maccy](https://github.com/p0deje/Maccy) - Lightweight clipboard manager. `Free` `Open Source`
```

### Pricing Labels

Use ONE of these labels:
- `Free` - Completely free with no paid features
- `Free` `Open Source` - Free and open source
- `Freemium` - Free with optional paid features
- `Freemium` `Open Source` - Open source with optional paid features
- `Paid` - One-time purchase
- `Subscription` - Requires ongoing subscription

### Description Guidelines

- **One line only** - Keep it concise (< 100 characters)
- **Focus on what it does** - Not marketing speak
- **Be objective** - Avoid subjective terms like "the best"
- **No emojis** - Keep it professional
- **Proper grammar** - Check spelling and punctuation

**Good descriptions:**
- ✅ "Control external monitor brightness like native displays."
- ✅ "Native code editor for macOS."
- ✅ "Advanced IMAP email client with keyboard control."

**Bad descriptions:**
- ❌ "The best app ever! 😍"
- ❌ "Revolutionary groundbreaking amazing tool"
- ❌ "You absolutely need this app"

## Pull Request Process

### 1. Fork the Repository

Click the "Fork" button at the top right of the repository page.

### 2. Create a Branch

```bash
git checkout -b add-app-name
```

### 3. Make Your Changes

- Add your app to the appropriate category
- Maintain alphabetical order within categories
- Follow the formatting guidelines exactly

### 4. Test Your Changes

- Preview your changes in Markdown
- Verify all links work
- Check for typos

### 5. Commit Your Changes

```bash
git add README.md
git commit -m "Add [App Name] to [Category]"
```

Use clear commit messages:
- ✅ "Add Bear to Note-Taking & Writing"
- ✅ "Update Things description"
- ✅ "Fix broken link for IINA"
- ❌ "Update"
- ❌ "Changes"

### 6. Push to GitHub

```bash
git push origin add-app-name
```

### 7. Create Pull Request

- Go to the original repository
- Click "New Pull Request"
- Select your branch
- Fill in the PR template
- Submit!

### PR Checklist

Before submitting, ensure:
- [ ] App is truly native (not Electron/web wrapper)
- [ ] App is in the correct category
- [ ] Alphabetically ordered within category
- [ ] Follows formatting guidelines exactly
- [ ] Description is concise and objective
- [ ] Link works and points to official site/repo
- [ ] Pricing label is accurate
- [ ] No duplicate entries
- [ ] Commit message is clear

## Review Process

1. **Automated checks** - Link checker, formatting validation
2. **Maintainer review** - We'll verify the app meets our criteria
3. **Feedback** - We may request changes
4. **Merge** - Once approved, we'll merge your PR!

Typical review time: 1-7 days

## Adding New Categories

Want to suggest a new category? Open an issue first to discuss:
- Why it's needed
- What apps would go in it
- How it differs from existing categories

## Questions?

- 💬 **Discussion**: Use [GitHub Discussions](../../discussions)
- 🐛 **Issues**: Create an [issue](../../issues/new)
- 📧 **Email**: (Add your contact email if you want)

## Recognition

Contributors are recognized in:
- GitHub's contributor graph
- Release notes when applicable
- Our gratitude! ⭐

## Code of Conduct

- Be respectful and constructive
- No spam or self-promotion
- No offensive language
- Follow GitHub's [Community Guidelines](https://docs.github.com/en/site-policy/github-terms/github-community-guidelines)

## Thank You!

Every contribution, no matter how small, helps make this list better for the macOS community. We appreciate your time and effort! 🙏