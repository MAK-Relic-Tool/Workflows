# Templates
## These are not reusable workflows
These workflows seem to fail by design or misconfiguration when running in a reusable workflow

To circumvent that, I created these files as templates

Replace any necessary literal variables (currently I mark them inside `${{}}` 

E.G. `${{ 'some literal value' }})`

## Dependabot
Dependabot isn't actually a workflow, but having a template for it is still nice