# packer-aws-ubuntujammy-terraform-agent
Packer image with TFC agent preinstalled

## Intro
This manual is dedicated to create AWS image with Ubuntu Jammy and TFC agent preinstalled

- Change folder to packer-aws-ubuntujammy-terraform-agent

```bash
cd packer-aws-ubuntujammy-terraform-agent
```

## Build
- In the same folder you were before run 

```bash
packer init template.pkr.hcl
packer build template.pkr.hcl
```
