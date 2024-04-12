
```
provider "azurerm" {
        features {}
}

module "resource_group" {
        source = "git@github.com:sreelakshmilingamgunta/module-Resource-Group.git"
        rg_name = "sreelakshmi-reg"
        loc = "west us"
}
```
