<div align="center">

<img src="assets/v-icon.png" width="80" height="80" alt="Veldora Logo">

# Veldora UI

**Accessible, copy-and-paste UI components for the Veldora PHP Framework.**

Inspired by shadcn/ui • 41+ Ready-to-Use Components • Pure CSS & Tailwind-Compatible • You Own the Code

[![License: MIT](https://img.shields.io/badge/License-MIT-8b5cf6?style=flat-square)](LICENSE)
[![PHP Version](https://img.shields.io/badge/PHP-8.2%2B-777BB4?style=flat-square&logo=php&logoColor=white)](https://php.net)
[![Version](https://img.shields.io/badge/version-0.5.2-7c6ef5.svg?style=flat-square)](https://github.com/veldorahq/veldora-ui)

</div>

---

## ✦ Philosophy

1. **You Own Every Component** — When you run `php veldora add button`, the component template is copied directly into `resources/views/components/`. You can edit, style, and customize it without restrictions.
2. **Zero Runtime Dependencies** — Components use semantic HTML and scoped CSS custom properties (`var(--vui-*)`).
3. **Full Keyboard Accessibility** — Every interactive component supports focus rings, ARIA roles, and standard keyboard navigation.

---

## 🚀 Installation & Usage

Inside any Veldora project:

```bash
# List all 41+ available components
php veldora ui:list

# Add specific components
php veldora add button card modal badge alert tabs footer rating
```

Then use directly in your `.veldora.php` views:

```html
<x-card title="Profile Settings">
    <p>Manage your account credentials and personal preferences.</p>
    <x-button variant="primary" size="md">Save Changes</x-button>
</x-card>

<x-footer brand="My App" tagline="Built with Veldora"></x-footer>
```

---

## 📦 Available Components (41+)

| Category | Components |
|---|---|
| **Layout & Structure** | `card`, `accordion`, `tabs`, `breadcrumb`, `navbar`, `sidebar`, `container`, `divider`, `footer` |
| **Actions & Triggers** | `button`, `dropdown`, `popover` |
| **Feedback & Overlays** | `alert`, `badge`, `modal`, `drawer`, `toast`, `spinner`, `progress`, `tooltip`, `skeleton`, `empty`, `confirm` |
| **Forms & Inputs** | `input`, `textarea`, `select`, `checkbox`, `radio`, `switch`, `datepicker`, `fileupload`, `combobox`, `inputgroup`, `rating` |
| **Data & Navigation** | `table`, `datatable`, `pagination`, `timeline`, `stepper`, `stat`, `avatar` |

---

## 📄 License & Author

- **Author**: Shahriyar Fahim
- **License**: [MIT](LICENSE)
- **Website**: [https://veldora.modrao.com](https://veldora.modrao.com) *(temporary — permanent domain coming soon)*
