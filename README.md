# Kube-token

Generate and extract a Kubernetes service account token.

## Configuration
|Var|Default value|Description|
|---|-------------|-----------|
|kube_token_namespace|undefined|Namespace to create token in|
|kube_token_name|undefined|Name of the service account to create|
|kube_token_path|undefined|Path to token file to create|
|kube_token_ca_path|undefined|Path to ca certificate file to create (PEM)|
|kube_token_kubeconfig|`~/.kube/config`|Path to kubeconfig to use on controller|
|kube_token_state|`present`|Whether to create or delete the token and service account|
|kube_token_owner|`root`|Owner of files on the target machine|
|kube_token_group|`root`|Group of files on the target machine|
|kube_token_mode|`0640`|Mode of files of the target machine|
