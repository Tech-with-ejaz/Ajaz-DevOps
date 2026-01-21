# DevOps Journal
 
## Git (Learning Git Commands)
# 1. Check current status
git status

# 2. Stage specific files (recommended)
git add code_file.py README.md DevOps_Journal.md

# OR stage everything (only if intentional)
git add .

# 3. Commit with a meaningful message
git commit -m "Add initial CI-ready Python script and documentation"

# 4. Push to remote repository
git push origin main

##  Git Hub Repo Structure should look like:

devops-ci-practice/
├── code_file.py
├── README.md
├── DevOps_Journal.md
└── .github/
    └── workflows/           (Git Hub See this Drive only.
        └── ci.yml   (later, when you add CI)   
		(its Active pipe line only)
	└── workflows-archive/     (Git Hub ignore this drive)
               ├── ci-basic.yml
               ├── ci-python-lint.yml
               └── ci-test-only.yml	
        Remember only one  pipeline (Ci.yaml or CI ) for one project.



## CI (GitHub Actions)
- YAML defines pipeline steps
- GitHub runner executes Linux commands
- Bash is the real worker

## Notes
- Learning slowly but clearly
- Will refine CI before moving ahead

