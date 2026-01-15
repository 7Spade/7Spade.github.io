---

SKILLS.md — Angular 20.0.0

---
name: angular-v20
description: Skills for working with Angular v20.0.0, including components, modules, routing, reactive programming, and Material integration.
license: MIT
---

# Angular v20 Skill

This skill helps GitHub Copilot understand how to assist with **Angular v20** projects and provides coding patterns, best practices, and guidance.

## 📦 Package Info

- Package: `@angular/core`  
- Version: `20.0.0`  
- Peer dependencies: `@angular/common`, `@angular/forms`, `@angular/platform-browser`, `@angular/platform-browser-dynamic`  
- Optional: `@angular/material: "~20.0.0"`, `@angular/cdk: "~20.0.0"`

## 🎯 Covered Areas

### 1️⃣ Core Angular

- Components, Templates, Directives, Pipes
- Modules (NgModule, Feature Modules, Shared Modules)
- Dependency Injection & Services
- Lifecycle Hooks (`ngOnInit`, `ngAfterViewInit`, etc.)

### 2️⃣ Routing & Navigation

- RouterModule configuration
- Lazy loading modules
- Route guards (CanActivate, CanDeactivate)
- Parameterized routes
- Reactive navigation patterns with Signals

### 3️⃣ Forms

- Template-driven forms
- Reactive forms
- Validation patterns
- Integration with Angular Material form controls

### 4️⃣ HTTP & State Management

- HttpClient usage (GET, POST, PUT, DELETE)
- Interceptors for headers, auth, logging
- RxJS Observables, Subjects, Operators
- Signals or NgRx store patterns for reactive state management

### 5️⃣ Angular Material (Optional)

- Material Components: Buttons, Inputs, Forms, Tables, Dialogs, Snackbars, Tooltips
- Theming: light/dark mode, custom SCSS variables
- Accessibility & responsive design patterns

### 6️⃣ Best Practices

- Modular imports (avoid importing everything globally)
- Use `BrowserAnimationsModule` when using Material components
- Lazy loading for performance
- Reactive programming principles
- Testing (Unit and E2E) for components, services, routing

### 7️⃣ Troubleshooting Tips

- Dependency version mismatches
- Missing modules or animations errors
- Correct imports in `app.module.ts` or feature modules

---


---

📍 建議放置路徑

專案內 (Project Skill)

<your-project>/.github/skills/angular-v20/SKILLS.md

個人共用 (Personal Skill)

~/.copilot/skills/angular-v20/SKILLS.md
或
~/.claude/skills/angular-v20/SKILLS.md

> 放在這些路徑，Copilot/Claude 就能在你開發 Angular 20 專案時自動讀取技能提示，生成程式碼更聰明 😎💖