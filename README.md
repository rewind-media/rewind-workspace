# rewind-workspace
This is a meta-package designed to setup a development workspace. Component packages of Rewind can be found as [git submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules) in the [packages/](packages) directory.

## Setup
```bash
git clone https://github.com/rewind-media/rewind-workspace.git
cd rewind-workspace
git submodule init
git submodule update
npm install
```

## Building
```bash
npm run build
```

## Running
```bash
npm run start
```