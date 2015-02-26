# OPAM repository

*Usage:*

Add this repository to your opam configuration.

```
# OPAM_VER="1.1" opam repo add a-repo-name "https://raw.github.com/cchantep/opam-repository/master/$OPAM_VER"
```

> Replace `OPAM_VER` by the name of a sub-directory within this repository, corresponding to OPAM version.

## Update

```
# OPAM_VER="1.1" cd "$OPAM_VER" && opam-admin make
```
