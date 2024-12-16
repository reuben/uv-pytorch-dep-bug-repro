```bash
$ git clone https://github.com/reuben/uv-pytorch-dep-bug-repro.git
$ cd uv-pytorch-dep-bug-repro/projects/app
$ uv sync --extra torch-v1
error: Requirements contain conflicting indexes for package `torch` in split `platform_system != 'Darwin'`:
- https://download.pytorch.org/whl/cu113/
- https://download.pytorch.org/whl/cu121/
```
