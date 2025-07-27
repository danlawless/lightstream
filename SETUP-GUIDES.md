# 📚 Light Stream Ministry - Documentation Setup Guide

This guide will help you set up all three documentation systems for maximum accessibility and sharing options.

---

## 🌍 **GitHub Pages Setup** (Beautiful Website)

### **Quick Setup** (5 minutes)
1. **Go to Repository Settings**
   - Navigate to your repository on GitHub
   - Click "Settings" tab
   - Scroll down to "Pages" section

2. **Enable GitHub Pages**
   - Source: Deploy from a branch
   - Branch: `main` (or `master`)
   - Folder: `/ (root)`
   - Click "Save"

3. **Customize Your Site**
   - Edit `_config.yml` and update these lines:
     ```yaml
     url: "https://YOUR-USERNAME.github.io"
     baseurl: "/YOUR-REPO-NAME"
     author:
       email: "your-email@example.com"
     ```

4. **Your Site Will Be Live At:**
   `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME`

### **Advanced Customization**
- **Change Theme**: Edit `theme:` in `_config.yml`
- **Add Logo**: Place logo in `/assets/images/` and update `logo:` path
- **Custom Domain**: Add CNAME file with your domain
- **Analytics**: Uncomment and add your Google Analytics ID

---

## 📚 **GitHub Wiki Setup** (Searchable Knowledge Base)

### **Enable Wiki** (2 minutes)
1. **Go to Repository Settings**
   - Navigate to your repository
   - Click "Settings" tab
   - Scroll to "Features" section
   - Check ✅ "Wikis"

2. **Access Your Wiki**
   - Click "Wiki" tab in your repository
   - Click "Create the first page"

### **Recommended Wiki Structure** 

#### **Home Page** (Wiki Landing)
```markdown
# 🌟 Light Stream Ministry Wiki

Welcome to our comprehensive spiritual knowledge base.

## 📖 Quick Navigation
- [[Articles of Association]] - Ministry foundation
- [[Certification of Execution]] - Legal establishment  
- [[Guiding Light]] - Complete spiritual framework
- [[Member Application]] - Join our community
- [[PMA Charter ByLaws]] - Governance framework

## 🤖 AI Integration
- [[AI Stewardship Council]] - Seven archetypal intelligences
- [[50 Sacred Laws]] - Universal spiritual principles

## 👥 Community
- [[Member Resources]] - Private member benefits
- [[Spiritual Practices]] - Daily guidance
- [[FAQ]] - Common questions
```

#### **Individual Wiki Pages**
Create separate wiki pages for each major document:

1. **Articles of Association** - Copy content from your markdown file
2. **Certification of Execution** - Legal establishment details
3. **Guiding Light** - Full spiritual framework
4. **Member Application** - Membership process
5. **PMA Charter ByLaws** - Complete governance
6. **AI Stewardship Council** - Detailed council information
7. **50 Sacred Laws** - Complete laws with explanations

### **Wiki Benefits**
- ✅ **Built-in Search** across all content
- ✅ **Easy Editing** for trusted collaborators
- ✅ **Link Connections** between related topics
- ✅ **Version History** tracks all changes
- ✅ **Collaborative** multiple editors can contribute

---

## 🔗 **Sharing & Access Control**

### **Public Sharing Options**

#### **Repository Links** (Most Direct)
- **Main Hub**: `https://github.com/USERNAME/REPO-NAME`
- **Specific Docs**: `https://github.com/USERNAME/REPO-NAME/tree/main/articled-md/guiding-light`
- **Raw Files**: Add `/raw/main/` for direct markdown viewing

#### **GitHub Pages Links** (Beautiful Website)
- **Home**: `https://USERNAME.github.io/REPO-NAME`
- **Direct Docs**: `https://USERNAME.github.io/REPO-NAME/articled-md/guiding-light/`

#### **Wiki Links** (Searchable)
- **Wiki Home**: `https://github.com/USERNAME/REPO-NAME/wiki`
- **Specific Pages**: `https://github.com/USERNAME/REPO-NAME/wiki/Guiding-Light`

### **Private/Controlled Sharing**

#### **Repository Collaborators**
- **Settings** → **Manage Access** → **Invite a collaborator**
- **Permissions**: Read, Write, or Admin access
- **Perfect for**: Trusted ministry members who can edit

#### **Wiki Access Control**
- **Public Wikis**: Anyone can read, collaborators can edit
- **Private Repos**: Only collaborators can access wiki
- **Perfect for**: Member-only spiritual resources

### **Sharing Best Practices**

#### **For General Public** 🌍
- Share **GitHub Pages** links (most beautiful)
- Use **Repository** links for technical users
- Reference specific sections with anchor links

#### **For Ministry Members** 👥
- Provide **Wiki** access for collaborative editing
- Use **Repository** collaborator access for document editing
- Share **direct markdown** links for easy reading

#### **For Official Distribution** 📋
- Use **GitHub Pages** for professional presentation
- Reference **Repository** for source verification
- Provide **Wiki** for searchable resource access

---

## 🎯 **Quick Action Checklist**

### **Immediate Setup** (15 minutes)
- [ ] Enable GitHub Pages in repository settings
- [ ] Update `_config.yml` with your information
- [ ] Enable Wiki in repository settings
- [ ] Create Wiki home page with navigation
- [ ] Test all three access methods

### **Content Population** (30 minutes)
- [ ] Copy each markdown document to corresponding wiki page
- [ ] Verify all internal links work correctly
- [ ] Test GitHub Pages site renders properly
- [ ] Create member-specific wiki resources
- [ ] Set up any private sections needed

### **Sharing Setup** (10 minutes)
- [ ] Document your three URL patterns
- [ ] Set up collaborator access for trusted members
- [ ] Create sharing templates for different audiences
- [ ] Test access controls and permissions

---

## 🌟 **Advanced Features**

### **GitHub Pages Enhancements**
- **Custom CSS**: Create `/assets/css/style.scss` for custom styling
- **Navigation Menu**: Customize `_includes/header.html`
- **Search**: Add Jekyll search plugin
- **Comments**: Integrate Disqus or similar

### **Wiki Power Features**
- **Templates**: Create page templates for consistency
- **Categories**: Use consistent tagging system
- **Cross-linking**: Link related concepts throughout
- **Media**: Embed images and videos in wiki pages

### **Repository Organization**
- **Issues**: Use for community questions and suggestions
- **Discussions**: Enable for community conversation
- **Projects**: Track documentation improvements
- **Releases**: Version your spiritual teachings

---

## 📞 **Support & Troubleshooting**

### **Common Issues**
- **Pages not loading**: Check repository settings and branch selection
- **Wiki access**: Verify wiki is enabled in repository features
- **Broken links**: Ensure consistent file paths and naming
- **Theme issues**: Try different Jekyll themes in `_config.yml`

### **Getting Help**
- **GitHub Docs**: [pages.github.com](https://pages.github.com)
- **Jekyll Docs**: [jekyllrb.com](https://jekyllrb.com)
- **Community**: GitHub Community Discussions

---

**🌟 Your Light Stream Ministry documentation will now be accessible through three powerful channels, each optimized for different audiences and use cases!**

*Est. April 8, 2016 ∼ and so it is ∼* 