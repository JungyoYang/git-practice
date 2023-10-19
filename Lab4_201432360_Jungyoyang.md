# Lecture 4
Linux CLI(Command Line Interface)

# Shell Command

- `pwd`: **print working directory** 현재 디렉토리의 경로를 표시하는 명령어입니다.
- `cd`: **change directory** 디렉토리를 변경합니다.
- `ls`: **list** 현재 디렉토리의 파일 및 폴더 목록을 표시합니다.
    - `ls /specific_directory`: 지정한 디렉토리(`specific_directory`) 내의 파일 및 폴더 목록을 보여줍니다
    - `ls -l`: **long** 디렉토리의 파일 및 폴더 목록을 자세히 표시합니다. 각 파일 및 폴더의 권한, 소유자, 그룹, 크기, 수정 날짜 및 시간 등의 정보를 보여줍니다.
    - `ls -la`: **long all** 디렉토리의 모든 파일 및 폴더 목록을 표시합니다. 이 옵션은 숨김 파일 및 폴더도 포함하여 자세히 보여줍니다.

# **Manipulation**

- `cp`: ********copy******** 파일이나 디렉토리를 복사합니다.
    - `cp original_file_or_dir target_file_or_dir`: 원본 파일이나 디렉토리(`original_file_or_dir`)를 다른 이름이나 다른 위치(`target_file_or_dir`)에 복사할 수 있습니다.
    - `cp -i`: **interactive** 기존 파일을 덮어쓰기 전에 사용자에게 확인 메시지를 보여줍니다.
    - `cp -R original_dir target_dir`: **recursive** 디렉토리와 그 내용을 복사합니다. `target_dir` 안에 `original_dir` 생성, 디렉토리 내의 모든 파일과 하위 디렉토리를 함께 복사합니다.
- `mv`: **move** 파일이나 디렉토리를 이동하거나 이름을 변경합니다.
    - `mv original_file target_file`: `original_file`을 `target_file`로 이름을 변경합니다.
    - `v -i original_file target_file`: **interactive** 기존 파일을 덮어쓰기 전에 사용자에게 확인 메시지를 보여줍니다.
    - `mv original_file1 original_file2 target_dir`: `original_file1`과 `original_file2`를 `target_dir`로 이동합니다. `original_file1`과 `original_file2`는 동일한 디렉토리에 있어야 합니다.
    `target_dir`가 존재해야 합니다.
    - `mv original_dir target_dir`: `original_dir`를 `target_dir`로 이동하거나 이름을 변경합니다. `original_dir`은 원래 있던 디렉토리이고, `target_dir`은 이동 또는 이름 변경할 디렉토리입니다. 이 명령을 사용하여 디렉토리를 다른 위치로 이동하거나, 디렉토리의 이름을 변경할 수 있습니다.
- `rm`: 파일이나 디렉토리를 삭제합니다.
- `mkdir`: 새로운 디렉토리를 생성합니다.

**Kernel**: Core of OS that controls and communicates with hardware resource
**Shell**: Interface that allows users to communicate with kernel: bash, zsh, …
Users runs applications and give commands through shell
---
# CLI(Command Line Interface)
> Have to remember commands
> Keyboards, mostly
> Relatively fast
> Scripts enable automation and records
> Basic environment for developers
---
# GUI (Graphical User Interface)
> Easy to use and Intuitive
> Mouse mostly + Some keyboard shorcuts
> Relatively slow
> Manual labors required for repetitive tasks
> For daily users
---
### Shell command: 
pwd
### pwd: 
shows the current path in a hierarchical directory

---
# Shell command: cd and ls
### cd: 
change directory
### ls: 
list files and directories
### arguments:
> [directory name]
> / root
> . current directory
> .. upper-level directory
> ~ home of current user
> /[directory name]: absolute path
> ./[directory name]: relative path
> ../[directory name]: relative path

## options:
- l show detailed information (long format)
- lh same as above, but size in units
---
# Manipulation
**Warning**: These commands may delete or overwrite your files and directories!
Make sure to backup your important contents.
---
# Manipulation: cp
**cp**: copy files and directories
**mv**: move files and directories or rename them
**rm**: delete files and directories permantely and irreversevely!!!
**mkdir**: make a new directory
---
# Help command
- help
- man
- exit
