# Sunaoka Tap

## How do I install these formulae?

```bash
brew install sidneys/homebrew/openssl@1.0

mkdir $(brew --repository)/Library/Taps/sunaoka
git clone https://github.com/sunaoka/homebrew-tap.git $(brew --repository)/Library/Taps/sunaoka/homebrew-tap

brew install --build-from-source sunaoka/tap/php@5.5
```

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
