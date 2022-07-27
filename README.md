checkout-dir action
======================

GitHub Action to checkout specific directory (instead of the whole repo).

## Usage
```yaml
  - uses: sergeidyga/checkout-dir@v1
    with:
      # Directory to checkout
      # [required]
      dir: ''
      # Repository name
      # [optional] | defaults to ${{ github.repository }}
      repository: ''
      # Ref to checkout
      # [optional] | defaults to ${{ github.ref_name }}
      ref: ''
```