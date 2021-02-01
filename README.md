# test_link


# Windows
mklink <source> <target>

# Linux
ln -s <source> <target>
> In some cases the source and target are swapped

# Clone with symbolic links must be done by Administrator

## Set config permanently
git config core.symlinks true

## Clone repo with config override
git clone -c core.symlinks=true <Git URL>