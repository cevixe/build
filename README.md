# Cevixe Build GitHub Actions

Cevixe Build GitHub Actions allows you to build cevixe projects

## Example usage

```yaml
on: [push]

jobs:
  aws_cdk:
    runs-on: ubuntu-latest
    steps:
      - name: Build
        uses: cevixe/build@v1
```

## License

[MIT](LICENSE)

## Authors

[Ronnie Ayala](https://github.com/ronnieacs)