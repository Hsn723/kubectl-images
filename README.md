# kubectl-images
List unique images used by Pods for the given criteria.

## Installation
Place this anywhere in your PATH and ensure it is executable by `chmod`-ing it as necessary.

## Usage
```sh
Usage: kubectl images [options]

Options:
        -A, --all-namespaces: list accross all namespaces. Overrides the namespace specified with --namespace
        -l, --selector: label selector
        -n, --namespace: list for the specified namespace
        -h, --help: show this help
```