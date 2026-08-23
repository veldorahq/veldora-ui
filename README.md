<div align="center">

<img src="https://raw.githubusercontent.com/veldorahq/veldora-ui/main/assets/v-icon.png" width="80" height="80" alt="Veldora Logo">

# Veldora UI

**Accessible, copy-and-paste UI components for the Veldora PHP Framework.**

Inspired by shadcn/ui • 21 Ready-to-Use Components • Pure CSS & Tailwind-Compatible • You Own the Code

[![License: MIT](https://img.shields.io/badge/License-MIT-8b5cf6?style=flat-square)](LICENSE)
[![PHP Version](https://img.shields.io/badge/PHP-8.2%2B-777BB4?style=flat-square&logo=php&logoColor=white)](https://php.net)
[![Docs](https://img.shields.io/badge/Documentation-veldora.modrao.com%2Fcomponents-10B981?style=flat-square)](https://veldora.modrao.com/components)

</div>

---

## ✦ Philosophy

1. **You Own Every Component** — When you run `php veldora add button`, the component template is copied directly into `resources/views/components/`. You can edit, style, and customize it without restrictions.
2. **Zero Runtime Dependencies** — Components use semantic HTML and scoped CSS custom properties (`var(--v-*)`).
3. **Full Keyboard Accessibility** — Every interactive component supports focus rings, ARIA roles, and standard keyboard navigation.

---

## 🚀 Installation & Usage

Inside any Veldora project:

```bash
# List all 21 available components
php veldora ui:list

# Add specific components
php veldora add button card modal badge alert tabs
```

Then use directly in your `.veldora.php` views:

```html
<x-card title="Profile Settings">
    <p>Manage your account credentials and personal preferences.</p>
    <x-button variant="primary" size="md">Save Changes</x-button>
</x-card>
```

---

## 📦 Available Components (21)

| Category | Components |
|---|---|
| **Layout & Structure** | `card`, `accordion`, `tabs`, `breadcrumb`, `navbar` |
| **Actions & Triggers** | `button`, `dropdown` |
| **Feedback & Overlays** | `alert`, `badge`, `modal`, `drawer`, `toast`, `spinner`, `progress`, `tooltip` |
| **Forms & Inputs** | `input`, `textarea`, `select`, `checkbox`, `radio` |
| **Media & Content** | `avatar` |

---

## 📄 License & Author

- **Author**: Shahriyar Fahim
- **License**: [MIT](LICENSE)
- **Website**: [https://veldora.modrao.com](https://veldora.modrao.com)
