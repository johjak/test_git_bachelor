# TEST-REPOSITORY – ELTS3900

Stian, Sindre, John Rune, Einar

## Git - documentation

### General guidelines
Hei
#### VHDL-formatting

> See template

#### Commits

- **Always** pull *before* making any changes to files inside the repository.
- All commit-messages in present tense.
- A **logfile**, like the example `commit.txt`, is to be updated regulary, to keep track of commits.
- Every change documented in commit-messsage, sorted by file edited, as the below example.


#### logfile (might be able to be automated?)

Command for updating the logfile (here called `commits.txt`):

- `git log --graph > commits.txt`

> examplefile1.vhd:
>
> - Edit X-statement in EXAMPLE_PROC
>
> examplefile2.vhd:
>
> - Minor correction after compilation.

#### VsCode

Visual Studio Code is mainly to be used, both for editing source-code and version control.
Extensions used:

- Source control
- (Gitlens)
- VHDL by VHDLWhiz
- ...
