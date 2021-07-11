```
[ec2-user@ip-172-31-59-205 code]$ history
    1  python -V
    2  sudo yum list python3
    3  sudo yum install  python3
    4  python3 -V
    5  pip3 --version
    6  sudo pip3 install ansible
    7  ansible --version
    8  ssh-keygen
    9  ls -ltr ~/.ssh/
   10  cat ~/.ssh/id_rsa.pub
   11  ssh ec2-user@172.31.60.171
   12  vi inv
   13  ansible -i inv -m ping 
   14  ansible all -i inv -m ping 
   15  vi inv 
   16  ansible all -i inv -m ping 
   17  ansible web -i inv -m ping 
   18  vi inv 
   19  ansible all -i inv -m ping 
   20  ansible web -i inv -m ping 
   21  cat inv 
   22  ansible all -m ping 
   23  sudo mkdir /etc/ansible
   24  sudo vi /etc/ansible/hosts
   25  ansible all -m ping 
   26  vi .ssh/admin_k8s_key.pem
   27  chmod 400 .ssh/admin_k8s_key.pem
   28  vi inv 
   29  ls -ltr /home/ec2-user/.ssh/admin_k8s_key.pem
   30  vi inv 
   31  ansible web -i inv  -m ping 
   32  cat inv 
   33  ansible web -i inv  -m shell -c uptime
   34  ansible web -i inv  -m shell -C uptime
   35  ansible web -i inv  -m shell -a uptime
   36  ansible web -i inv  -m shell -a hostname
   37  mkdir code
   38  cd code/
   39  mkdir single_apache
   40  cd single_apache/
   41  vi apache.yaml
   42  ls -ltr
   43  cp ../../inv .
   44  cat inv 
   45  ls- ltr
   46  ls -ltr
   47  ansible-playbook -i inv apache.yaml
   48  ls -ltr
   49  vi index.html
   50  ansible-playbook -i inv apache.yaml
   51  ls -ltr
   52  cat apache.yaml 
   53  ansible-playbook -i inv apache.yaml
   54  cat inv 
   55  vi index.html 
   56  ansible-playbook -i inv apache.yaml
   57  cd ../
   58  ls -ltr
   59  mkdir webproject
   60  cd webproject/
   61  ls -ltr
   62  cat ../single_apache/apache.yaml 
   63  vi apache.yaml
   64  ls -ltr
   65  cat apache.yaml 
   66  vi apache.yaml
   67  ls -ltr
   68  mkdir roles
   69  cd roles/
   70  mkdir webserver
   71  cd webserver/
   72  pwd
   73  mkdir tasks
   74  cd tasks/
   75  ls -ltr
   76  vi main.yaml
   77  cat ../../../../single_apache/apache.yaml 
   78  vi main.yaml
   79  ls -ltr
   80  cd ../
   81  ls -ltr
   82  cd ../
   83  ls -ltr
   84  vi index.html
   85  ls -ltr
   86  co ../single_apache/inv .
   87  cp ../single_apache/inv .
   88  ls -ltr
   89  cat apache.yaml 
   90  cd code/
   91  ls -ltr
   92  cd webproject/
   93  sudo yum install tree
   94  tree
   95  ansible-playbook -i inv apache.yaml
   96  tree
   97  cat apache.yaml 
   98  ls- ltr
   99  ls -ltr
  100  mkdir roles/webserver/templates
  101  mv index.html roles/webserver/templates/
  102  vi roles/webserver/tasks/main.yaml 
  103  ansible-playbook -i inv apache.yaml
  104  ls -ltr
  105  cat apache.yaml 
  106  ls -ltr
  107  mkdir group_vars
  108  vi group_vars/web
  109  vi roles/webserver/templates/index.html 
  110  ansible-playbook -i inv apache.yaml
  111  tree
  112  cat apache.yaml 
  113  cat group_vars/web 
  114  cat roles/webserver/templates/index.html 
  115  vi roles/webserver/tasks/main.yaml 
  116  mkdir roles/webserver/handlers
  117  vi roles/webserver/handlers/main.yaml
  118  cat roles/webserver/tasks/main.yaml 
  119  vi roles/webserver/handlers/main.yaml
  120  vi group_vars/web 
  121  ansible-playbook -i inv apache.yaml
  122  tree
  123  sudo yum install git -y
  124  cd ../
  125  git init 
  126  git add .
  127  git commit -m "first commit"
  128  git branch -M main
  129  git remote add origin https://github.com/devopsmar2021/ansible_code.git
  130  git push -u origin main
  131  history

```
