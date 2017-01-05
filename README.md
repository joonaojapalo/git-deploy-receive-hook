# Quick start

Replace `my-project` with a project name.

1. Create bare repo into server:
```
mkdir my-project
cd my-project
git init --bare --shared
```

2. Copy `hook` file into bare repo hooks/
```
cp hook my-project/hooks/post-receive
```
