# CD12352 - Infrastructure as Code Project Solution

## Abdulaziz Alsafadi

## Spin up instructions

### To create the network infrastructure, use the following command:

```bash
./run.sh deploy \
us-east-1 \
UdagramNetwork \
./network-infrastructure/network.yml \
./udagram-infrastructure/network-parameters.json
```

### To create the udagram infrastructure, use the following command:

```bash
./run.sh deploy \
us-east-1 \
UdagramResources \
./udagram-infrastructure/udagram.yml \
./udagram-infrastructure/udagram-parameters.json
```

### To delete the network infrastructure, use the following command:

```bash
./run.sh delete \
us-east-1 \
UdagramNetwork \
```

### To delete the udagram infrastructure, use the following command:

```bash
./run.sh delete \
us-east-1 \
UdagramResources
```
