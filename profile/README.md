# Gravemind Labs

**Open source automation tools and integrations**

Gravemind Labs develops and maintains open source projects focused on infrastructure automation and API integrations. Our mission is to simplify complex integrations and make automation accessible through well-documented, reliable tools.

## 🚀 Projects

### Ansible Collections

We maintain Ansible collections that provide modules and plugins for managing third-party services:

- **[gravemind.microsoft_graph](https://github.com/Gravemind-Labs/gravemind.microsoft_graph)** - Manage Microsoft Graph resources via the Microsoft Graph API
  - Available on [Ansible Galaxy](https://galaxy.ansible.com/ui/repo/published/gravemind/microsoft_graph/)

- **[gravemind.wasp_barcode](https://github.com/Gravemind-Labs/gravemind.wasp_barcode)** - Manage WASP Barcode Technologies resources via the WASP Barcode API
  - Available on [Ansible Galaxy](https://galaxy.ansible.com/ui/repo/published/gravemind/wasp_barcode/)

## 📦 Installation

Install any of our Ansible collections from Ansible Galaxy:

```bash
ansible-galaxy collection install gravemind.microsoft_graph
ansible-galaxy collection install gravemind.wasp_barcode
```

Or add them to your `requirements.yml`:

```yaml
collections:
  - name: gravemind.microsoft_graph
  - name: gravemind.wasp_barcode
```

## 🤝 Contributing

We welcome contributions! Each project has its own contribution guidelines. Please check the individual repository for details.

All projects follow the [Ansible Code of Conduct](https://docs.ansible.com/ansible/latest/community/code_of_conduct.html).

## 📄 License

Unless otherwise specified, all projects are licensed under the GNU General Public License v3.0 or later. See individual repositories for specific licensing information.

## 🐛 Issues & Feedback

Found a bug or have a feature request? Please open an issue in the respective project repository.

## 📧 Contact

**Author**: Adam Brauns ([@AdamBrauns](https://github.com/AdamBrauns))

---

*Building reliable automation tools, one integration at a time.*
