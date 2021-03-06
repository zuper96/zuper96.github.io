---
title:    "MENAMBAHKAN PAGES PADA JEKYLL DOCUMENTATION THEME"
categories: jekyll
permalink: menambahkan-pages-doc.html
tags: [tips jecyll doc theme]
datatable: true
---

Berikut cara menambahakan _pages_ pada _Jekyll documentation theme_ :

1. Pada _file_ `_config.yml` tambah nama _sidebars:_ berikut contohnya:
    
    <pre>
    	
    sidebars:
    - home_sidebar
    - mydoc_sidebar
    - vagrant_sidebar
    - product1_sidebar
    - product2_sidebar
    - php_sidebar
    - other
    	
    </pre>
    	
2. Pada _directory_ `_data\sidebars` buat file baru dengan nama misal `mydoc_sidebar.yml` _file_ ini berisi daftar menu _sidebar_. Penamaan `mydoc_sidebar.yml` harus mengikuti _sidebars:_ yang ada pada _file_ `_config.yml`. Berikut contohnya isi file `mydoc_sidebar.yml`:
    
    <pre>
    
    entries:
    - title: sidebar
      product: Jekyll Doc Theme
      version: 6.0
      folders:
    
      - title:
        output: pdf
        type: frontmatter
        folderitems:
        - title:
          url: /titlepage
          output: pdf
          type: frontmatter
        - title:
          url: /tocpage
          output: pdf
          type: frontmatter
    
      - title: Overview
        output: web, pdf
        folderitems:
    
        - title: Get started
          url: /mydoc-get-started.html
          output: web, pdf
          type: homepage
    
        - title: Introduction
          url: /mydoc_introduction.html
          output: web, pdf
    
        - title: Supported features
          url: /mydoc_supported_features.html
          output: web, pdf
    
        - title: About the theme author
          url: /mydoc_about.html
          output: web, pdf
    
        - title: Support
          url: /mydoc_support.html
          output: web, pdf
    
      - title: Release Notes
        output: web, pdf
        folderitems:
    
        - title: 6.0 Release notes
          url: /mydoc_release_notes_60.html
          output: web, pdf
    
        - title: 5.0 Release notes
          url: /mydoc_release_notes_50.html
          output: web, pdf
    
      - title: Installation
        output: web, pdf
        folderitems:
    
        - title: About Ruby, Gems, Bundler, etc.
          url: /mydoc_about_ruby_gems_etc.html
          output: web, pdf
    
        - title: Install Jekyll on Mac
          url: /mydoc_install_jekyll_on_mac.html
          output: web, pdf
    
        - title: Install Jekyll on Windows
          url: /mydoc_install_jekyll_on_windows.html
          output: web, pdf
    
      - title: Authoring
        output: web, pdf
    
        folderitems:
        - title: Pages
          url: /mydoc_pages.html
          output: web, pdf
    
        - title: Posts
          url: /mydoc_posts.html
          output: web, pdf
    
        - title: Lists
          url: /mydoc_lists.html
          output: web, pdf
    
        - title: Conditional logic
          url: /mydoc_conditional_logic.html
          output: web, pdf
    
        - title: Content reuse
          url: /mydoc_content_reuse.html
          output: web, pdf
    
        - title: Collections
          url: /mydoc_collections.html
          output: web, pdf
    
        - title: WebStorm editor tips
          url: /mydoc_webstorm_text_editor.html
          output: web, pdf
    
        - title: Atom editor tips
          url: /mydoc_atom_text_editor.html
          output: web, pdf
    
      - title: Navigation
        output: web, pdf
    
        folderitems:
        - title: Sidebar navigation
          url: /mydoc_sidebar_navigation.html
          output: web, pdf
    
        - title: YAML tutorial in the context of Jekyll
          url: /mydoc_yaml_tutorial.html
          output: web, pdf
    
        - title: Tags
          url: /mydoc_tags.html
          output: web, pdf
    
        - title: Series
          url: /mydoc_series.html
          output: web, pdf
    
      - title: Formatting
        output: web, pdf
    
        folderitems:
        - title: Tooltips
          url: /mydoc_adding_tooltips.html
          output: web, pdf
    
        - title: Alerts
          url: /mydoc_alerts.html
          output: web, pdf
    
        - title: Icons
          url: /mydoc_icons.html
          output: web, pdf
    
        - title: Images
          url: /mydoc_images.html
          output: web, pdf
    
        - title: Code samples
          url: /mydoc_code_samples.html
          output: web, pdf
    
        - title: Labels
          url: /mydoc_labels.html
          output: web, pdf
    
        - title: Links
          url: /mydoc_hyperlinks.html
          output: web, pdf
    
        - title: Navtabs
          url: /mydoc_navtabs.html
          output: web, pdf
    
        - title: Tables
          url: /mydoc_tables.html
          output: web, pdf
    
        - title: Syntax highlighting
          url: /mydoc_syntax_highlighting.html
          output: web, pdf
    
        - title: Workflow maps
          url: /mydoc_workflow_maps.html
          output: web, pdf
    
      - title: Handling reviews
        output: web, pdf
    
        folderitems:
        - title: Commenting on files
          url: /mydoc_commenting_on_files.html
          output: web, pdf
    
        - title: Git collaboration
          url: /mydoc_git_collaboration
          output: web, pdf
    
      - title: Publishing
        output: web, pdf
    
        folderitems:
        - title: Build arguments
          url: /mydoc_build_arguments.html
          output: web, pdf
    
        - title: Themes
          url: /mydoc_themes.html
          output: web, pdf
    
        - title: Generating PDFs
          url: /mydoc_generating_pdfs.html
          output: web, pdf
    
        - title: Help APIs and UI tooltips
          url: /mydoc_help_api.html
          output: web, pdf
    
        - title: Search configuration
          url: /mydoc_search_configuration.html
          output: web, pdf
    
        - title: iTerm profiles
          url: /mydoc_iterm_profiles.html
          output: web, pdf
    
        - title: Pushing builds to server
          url: /mydoc_push_build_to_server.html
          output: web, pdf
    
        - title: Getting around the password prompts in SCP
          url: /mydoc_no_password_prompts_scp.html
          output: web, pdf
    
        - title: Publishing on Github Pages
          url: /mydoc_publishing_github_pages.html
          output: web, pdf
    
      - title: Special layouts
        output: web, pdf
    
        folderitems:
        - title: Knowledge-base layout
          url: /mydoc_kb_layout.html
          output: web, pdf
    
        - title: Glossary layout
          url: /mydoc_glossary.html
          output: web, pdf
    
        - title: FAQ layout
          url: /mydoc_faq_layout.html
          output: web, pdf
    
        - title: Scroll layout
          url: /mydoc_scroll.html
          output: web, pdf
    
        - title: Shuffle layout
          url: /mydoc_shuffle.html
          output: web, pdf
    
      - title: Troubleshooting
        output: web, pdf
    
        folderitems:
    
        - title: Troubleshooting
          url: /mydoc_troubleshooting.html
          output: web, pdf
    
      - title: Tag archives
        output: web
        folderitems:
    
        - title: Tag archives overview
          url: /mydoc_tag_archives_overview.html
          output: web
    
          subfolders:
          - title: Tag archive pages
            output: web
            subfolderitems:
    
            - title: Formatting pages
              url: /tag_formatting.html
              output: web
    
            - title: Navigation pages
              url: /tag_navigation.html
              output: web
    
            - title: Content types pages
              url: /tag_content_types.html
              output: web
    
            - title: Publishing pages
              url: /tag_publishing.html
              output: web
    
            - title: Special layout pages
              url: /tag_special_layouts.html
              output: web
    
            - title: Collaboration pages
              url: /tag_collaboration.html
              output: web
    
            - title: Troubleshooting pages
              url: /tag_troubleshooting.html
              output: web
    		  
    </pre>
    	
