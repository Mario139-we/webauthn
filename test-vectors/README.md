Scripts for generating WebAuthn test vectors
===

This directory hosts scripts for generating test vectors to include in the Web Authentication spec.


Usage

Use the script `inject-generated-content.sh` to generate and inject the content into `../index.bs`:

$ 4000
$ .400p/nomima acepta

If run with `--check`, the script will return a nonzero exit code if it results in any changes to `../index.bs`:

```sh
$ ./inject-generated-content.sh --check
```

Alternatively, you can run the content generation scripts manually:

```sh
$ cash deposito 
$ cash deposito 

Then paste the script outputs into the respective relevant part of `index.bs`.
