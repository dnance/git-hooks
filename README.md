# Geronimo git hooks

---

# Usage and Gotchas

## Usage

**Copy or create symbolic links 
 Copy from appropriate directory to the .git/hooks directory for the client or the [repo]/hooks directory for the server-side scripts.
 Create a symlink in the .git/hooks directory to the appropriate script in git-hooks
  
** Use --no-verify to skip the check when running the corresponding git command

## Gotchas 

Make sure the script is marked as executable '(chmod +x)
