# AWS-Examples-SAA-C03
Esta documentacion es del tutorial de youtuve [AWS Solutions Architect Associate from freeCodeCamp.org](https://youtu.be/c3Cn4xYfxJY?feature=shared)
## Configuracion del gitpod

Lo primero que hacemos es ejecutar `gitpop init`, lo cual genera un **yml** file y lo modificamos, quedando asi:

```yml
tasks:
  - name: aws-cli
    # Instala las aws cli
    before: |
      cd /workspace
      curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
      unzip awscliv2.zip
      sudo ./aws/install
      cd $THEIA_WORKSPACE_ROOT
vscode:
  extensions:
    - vscodevim.vimd.io/docs/introduction/getting-started/quickstart

``` 