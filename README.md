# Core Components
- Workflows: Define Events + Jobs
- Jobs: Define Runner + Steps
- Steps: Do the actual work

# Events/Triggers
- Broad variety of events (repo-related & other)
- Workflows have >= 1 event

# Defining Workflows
- `github/workflows/<file>.yml`
- GitHub Actions syntax must be followed

# Runners
- Servers (machines) that execute the jobs
- Pre-defined runners (with different OS) exist
- Can also create custom runners

# Workflow Execution
- Workflows are executed when their events are triggered
- GitHub provides detailed insights into job execution (+logs)

# Actions
- Can run shell commands
- But can also use pre-defined Actions (official, community, or custom)