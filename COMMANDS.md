# Commands

List of handy ansible commands to know about.

## Run module on all hosts
```
$ ansible all -m ping
```

## Run module on a certain host
```
$ ansible pi -m ping -i inventory
```

## Run command on a certain host
```
$ ansible pi -i inventory -a "ls -al"
```

## Run in dry mode
```
$ ansible pi -C -i inventory -a "ls -al"
```
