Clone a Fly machine


## Usage
~~~
flyctl machine clone <id> [flags]
~~~

## Options

~~~
  -a, --app string             Application name
      --attach-volume string   Existing volume to attach to the new machine
  -c, --config string          Path to application configuration file
      --from-snapshot string   Clone attached volumes and restore from snapshot, use 'last' for most recent snapshot. The default is an empty volume
  -h, --help                   help for clone
      --name string            Optional name for the new machine
      --region string          Target region for the new machine
~~~

## Global Options

~~~
  -t, --access-token string   Fly API Access Token
  -j, --json                  json output
      --verbose               verbose output
~~~

## See Also

* [flyctl machine](/docs/flyctl/machine/)	 - Commands that manage machines

