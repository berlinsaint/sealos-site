# Environment settings

sealos only support linux now, you need a linux server to test it.

Some tools can be very handy to help you start a virtual machine such as [multipass](https://multipass.run/)

# Build the project

```shell
git clone https://github.com/labrirng/sealos
cd sealos
make build
```

You can scp the bin file to your linux host.

If you use multipass, you can mount the bin dir to the vm:

```shell
multipass mount /your-bin-dir <name>[:<path>]
```

Then test it locally.