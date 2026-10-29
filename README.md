# Kiz Radar claims

The owner's decisions for [Kiz Radar](https://github.com/clombion/kiz-radar): that two artists are one, where an artist
is from, which artist a festival's line-up means, and what a ticket site waits for. Each claim is one JSON file, named
by the digest of its text (`pipeline/claims.py` in kiz-radar), so writing a claim again changes nothing.

kiz-radar holds this repository as a git submodule pinned at a commit: a claim reaches the site at kiz-radar's next run
that moves the pin. A claim here comes first over the pipeline's own answers; a file that is no claim stops the run.
