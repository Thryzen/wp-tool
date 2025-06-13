# wp-tool

**A personal, evolving utility plugin for WordPress.**

`wp-tool` is a lightweight and extensible WordPress plugin designed to enhance your site with simple but useful features. Built to serve personal needs, it will continue to grow with additional functionalities over time.

---

## ✨ Features

* **📩 Inline Email Sender**
  Add a customizable email-sending form directly inside your posts or pages using a shortcode.

* **🔐 User Login Restriction**
  Prevent non-administrator users from logging into the WordPress admin area.

* **🌍 Display IP Location in Comments (Experimental)**
  Non-invasively show the IP-based location next to each commenter's username beneath posts.

  > Currently suitable for sites with a small number of comments per post. This feature is still in an experimental phase.

* **💬 Tooltip-Style Inline Annotations**
  Add brief explanations for terms or concepts directly within the text.
  On desktop, hovering will show the annotation; on mobile, users can tap to reveal it.
  Helps clarify without disrupting the article’s structure or flow.

* **🛠️ Extensible by Design**
  This plugin is under continuous development, and new features will be added as needed based on personal or project-specific requirements.

---

## 🔧 Installation

1. Upload the plugin folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the WordPress admin dashboard.
3. Configure settings if applicable (some features may work out-of-the-box).

---

## 📌 Usage

### Embed Email Form

Use the following shortcode in any post or page to display the email-sending component:

```plaintext
[send_email_form]
```

> Additional options and customization may be added in future updates.

### Add Tooltip Annotations

Use this shortcode to annotate terms inline with additional explanations:

```plaintext
[tooltip tip="Your explanation here"]Text to annotate[/tooltip]
```

The explanation appears on hover (desktop) or tap (mobile), allowing you to add context without breaking the reading rhythm.

---

## 🧪 Development Philosophy

This plugin is not designed to be a general-purpose toolset for all users, but rather a personal utility plugin. Features are added based on subjective needs and may not follow a public roadmap. However, it's cleanly written, modular, and may still be useful for others with similar needs.
