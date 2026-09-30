# rules_python #4198 repro

```console
$ bazel build //:hello_tar
tar: Error reading archive bazel-out/k8-fastbuild/bin/hello_tar_mtree.txt: mtree specification has different type for hello.runfiles/rules_python++python+python_3_12_x86_64-unknown-linux-gnu/lib/python3.12/__phello__/__pycache__
```
