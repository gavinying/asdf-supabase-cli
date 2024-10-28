<div align="center">

# asdf-supabase-cli [![Build](https://github.com/gavinying/asdf-supabase-cli/actions/workflows/build.yml/badge.svg)](https://github.com/gavinying/asdf-supabase-cli/actions/workflows/build.yml) [![Lint](https://github.com/gavinying/asdf-supabase-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/gavinying/asdf-supabase-cli/actions/workflows/lint.yml)

[supabase-cli](https://supabase.com/docs/reference/cli) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add supabase-cli
# or
asdf plugin add supabase-cli https://github.com/gavinying/asdf-supabase-cli.git
```

supabase-cli:

```shell
# Show all installable versions
asdf list-all supabase-cli

# Install specific version
asdf install supabase-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global supabase-cli latest

# Now supabase-cli commands are available
supabase --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/gavinying/asdf-supabase-cli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Gavin Ying](https://github.com/gavinying/)
