# currproj

Quick project opener with tmux + nvim.

## Usage

```bash
currproj                    # open all files in current project
currproj py js              # open only .py and .js files
currproj -n /path/to/proj   # set new project directory
```

## Setup

Put the script somewhere in your PATH. First run creates `~/.currproj_dir` with your home directory as default.

Opens files in nvim tabs within a tmux session called "currproj". Reattaches to existing session if found.
