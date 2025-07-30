# Eyelash Corne

## Archivos de Configuración Clave

Accesos directos a los archivos de configuración:

|         Archivo      |      Descripción      |
| --------------------- | ---------------------- |
| [`eyelash_corne.keymap`](config/eyelash_corne.keymap)         | Aquí se definen las capas y se asigna cada tecla.             |
| [`eyelash_corne.config`](config/eyelash_corne.conf)           | Opciones de configuración o activación de funcionalidades cómo `NKRO`, etc.   |
| [`keymap_drawer.config.yaml`](keymap_drawer.config.yaml)      | YAML con la información de keycodes para Keymap-Drawer. |
| [`Keymap editor`](https://nickcoutsos.github.io/keymap-editor/)                                                | Herramienta para configurar visualmente el keymap  |



## Layout

![Eyelash Corne 3x6+3](keymap-drawer/eyelash_corne.svg)

<details>
<summary>Información adicional</summary>

## Recursos
|      Enlaces       |       Descripción       |
| ------------------- | ------------------------ |
| [`Keymap-Drawer`](https://keymap-drawer.streamlit.app/)   | Web para dibujar el keymap manualmente.      |
| [`Pictogrammers`](https://pictogrammers.com/library/mdi/)            | Web para buscar iconos para dibujar en el keymap.                       |
| [`Keymap_Drawer Repo`](https://github.com/caksoylar/keymap-drawer)  | Documentación y repositorio original de keymap drawer.          |
| [`Keymap-Drawer Reference Repo`](https://github.com/minusfive/knucklehead) | Repositorio de referencia de keymap drawer.                   |
| [`Keymap.backup`](857130589ffc2c96f7cb2c11be58c2ae0add000e/config/eyelash_corne.keymap) | Backup antiguo del keymap |


<details>
<summary>Antiguo</summary>
  
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
