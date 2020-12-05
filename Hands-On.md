# Hands on

> Connect-AzAccount

> New-AzResourceGroup -Name azpkaz303rg -Location EastUs

> New-AzVM -ResourceGroupName "azpkaz303rg" -Name "azpkaz303vm01" -Location "EastUS" -VirtualNetworkName "azpkaz303vnet" -SubnetName "azpkaz303snet" -SecurityGroupName "azpkaz303nsg" -PublicIpAddressName "azpkaz303ipaddr" -OpenPorts 80,443,22


