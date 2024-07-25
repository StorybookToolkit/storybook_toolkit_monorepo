# Storybook Toolkit Monorepo

Monorepo for development of storybook_toolkit package.

## Features

- Flutter package maintained by melos
- In package directory are submodules of other packages used in storybook_toolkit

## Installation

Clone project with all submodules:

```sh
git clone --recurse-submodules <repo_url>
```

Update all submodules:

```sh
git submodule update --remote --merge
```

## Usage

Update dependencies:

```sh
melos bs
```

Publish packages:

```sh
melos publish --no-dry-run
```


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## Author

👤 **Martin Jablečník**

* Website: [martin-jablecnik.cz](https://www.martin-jablecnik.cz)
* Github: [@mjablecnik](https://github.com/mjablecnik)
* Blog: [dev.to/mjablecnik](https://dev.to/mjablecnik)


## Show your support

Give a ⭐️ if this project helped you!

<a href="https://www.patreon.com/mjablecnik">
  <img src="https://c5.patreon.com/external/logo/become_a_patron_button@2x.png" width="160">
</a>


## 📝 License

Copyright © 2024 [Martin Jablečník](https://github.com/mjablecnik).<br />
This project is licensed under [MIT License](https://github.com/mjablecnik/storybook_toolkit_monorepo/blob/master/LICENSE).
