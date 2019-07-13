# ![Bash Logo][img_bash_logo] BashKit

## Bash Cheatsheet

- Search backward through the command history for a particular string
    ```bash
    ctrl + r
    ```

- Loop using `until`, `while`, and `for`
    ```bash
    until test-commands; do consequent-commands; done
    ```
    ```bash
    while test-commands; do consequent-commands; done
    ```
    ```bash
    for name [ [in [words ...] ] ; ] do commands; done
    ```
    ```bash
    for (( expr1; expr2; expr3 )) ; do commands; done
    ```

- Return to the previous working directory
    ```bash
    cd -
    ```

- Move to the beginning or end of the current line
    ```bash
    ctrl + a
    ```
    ```bash
    ctrl + e
    ```

- Reuse the last item from the previous command
    ```bash
    !$
    ```

- Reuse the previous command in present command
    ```bash
    !!
    ```

## 

### ![Bash Favicon][img_bash_favicon] &nbsp; [Bash 5.0 Manual][href_bash_manual]
### ![Bash Favicon][img_bash_favicon] &nbsp; [Bash Logos]()

[//]: # (---------------- Assets ----------------)

[img_bash_logo]: /assets/24x24.png
[img_bash_favicon]: /assets/Favicon-16x16.png

[//]: # (---------------- Links ----------------)

[href_bash_manual]: https://www.gnu.org/software/bash/manual/bash.pdf
[href_bash_logos]: https://github.com/odb/official-bash-logo