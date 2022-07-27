checkout-dirs action
======================

Minimalistic GitHub Action to checkout specific directories (instead of the whole repo).

## Usage
```yaml
  - uses: sergeidyga/checkout-dirs@v1
    with:
      # Space-separated directories to checkout
      # [required]
      dirs: 'dir1 dir2'
      # Repository name
      # [optional] defaults to ${{ github.repository }}
      repository: ''
      # Ref to checkout
      # [optional] defaults to ${{ github.ref_name }}
      ref: ''
```