# Eyelash Corne

## Archivos de Configuración Clave

Accesos directos a los archivos de configuración:

| Archivo                                                                                                        | Descripción                                                                                      |
| -------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| [`eyelash_corne.keymap`](https://github.com/NicohBu/ZMK-Nicorne/blob/main/config/eyelash_corne.keymap)         | Aquí se definen las capas y se asigna cada tecla.             |
| [`eyelash_corne.config`](https://github.com/NicohBu/ZMK-Nicorne/blob/main/config/eyelash_corne.conf)           | Opciones de configuración o activación de funcionalidades cómo `NKRO`, etc.   |
| [`keymap_drawer.config.yaml`](https://github.com/NicohBu/ZMK-Nicorne/blob/main/keymap_drawer.config.yaml)      | YAML con la información de keycodes para Keymap-Drawer. |
| [`Keymap editor`](https://nickcoutsos.github.io/keymap-editor/)                                                | Herramienta para configurar visualmente el keymap  |



## Layout

![Eyelash Corne 3x6+3](https://github.com/NicohBu/zmk-Nicorne/blob/main/keymap-drawer/eyelash_corne.svg)

<details>
<summary>Información adicional</summary>
  
## (Eyelash Peripherals) Corne ZMK Repository

**This keyboard is not the same as [foostan's Corne](https://github.com/foostan/crkbd). It will not work with standard `corne` firmware.**

![Photo of Eyelash Peripherals Corne](https://ae01.alicdn.com/kf/Sa797fee25edd44248fbfdb0e13d44e00B.jpg)

If you need a 3D model of this keyboard, email `380465425@qq.com`.

## Instructions

1. [Fork this repository](https://docs.github.com/en/get-started/quickstart/fork-a-repo#forking-a-repository).
2. [Click the **Actions** tab and make sure the workflow is enabled](https://docs.github.com/en/actions/managing-workflow-runs-and-deployments/managing-workflow-runs/disabling-and-enabling-a-workflow#enabling-a-workflow).
3. Make sure the `eyelash_corne` project in [`config/west.yml`](config/west.yml) still works. The `boards/arm/eyelash_corne` folder will be downloaded from this URL.
4. If there is still a `boards/arm/eyelash_corne` folder in your fork, delete it.

**If you already have a ZMK config repository, [you can add this one as a module instead of forking](https://zmk.dev/docs/features/modules#building-with-modules).**

</details>
