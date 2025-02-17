# learn_bazel

## Code Example
https://github.com/bazelbuild/examples/tree/main/frontend

## Install Bazel
```
brew install bazel@8
```

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
