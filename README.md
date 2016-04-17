BookStack Vagrant Box
=====================
A [Vagrant][VAGRANT] box provisioned via [Ansible][ANSIBLE] for [BookStack][BOOKSTACK], a simple and free documentation platform.

Usage
-----
From the command line run:

```sh
vagrant up
```

Then navigate to <http://localhost:8080> and login as `admin@admin.com` with the password `password`.

Shutting Down the Box
---------------------
From the command line run:

```sh
vagrant halt
```

License
-------
The MIT License (Expat). See the [license file](LICENSE) for details.

[ANSIBLE]: https://www.ansible.com/
[BOOKSTACK]: https://www.bookstackapp.com/
[VAGRANT]: https://www.vagrantup.com/
