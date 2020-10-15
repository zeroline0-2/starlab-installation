# How to use the script
## Run the script
    ./createvm.sh

## 1. Enter the flavor id
    What is the flavor id?
    <flavor-id>
Discover the flavor id what you want with the **openstack flavor list** command.

## 2. Enter the image id
    What is the image id?
    <image-id>
Discover the image id what you want with the **openstack image list** command.

## 3. Enter the keypair name
    What is the keypair-name?
    <keypair-name>
Discover the keypair name what you want with the **openstack keypair list** command.

## 4. Enter the security group id
    What is the security-group?
    <security-group-id>
Discover the security group id what you want with the **openstack security group list** command.

## 5. Enter the network id
    What is the network id?
    <network-id>
Discover the network id what you want with the **openstack network list** command.

## 6. Enter the name of the instance
    What is the name of instance?
    <instance-name>

## 7. Enter the number of instances
    How many instances?
    <amount>
    
## Example
    What is the flavor id?
    4
    What is the image id?
    0533430c-2518-4689-a35d-a4233348e942
    what is the keypair-name?
    mykey
    what is the security-group?
    a6344356-5a2d-4060-9e09-390370957802
    What is the network id?
    e294144b-abdd-48b9-a305-3019b7cbfe35
    What is the name of instance?
    test22
    How many instances?
    1
    +-------------------------------------+-------------------------------------------------------------+
    | Field                               | Value                                                       |
    +-------------------------------------+-------------------------------------------------------------+
    | OS-DCF:diskConfig                   | MANUAL                                                      |
    | OS-EXT-AZ:availability_zone         |                                                             |
    | OS-EXT-SRV-ATTR:host                | None                                                        |
    | OS-EXT-SRV-ATTR:hypervisor_hostname | None                                                        |
    | OS-EXT-SRV-ATTR:instance_name       |                                                             |
    | OS-EXT-STS:power_state              | NOSTATE                                                     |
    | OS-EXT-STS:task_state               | scheduling                                                  |
    | OS-EXT-STS:vm_state                 | building                                                    |
    | OS-SRV-USG:launched_at              | None                                                        |
    | OS-SRV-USG:terminated_at            | None                                                        |
    | accessIPv4                          |                                                             |
    | accessIPv6                          |                                                             |
    | addresses                           |                                                             |
    | adminPass                           | DahN5unjJs8a                                                |
    | config_drive                        |                                                             |
    | created                             | 2020-10-15T05:54:43Z                                        |
    | flavor                              | m1.large (4)                                                |
    | hostId                              |                                                             |
    | id                                  | 11562bac-635e-4cbc-a6f4-a44747f4ff0e                        |
    | image                               | ubuntu_snapshot_test (0533430c-2518-4689-a35d-a4233348e942) |
    | key_name                            | mykey                                                       |
    | name                                | test220                                                     |
    | progress                            | 0                                                           |
    | project_id                          | 4d84cb93930c46ae9f230746140c3443                            |
    | properties                          |                                                             |
    | security_groups                     | name='a6344356-5a2d-4060-9e09-390370957802'                 |
    | status                              | BUILD                                                       |
    | updated                             | 2020-10-15T05:54:43Z                                        |
    | user_id                             | cdc9b9a77f4c4ce2a8c5654edf9ab21c                            |
    | volumes_attached                    |                                                             |
    +-------------------------------------+-------------------------------------------------------------+
