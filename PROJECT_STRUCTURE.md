# Awesome Machine Learning Project Structure

```
awesome-machine-learning/
├── README.md                           # Main content file
├── CONTRIBUTING.md                     # Contribution guidelines
├── CHANGELOG.md                        # Update log
├── LICENSE                            # MIT license
├── .github/                           # GitHub configuration files
│   ├── ISSUE_TEMPLATE/               # Issue templates
│   │   ├── new-resource.yml          # New resource template
│   │   └── bug-report.yml            # Bug report template
│   └── PULL_REQUEST_TEMPLATE.md      # PR template
├── docs/                             # Documentation directory (planned)
│   ├── guidelines/                   # Detailed guidelines
│   ├── examples/                     # Examples and templates
│   └── assets/                       # Images and resources
└── scripts/                          # Automation scripts
    ├── README.md                     # Scripts documentation
    ├── arxiv_date_extractor.sh       # Extract arXiv paper dates
    ├── update_and_sort_papers.sh     # Update and sort papers by date
    ├── install_hook.sh               # Install git hooks for automation
    └── test_hook.sh                  # Test git hooks locally
```

## File Descriptions

### Core Files
- **README.md**: Main project content with categorized machine learning resources
- **CONTRIBUTING.md**: Detailed contribution guide to help new contributors understand participation
- **CHANGELOG.md**: Records project version updates and important changes
- **LICENSE**: MIT open source license

### GitHub Configuration
- **Issue Templates**: Standardized problem reporting and resource suggestion formats
- **PR Template**: Unified Pull Request submission format

## Content Organization Principles

### Classification Logic
1. **By Usage**: Papers, tools, datasets, courses, etc.
2. **By Domain**: NLP, CV, reinforcement learning, and other technical directions
3. **By Time**: Priority display of latest and most relevant content
4. **By Authority**: Preference for top conferences and renowned institutions

### Quality Control
- All resources are manually reviewed
- Regular checking of link validity
- Priority given to authoritative and high-quality sources
- Maintaining content timeliness and relevance

## Maintenance Plan

### Regular Tasks
- **Weekly**: Check new submitted PRs and Issues
- **Monthly**: Update latest papers and tools
- **Quarterly**: Organize research trends, clean outdated content
- **Annually**: Major structural adjustments and annual summaries

### Automation Tools (Available)
- **arXiv Date Extractor**: Automatically extracts publication dates from arXiv papers
- **Paper Sorter**: Sorts papers by publication date within each section
- **Git Hooks**: Automatically processes papers and updates dates on commit/push
- **Backup System**: Creates backup files before making changes

### Automation Tools (Planned Development)
- Link validity checker
- Content format validator
- Duplicate content detector
- Update reminder system
