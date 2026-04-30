# LayerLab
LayerLAB is a web-based intelligence system designed to bridge the gap between skincare chemistry and data analytics. Developed as a technical showcase of information systems and retail technology, the project focuses on analyzing skincare ingredient compatibility to help users build safer, more effective routines.C

# --- LayerLAB Capstone GitIgnore ---

# 1. PHP/Web Security (CRITICAL)
# This prevents your AWS/MySQL passwords from leaking to GitHub
db_config.php
config.php
.env
*.publishsettings

# 2. JavaScript Dependencies
# We run 'npm install' on the EC2 to generate these
node_modules/
npm-debug.log*

# 3. VS Code Specifics
# Keeps your personal editor settings off the repo
.vscode/*
!.vscode/settings.json
.history/

# 4. Database Files
# Don't upload raw database dumps to the repo
*.sql
*.mdf
*.ldf

# 5. System Junk
.DS_Store
Thumbs.db
[Ll]og/
[Ll]ogs/