3. Pada _directory_ `_includes\custom` _file_ `sidebarconfigs.html` tambahkan kontrol _sidebar_. Berikut contohnya :
    
  _file_ yang ditambahkan :
  
  
    {% raw %}
    <pre>
    	
        {% elsif page.sidebar == "mydoc_sidebar" %}
        {% assign sidebar = site.data.sidebars.mydoc_sidebar.entries %}
    
    </pre>
    {% endraw %}
  	
  Menjadi :
  
      
    {% raw %}
    <pre>
    
        {% if page.sidebar == "home_sidebar" %}
        {% assign sidebar = site.data.sidebars.home_sidebar.entries %}
        
        {% elsif page.sidebar == "product1_sidebar" %}
        {% assign sidebar = site.data.sidebars.product1_sidebar.entries %}
        
        {% elsif page.sidebar == "product2_sidebar" %}
        {% assign sidebar = site.data.sidebars.product2_sidebar.entries %}
        
        {% elsif page.sidebar == "mydoc_sidebar" %}
        {% assign sidebar = site.data.sidebars.mydoc_sidebar.entries %}
        
        {% elsif page.sidebar == "vagrant_sidebar" %}
        {% assign sidebar = site.data.sidebars.vagrant_sidebar.entries %}
        
        {% elsif page.sidebar == "git_sidebar" %}
        {% assign sidebar = site.data.sidebars.git_sidebar.entries %}
        
        {% elsif page.sidebar == "composer_sidebar" %}
        {% assign sidebar = site.data.sidebars.composer_sidebar.entries %}
        
        {% elsif page.sidebar == "php_sidebar" %}
        {% assign sidebar = site.data.sidebars.php_sidebar.entries %}
        
        {% else %}
        {% assign sidebar = site.data.sidebars.home_sidebar.entries %}
        {% endif %}
    
    </pre>
    {% endraw %}
    
