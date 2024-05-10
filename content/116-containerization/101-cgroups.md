# Cgroups

Cgroups, abreviatura de grupos de control, es una característica del kernel de Linux que permite organizar los procesos en grupos jerárquicos. Su papel crucial en la contenedorización es su capacidad para limitar, contabilizar y aislar el uso de recursos (CPU, memoria, E/S de disco, etc.) de estos grupos de procesos.

En el contexto de la contenedorización, donde se ejecutan entornos ligeros y aislados en la misma máquina host, los cgroups se vuelven fundamentales para una gestión eficiente de los recursos. Al utilizar cgroups, se puede garantizar que cada contenedor no monopolice los recursos del host, lo que mejora la estabilidad y el rendimiento general del sistema.

A continuación se muestra un ejemplo de cómo podría crear un nuevo cgroup para un contenedor:

```bash
# Create a new cgroup for a container;
sudo cgcreate -g cpu:/my_new_container

# Assign the current shell's process to the new cgroup;
echo $$ | sudo tee /sys/fs/cgroup/cpu/my_new_container/tasks

# Limit the CPU usage of the cgroup to 20%;
echo 200000 | sudo tee /sys/fs/cgroup/cpu/my_new_container/cpu.cfs_quota_us
```

En este fragmento, estamos usando `cgcreate` para crear un nuevo cgroup, luego le agregamos el proceso actual y finalmente establecemos un límite de CPU.