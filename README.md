# unRAID Templates Repository

![IBRACORP Logo](https://raw.githubusercontent.com/ibracorp/unraid-templates/master/IBRACORP_Logo.png)

**Central storage for unRAID Community Applications Templates**

A comprehensive collection of Docker container templates for unRAID, maintained by the community and IBRACORP. These templates make it easy to deploy and manage applications on your unRAID server with just a few clicks.

## Quick Start

### Adding Templates to unRAID

Manually download individual `.xml` template files and place them in:
```
/boot/config/plugins/dockerMan/templates-user/
```

## Available Applications

Our template collection includes 54+ applications across multiple categories including Security & Authentication, Media & Entertainment, Productivity & Business, Development & DevOps, Gaming, and more.

📋 **[View Complete Template List by Category](docs/templates-by-category.md)**

For a comprehensive overview of all available templates organized by category, including descriptions and directory paths, see our detailed documentation.

## 🔧 Template Structure

Each template follows the unRAID XML format and includes:

- **Application metadata** (name, description, icon, project links)
- **Docker configuration** (image, networking, volumes)
- **Environment variables** with descriptions
- **Port mappings** for web interfaces and services
- **Volume mounts** for persistent data
- **Support and documentation links**

## 📖 Usage Instructions

### Installing an Application

1. Navigate to **Apps** tab in unRAID
2. Search for your desired application
3. Click **Install** on the template
4. Configure the required settings:
   - **Host paths** for persistent data storage
   - **Port mappings** (ensure no conflicts)
   - **Environment variables** (API keys, database connections, etc.)
5. Click **Apply** to deploy the container

### Common Configuration Tips

- **AppData Location**: Store persistent data in `/mnt/user/appdata/[app-name]/`
- **Port Conflicts**: Check existing containers to avoid port conflicts
- **Network Access**: Most templates use `bridge` networking by default
- **Updates**: Use the **Check for Updates** feature in Docker tab
- **Backups**: Regularly backup your `/mnt/user/appdata/` directory

## Contributing

We welcome contributions from the community! Here's how you can help:

### Adding New Templates

1. **Fork** this repository
2. Create a new branch: `git checkout -b add-new-template`
3. Add your template XML file to the appropriate category folder
4. Ensure your template follows our standards:
   - Clear descriptions and proper categorization
   - Working web UI links and port configurations
   - Proper volume mappings for data persistence
   - Required environment variables with descriptions
5. **Test** your template thoroughly on unRAID
6. Submit a **Pull Request** with:
   - Clear description of the application
   - Testing results and screenshots if applicable
   - Any special configuration requirements

### Template Standards

- Use descriptive names and clear overviews
- Include proper support and project links
- Set sensible defaults for ports and paths
- Document all required environment variables
- Test on latest unRAID stable release
- Include appropriate categories and icons

### Reporting Issues

- Use **GitHub Issues** for template problems
- Include unRAID version, template name, and error details
- Join our **Discord** for community support and real-time help

## Support & Community

- **Discord Community**: [https://discord.gg/VWAG7rZ](https://discord.gg/VWAG7rZ)
- **Documentation**: [https://docs.ibracorp.io](https://docs.ibracorp.io)  
- **YouTube Channel**: Educational content and tutorials
- **GitHub Issues**: Template-specific problems and feature requests

## Support Our Work

If these templates save you time and make your homelab better, consider supporting our continued development:

**Donate**: [https://paypal.me/ibracorp](https://paypal.me/ibracorp)

Your support helps us:
- Maintain and update existing templates
- Add new applications and features  
- Create educational content and documentation
- Provide community support

## License

This project is licensed under the **GNU General Public License v3.0** - see the [LICENSE](LICENSE) file for details.

### What this means:
- **Free to use** for personal and commercial purposes
- **Modify and distribute** under the same license terms
- **Access to source code** always guaranteed
- **Must provide source** if you distribute modifications
- **Same license** must be used for derived works

## Infrastructure

This repository serves templates for **unRAID Community Applications**, making it easy to deploy containerized applications on unRAID systems. Templates are automatically synced and available through the unRAID Apps interface.

### Repository Structure
```
├── README.md                    # This file
├── LICENSE                      # GPL v3 License
├── .gitignore                  # Git ignore patterns
├── ca_profile.xml              # Community Applications profile
├── [app-name]/                 # Individual application folders
│   └── [app-name].xml         # unRAID template file
└── icons/                      # Application icons and assets
```

---

**Made with ❤️ by the unRAID Community and IBRACORP**

*Join thousands of users who trust these templates for their homelab deployments*