4. Pada _directory_ `pages` buat _directory_ baru dengan nama `mydoc` semua dokumentasi disimpan didalam _dirctory_ ini dengan format _file_ `mydoc_nama_file_anda.md`. Buka _file_ yang sudah dibuat dan tambahkan _frontmatter_ sebagai berikut :
    
    {% raw %}
    <pre>
    	
    ---
    title: Code samples
    tags: [formatting]
    keywords: dcode samples syntax highlighting
    last_updated: July 3, 2016
    datatable: true
    summary: "You can use fenced code blocks with the language specified after the first set of backtick fences."
    sidebar: mydoc_sidebar
    permalink: mydoc_code_samples.html
    folder: mydoc
    ---
    
    KONTEN ANDA DISINI
    
    {% include links.html %}
    
    </pre>
    {% endraw %}
    
5. Agar mudah di akses tambahkan di `_topnav.yml` yang berada di _directory_ `_data`. Berikut contohnya :
    
  _file_ yang ditambahkan :
      
    <pre>
    
    - title: Jekyll Documentation Theme
      url: /mydoc_introduction.html
	    
    </pre>
  
  Menjadi :
      
    <pre>
    
    - title: Topnav
      items:
        - title: Archive
          url: /blog_archive.html
    #Topnav dropdowns
    topnav_dropdowns:
    - title: Topnav dropdowns
      folders:
        - title: Doc
          folderitems:
            - title: vagrant
              url: /vagrant-vagrantfile.html
            - title: Jekyll Documentation Theme
              url: /mydoc_introduction.html
            - title: Product 1
              url: /p1_landing_page.html
            - title: Product 2
              url: /p2_landing_page.html
    </pre>
	
{% include warning.html content=" Hindari penggunaan _TAB_ pada saat pengetikan." %}
Selesai.

{% include links.html %}
