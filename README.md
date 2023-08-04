# kubebuilder-Tasks
kubebuilder-Tasks

# Install golang
```shell
wget https://go.dev/dl/go1.20.6.linux-amd64.tar.gz && rm -rf /usr/local/go && tar -C /usr/local -xzf go1.20.6.linux-amd64.tar.gz

```


# Install kubebuilder

```shell
# download kubebuilder and install locally.
curl -L -o kubebuilder "https://go.kubebuilder.io/dl/latest/$(go env GOOS)/$(go env GOARCH)"
chmod +x kubebuilder && mv kubebuilder /usr/local/bin/

```

