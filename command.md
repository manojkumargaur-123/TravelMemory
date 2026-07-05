ls
    2  sudo bash
    3  use employee_db
    4  db.employees.find() db.employees.find()
    5  mongosh "mongodb://appuser:Password@123@localhost:27017/employee_db?authSource=employee_db"
    6  mkdir mongodb-test
    7  cd mongodb-test~mkdir mongodb-test
    8  mkdir mongodb-test
    9  cd mongodb-test
   10  npm init -y
   11  npm install mongodb
   12  npm list mongodb
   13  nano test.js
   14  node test.js
   15  npm install mongodb
   16  node test.js
   17  ls
   18  nano test.js
   19  sudo systemctl status mongod
   20  sudo ss -tulnp | grep 27017
   21  node test.js
   22  cat test.js
   23  nano test.js
   24  node test.js
   25  npm install express
   26  nano app.js
   27  node app.js
   28  cat app.js
   29  nano app.js
   30  node app.js
   31  docker run hello-world
   32  ls
   33  nano Dockerfile
   34  nano .dockerignore
   35  ls -a
   36  docker build -t employee-backend .
   37  docker images
   38  grep "const uri" -A1 app.js
   39  grep bindIp /etc/mongod.conf
   40  sudo nano /etc/mongod.conf
   41  sudo systemctl restart mongod
   42  sudo systemctl status mongod
   43  hostname
   44  nano app.js
   45  docker build -t employee-backend .
   46  docker run -d   --name employee-backend   -p 3000:3000   employee-backend
   47  docker ps -a
   48  docker logs employee-backend
   49  ping 172.31.22.74
   50  curl ifconfig.me
   51  nano .env
   52  ls
   53  nano app.js
   54  npm install dotenv
   55  nano Dockerfile
   56  nano .dockerignore
   57  docker build -t employee-backend .
   58  ls -a
   59  nano .env
   60  docker run -t travel-Memory-backend -p 3000:3000 employee-backend
   61  docker run -p 3000:3000 employee-backend
   62  nano app.js
   63  docker build -t employee-backend .
   64  docker build -t employee-backend . --no-cache
   65  docker run -p 3001:3000 employee-backend
   66  nano app.js
   67  docker build -t employee-backend . --no-cache
   68  docker run -p 3001:3000 employee-backend
   69  cd ..
   70  ls
   71  mkdir backend
   72  ls
   73  mv mongodb-test/ backend/
   74  ls
   75  cd backend/
   76  ls
   77  cd..
   78  cd ..
   79  mkdir frontend
   80  cd frontend
   81  ls
   82  cd ~/mongodb-test
   83  curl http://localhost:3000/employees
   84  docker --version
   85  sudo usermod -aG docker $ubuntu
   86  sudo usermod -aG docker $USER
   87  newgrp docker
   88  ls
   89  sudo bash
   90  ls
   91  cd TravelMemory/
   92  ls
   93  cd backend
   94  ls
   95  cd ..
   96  ls
   97  df -l
   98  sudo cd /dev/root
   99  cd su
  100  sodo bash
  101  sudo bash
  102  su - ubuntu
  103  ls
  104  cd T
  105  cd TravelMemory/
  106  ls
  107  eval "$(ssh-agent -s)"
  108  ssh-add ~/TravelMemory/key
  109  ssh -T git@github.com
  110  git push -u origin main
  111  git config --global --add safe.directory /home/ubuntu/TravelMemory
  112  git push -u origin main
  113  sudo chown -R ubuntu:ubuntu /home/ubuntu/TravelMemory
  114  git status
  115  git add "/home/ubuntu/TravelMemory/azure-pipelines.yml"
  116  git commit -m "azure pipeline"
  117  git config --global user.name "manojkumargaur-123"
  118  git config --global user.email "manojkumargaur86@gmail.com"
  119  git commit --amend --reset-author
  120  git push -u origin main
  121  git add "/home/ubuntu/TravelMemory/docker-compose.yml"
  122  git add "/home/ubuntu/TravelMemory/LICENSE"
  123  git add "/home/ubuntu/TravelMemory/README.md"
  124  git add "/home/ubuntu/TravelMemory/backend/"
  125  git add "/home/ubuntu/TravelMemory/frontend/"
  126  git commit -m "all file upload"
  127  git push
  128  ls
  129  df -h
  130  sudo du -sh /home/ubuntu/* /var/lib/docker /var/log/* 2>/dev/null | sort -hr
  131  sudo du -xhd1 / | sort -hr
  132  ls
  133  cd TravelMemory/
  134  git init
  135  git add .
  136  git commit -m "Initial TravelMemory project"
  137  git branch -M main
  138  git remote add origin https://github.com/manojkumargaur-123/TravelMemory.git
  139  git remote -v
  140  git remote set-url origin https://github.com/manojkumargaur-123/TravelMemory.git
  141  git remote -v
  142  git push -u origin main
  143  git remote -v
  144  git push -u origin main
  145  git remote set-url origin https://github.com/manojkumargaur-123/TravelMemory.git
  146  git remote -v
  147  git init
  148  git add .
  149  git commit -m "Initial TravelMemory project"
  150  git branch -M main
  151  git remote add origin https://github.com/manojkumargaur-123/TravelMemory.git
  152  git push -u origin main
  153  ssh-keygen -t ed25519 -C "manojkumargaur86@gmail.com"
  154  cat ~/.ssh/id_ed25519.pub
  155  ls
  156  cat key.pub
  157  eval "$(ssh-agent -s)"
  158  ssh-add ~/TravelMemory/key
  159  git remote set-url origin git@github.com:manojkumargaur-123/TravelMemory.git
  160  git remote -v
  161  ssh -T git@github.com
  162  eval "$(ssh-agent -s)"
  163  ssh-add ~/TravelMemory/key
  164  ssh-add -l
  165  ssh -T git@github.com
  166  eval "$(ssh-agent -s)"
  167  ssh-add ~/TravelMemory/key
  168  ssh-add -l
  169  ls
  170  cat key.pub 
  171  ssh -T git@github.com
  172  git push -u origin main
  173  git remote -v
  174  git push -u origin main
  175  ls -l key key.pub
  176  git remote set-url origin https://github.com/manojkumargaur-123/TravelMemory.git
  177  git push -u origin main
  178  git ls-remote git@github.com:manojkumargaur-123/TravelMemory.git
  179  git remote -v
  180  git remote set-url origin git@github.com:manojkumargaur-123/TravelMemory.git
  181  git remote -v
  182  git ls-remote origin
  183  ls
  184  git branch
  185  git remote -v
  186  git status
