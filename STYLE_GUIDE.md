# Code Style Guide - NguyenHoangPhuc

## JavaScript/TypeScript Style
- Use semicolons
- 2 spaces indentation
- Single quotes for strings
- CamelCase for variables and functions
- PascalCase for classes and components

## Git Commit Convention
```
type(scope): description

Types: feat, fix, docs, style, refactor, test, chore
Examples:
- feat: add user authentication
- fix: resolve login bug
- docs: update README
```

## Code Review Checklist
- [ ] Code follows style guide
- [ ] No console.log left in production code
- [ ] Functions have proper JSDoc comments
- [ ] Error handling implemented
- [ ] Tests written for new features

## File Naming
- Components: PascalCase (UserProfile.js)
- Utilities: camelCase (formatDate.js)
- Constants: UPPER_SNAKE_CASE
- Folders: kebab-case