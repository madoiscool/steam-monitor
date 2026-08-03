# steam-monitor

Automatically published Steam client data. Do not edit by hand.

The data lives on separate orphan branches — this branch (`main`) only carries
the workflow that keeps them up to date.

| Branch | Contents |
| --- | --- |
| [`pattern`](../../tree/pattern) | Steam client rule patterns |
| [`ipc`](../../tree/ipc) | Steam client IPC interfaces |
| [`protobuf`](../../tree/protobuf) | Steam client protobuf definitions |

Each branch has its own README listing the client build versions it covers.

## Usage

```sh
git clone --branch protobuf --single-branch https://github.com/madoiscool/steam-monitor.git
```

Branches are updated within seconds of a new client build being published, and
are only ever fast-forwarded.
