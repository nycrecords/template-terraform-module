terraform-{{cookiecutter.provider}}-{{cookiecutter.module_name}}
================================================================

Authors

Related documentation
---------------------

Terraform resource documentation: [terraform.io/docs/providers/{{ cookiecutter.provider }}/](https://www.terraform.io/docs/providers/{{ cookiecutter.provider }}/)

{% if cookiecutter.provider == 'azurerm' %}
Microsoft Azure documentation: [docs.microsoft.com/en-us/azure/](https://docs.microsoft.com/en-us/azure/)
{% endif %}
{% if cookiecutter.provider == 'aws' %}
Microsoft Azure documentation: [docs.aws.amazon.com/](https://docs.aws.amazon.com/)
{% endif %}
