# Atom Terraform Snippets

An Atom snippet library for terraform. [language-terraform](https://atom.io/packages/language-terraform) must be installed.

## Install

Go to Packages > Settings View > Open once in settings go to the Install tab and search for terraform-snippets

OR 

```sh
apm install terraform snippets
```

## Development

```sh
$ cd ~/.atom/packages
$ git clone https://github.com/starlightromero/terraform-snippets.git
$ cd terraform-snippets
$ apm install
$ apm link
```

## Snippets

the → means the TAB key

Trigger                       | Content
:---------------------------- | :----------------------------
`aws_eip`                     | aws elastic ip
`aws_instance`                | aws ec2 instance
`aws_internet_gateway`        | aws internet gateway
`aws_network_interface`       | aws network interface
`aws_route_table_association` | aws route table association
`aws_route_table`             | aws route table
`aws_security_group`          | aws security group
`aws_subnet→`                 | aws subnet
`aws_vpc`                     | aws virutal private cloud
`aws`                         | aws provider
`digitalocean`                | digitalocean provider
`droplet`                     | digitalocean droplet resource
`egress`                      | egress
`for_each`                    | for each
`forwarding_rule`             | forwarding_rule
`healthcheck`                 | healthcheck
`ingress`                     | ingress
`network_interface`           | network interface
`output`                      | output
`provider`                    | provider
`resource`                    | resource
`route`                       | route
`sensitive-list`              | sensitive list variable
`sensitive-map`               | sensitive map variable
`sensitive-number`            | sensitive number variable
`sensitive-string`            | sensitive string variable
`sensitive`                   | sensitive variable
`variable-list`               | list variable
`variable-map`                | map variable
`variable-number`             | number variable
`variable-string`             | string variable
`variable`                    | variable

## Contributing

1. Fork it!
2. Create your feature branch: git checkout -b my-new-feature
3. Commit your changes: git commit -m 'Add some feature'
4. Push to the branch: git push origin my-new-feature
5. Submit a pull request

## License

MIT License © Starlight Romero
