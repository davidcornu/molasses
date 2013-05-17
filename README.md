# Molasses

## Usage

```
$ npm install -g molasses
```

```
$ molasses
Usage: molasses --target [host]

Options:
  --port    Port to listen on                                [default: 3000]
  --delay   Number of milliseconds to delay the request      [default: 5000]
  --target  URL of the resource you would like to slow down  [required]

Missing required arguments: target
```

```
$ molases --target http://127.0.0.1:5984 --port 5985 --delay 30000
Port 5985 is now slow as molasses.
```