# OCP Playbooks

## Provision
Refer to the [ocp_provision](../roles/ocp_provision.md) role documentation for more information.

```bash
export CLUSTER_NAME=masinst1
export OCP_VERSION="4.8_openshift"

export IBMCLOUD_APIKEY=xxx

ansible-playbook playbooks/ocp/provision-roks.yml
```

```bash
export CLUSTER_NAME=masinst1
export OCP_VERSION=4.6.16

export FYRE_USERNAME=xxx
export FYRE_PASSWORD=xxx
export FYRE_PRODUCT_ID=xxx

ansible-playbook playbooks/ocp/provision-quickburn.yml
```


## Deprovision
Refer to the [ocp_deprovision](../roles/ocp_deprovision.md) role documentation for more information.

**TODO: Update the role doc as it's rubbish atm**

```bash
export CLUSTER_NAME=masinst1
export IBMCLOUD_APIKEY=xxx

ansible-playbook playbooks/ocp/deprovision-roks.yml
```

```bash
export CLUSTER_NAME=masinst1
export FYRE_USERNAME=xxx
export FYRE_PASSWORD=xxx

ansible-playbook playbooks/ocp/deprovision-quickburn.yml
```


## Configure
Refer to the [ocp_setup_mas_deps](../roles/ocp_setup_mas_deps.md) role documentation for more information.

**TODO: Provide example (and update the role doc as it's rubbish atm)**

```bash
export VAR1=xxx

ansible-playbook playbooks/ocp/configure-ocp.yml
```


## Verify
Refer to the [ocp_verify](../roles/ocp_verify.md) role documentation for more information.

**TODO: Provide example (and update the role doc as it's rubbish atm)**

```bash
export VAR1=xxx

ansible-playbook playbooks/ocp/verify-roks.yml
```
