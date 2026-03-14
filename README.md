# S. Taylor Labs

Claude Code plugin marketplace.

## Install

```bash
# Add the marketplace
/plugin marketplace add SteeZyT33/s-taylor-labs

# Install a plugin
/plugin install perf-lab@s-taylor-labs
```

## Plugins

| Plugin | Version | Description |
|--------|---------|-------------|
| [perf-lab](https://github.com/SteeZyT33/perf-lab-plugin) | 3.0.0 | Autonomous multi-agent performance optimization for Claude Code |

### perf-lab

Turns any "optimize metric X" problem into coordinated research teams with experiment tracking, breakthrough detection, fleet orchestration, and knowledge curation.

Three adoptable layers:
1. **Experiment Discipline** - single agent, tracked iterations
2. **Autonomous Iteration** - unattended sweeps with plateau breaking
3. **Fleet Orchestration** - multi-agent teams with Jarvis5A orchestrator

Skills: `/perf-lab:experiment`, `/perf-lab:jarvis`, `/perf-lab:sweep`, `/perf-lab:status`, `/perf-lab:research`, `/perf-lab:plateau`, `/perf-lab:replay`, `/perf-lab:analyze`, `/perf-lab:swarm`, `/perf-lab:init`

After installing, run the setup script in your target project:

```bash
# Set up shared directories, config, and scripts
/path/to/perf-lab-plugin/install.sh /path/to/your/project
```
