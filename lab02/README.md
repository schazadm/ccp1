# Lab OSTK

## Task 1

> Creating an Instance with the CLI

```sh
openstack server create --flavor m1.small --image 202110_Ubuntu-Focal-20.04 --key-name Desk_Monster --security-group  ccp1-lab --network internal lab_ostk_subtask
```

> Elasticity, Scale an Instance Vertically

```sh
openstack server resize --wait --flavor m1.medium lab_ostk_subtask
```
