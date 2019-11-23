# git-superblame

## Usage
```
./git-superblame path/to/repo/.git path/to/file commit [path/to/tracespec]
```

## tracespec

Each line in `tracespec` file follows this format:
```
commit:path/to/filename:commit_orig:path/to/filename_orig
```
This line tells that the script regards `path/to/filename` in `commit` was copied/renamed from `path/to/filename_orig` in `commit_orig`.

## See Also

- blameFollow (https://github.com/dmgerman/blameFollow)
