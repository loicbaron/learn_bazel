# learn_bazel

## Install Bazel
```
brew install bazel@8
brew install ibazel
```

## Code Example
https://github.com/bazelbuild/examples/tree/main/frontend


## Monorepo structure
```
frontend/
│── react/
│   ├── src/
│   ├── public/
│   ├── BUILD.bazel
│   ├── package.json
│── WORKSPACE.bazel
│── MODULE.bazel               # Bzlmod module definition
│── .bazelrc
│── package.json               # Root package.json for dependency management
│── BUILD.bazel
```


## Build
```
cd frontend
bazel build //...
```

## Run React App
```
cd frontend
bazel run //react:start
```
