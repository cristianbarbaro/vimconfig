### Instalación:

* Renombrar o eliminar la carpeta `~./vim`:
    * `mv ~/.vim ~/.vim-back`

* Clonar este repositorio:
    * `git clone https://github.com/cristianbarbaro/vimconfig.git ~/.vim/`

* Instalar el script de [Vundle](git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim) (administra e instala los plugins necesarios para Vim):
    * `git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`

* Editar el archivo `~/.vim/vimrc` a gusto (hay cientos de cosas que se les puede hacer) agregando plugins y configurando el editor a tu gusto.

* Finalmente, instalar los plugins ejecutando dentro de vim:
    * `:PluginInstall`

* O ejecutando desde la consola:
    * `vim +PluginInstall +qall`
