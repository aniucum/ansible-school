# lesson_01
1. task_01
```
cd ansible-school/lesson_01/
ansible-playbook -i ./inventory/dev/dev.ini  ./playbooks/task_01.yml
```
![lesson_01 task_01](/img/lesson_01_task_01.JPG)
2. task_02
```
ansible-playbook -i ./inventory/dev/dev.ini  ./playbooks/task_02.yml
```
![lesson_01 task_02](/img/lesson_01_task_02.JPG)
3. task_03
```
ansible-playbook -i ./inventory/dev/dev.ini  ./playbooks/task_03.yml
```
![lesson_01 task_03](/img/lesson_01_task_03.JPG)
# lesson_02
- Create password
```bash
python -c 'import crypt,getpass;pw=getpass.getpass();print(crypt.crypt(pw) if (pw==getpass.getpass("Confirm: ")) else exit())'

passwordAlice
passwordBob
passwordCarol
```
![lesson_02 task_01](/img/lesson_02_task_01.JPG)
