    1  su 
    2  su
    3  cat /etc/passwd
    4  su 
    5  whoami
    6  sudo 
    7  sudo ls -la
    8  sudo apt-get update
    9  sudo apt-get install ca-certificates curl gnupg
   10  sudo install -m 0755 -d /etc/apt/keyrings
   11  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg
   12  sudo chmod a+r /etc/apt/keyrings/docker.gpg
   13  echo   "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/ubuntu \
   14    $(. /etc/os-release && echo "$VERSION_CODENAME") stable" |   sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
   15  sudo apt-get update
   16  sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
   17  docker 
   18  exit
   19  docker 
   20  docker ps 
   21  docker ps
   22  sudo chmod 777  /var/run/docker.sock
   23  docker ps
   24  docker ps 
   25  sudo chown adi:adi /var/run/docker.sock
   26  docker ps 
   27  docker ps 
   28  git 
   29  git -v
   30  clear
   31  cd d:
   32  cd /mnt/d
   33  dir 
   34  ls 
   35  cd ~
   36  pwd 
   37  docker run -d -e POSTGRES_USER=odoo -e POSTGRES_PASSWORD=odoo -e POSTGRES_DB=postgres --name db postgres:15 > postgres.sh
   38  echo "docker run -d -e POSTGRES_USER=odoo -e POSTGRES_PASSWORD=odoo -e POSTGRES_DB=postgres --name db postgres:15 > postgres.sh"
   39  dir 
   40  chmod 777 postgres.sh 
   41  ./postgres.sh 
   42  docker run -d -e POSTGRES_USER=odoo -e POSTGRES_PASSWORD=odoo -e POSTGRES_DB=postgres --name db postgres:15
   43  docker ps 
   44  docker run -p 8069:8069 --name odoo --link db:db -t odoo
   45  docker ps 
   46  docker container stop a8073af1719a
   47  dir 
   48  mkdir odoo-community
   49  cd odoo-community/
   50  touch dokcer-compose.yml
   51  nano dokcer-compose.yml 
   52  docker-compose up -d 
   53  mv dokcer-compose.yml  docker-compose.yml 
   54  docker-compose up -d 
   55  docker ps
   56  docker ps 
   57  docker exec -it 27760159b002 sh 
   58  dir 
   59  cd ..
   60  git clone https://github.com/docker/python-docker
   61  cd python-docker/
   62  dir 
   63  python3 -m venv .venv
   64  py
   65  pyton
   66  python
   67  py
   68  apt-get install python3 python3-dev
   69  sudo apt-get install python3 python3-dev
   70  py
   71  python 
   72  python3
   73  py3
   74  python
   75  python3
   76  python3-dev'
   77  python3-dev
   78  python3
   79  python3 -m venv .venv
   80  ls 
   81  source .venv/bin/activate
   82  dir 
   83  python3 -m pip install -r requirements.txt
   84  cat requirements.txt 
   85  dir 
   86  ls -la
   87  dir .venv
   88  source .venv/bin/activate
   89  source ./.venv/bin/activate
   90  dir .venv/bin/python
   91  dir .venv/bin/
   92  dir .venv/bin/python
   93  dir .venv/bin/python3
   94  dir .venv/bin/python3.10 
   95  ls -la .venv/bin/python3.10 
   96  python3 -m pip install -r requirements.txt
   97  git branch -l
   98  git pull 
   99  python3 -m venv .venv
  100  apt install python3.10-venv
  101  sudo apt install python3.10-venv
  102  apt install python3.10-venv
  103  source .venv/bin/activate
  104  python3 -m pip install -r requirements.txt
  105  virtualenv .env
  106  source .venv/bin/activate
  107  pip install --upgrade virtualenv
  108  sudo apt install python3-pip
  109  pip install --upgrade virtualenv
  110  history 
  111  virtualenv -p python3 venv
  112  cd ~
  113  ls 
  114  cd odoo-community/
  115  docker-compose down 
  116  docker volume ls 
  117  docker volume prune
  118  docker volume ls 
  119  docker ps 
  120  docker volume rm cbc6583190eeff556a856fa6f77f4638492fca4e1f5af4fdb5a11ccf2afa4057
  121  docker ps
  122  cat docker-compose.yml 
  123  docker-compose up -d 
  124  docker ps 
  125  docker compose down 
  126  docker-compose up -d 
  127  docker compose down 
  128  docker-compose up -d 
  129  docker compose down 
  130  docker-compose up -d 
  131  docker ps 
  132  docker-compose down 
  133  cp docker-compose.yml docker-compose-14.yml 
  134  echo "" > docker-compose-14.yml 
  135  nano docker-compose-14.yml 
  136  docker-compose down 
  137  docker 
  138  docker-compose up -f docker-compose-14.yml 
  139  docker-compose  -f docker-compose-14.yml up -d
  140  docker ps 
  141  docker-compose  -f docker-compose-14.yml up 
  142  docker-compose   up 
  143  docker volume ls 
  144  docker volume prune 
  145  docker-compose   up -d
  146  docker volume ls 
  147  docker-compose   down 
  148  docker volume prune 
  149  docker volume ls 
  150  docker volume prune 
  151  docker volume rm  odoo-community_odoo-db-data
  152  docker volume rm  4b3b258d4aec8045030eb04e7afd8730a537393224821d784f56c424cd58b35a
  153  docker volume rm  23961adb66ca34a908ec1895db795bce84a9b650bf4f240cc131c18a431dd54d
  154  docker volume rm   odoo-community_odoo-web-data
  155  docker-compose   up -d
  156  docker ps 
  157  docker exec -it 6dd049b126a6 sh 
  158  python 
  159  python3
  160  dir 
  161  docker-compose down 
  162  docker ps 
  163  git clone https://github.com/odoo/odoo.git
  164  cd ~?
  165  cd ~/
  166  pwd
  167  ls -la
  168  cd odoo-community/
  169  ls 
  170  docker-compose up -d 
  171  docker-compose down 
  172  docker-compose up -d 
  173  pip version 
  174  exit
  175  py
  176  python --v
  177  python -v
  178  python --version 
  179  python3 --version 
  180  py
  181  cd ~
  182  command -v pip
  183  pip
  184  py
  185  python3 --version 
  186  pip
  187  pip --version 
  188  python3
  189  python3 -version 
  190  exit
  191  cd ~/
  192  dir 
  193  cd odoo-community/
  194  dir 
  195  docker-compose down 
  196  code .
  197  docker-compose up
  198  cd ..
  199  dir 
  200  cd odoo-14.0/
  201  dir 
  202  phyton3 -v
  203  python3 -v
  204  cd ..
  205  python3 --version
  206  cd -
  207  python3 --version
  208  cd ..
  209  dir 
  210  docker ps 
  211  mkdir odoo-demo
  212  mv odoo-14.0 odoo-demo/
  213  ls 
  214  ls odoo-demo/
  215  mv odoo-community-docker odoo-demo/
  216  mv postgres.sh  odoo-demo/
  217  mv python-docker  odoo-demo/
  218  dir 
  219  mv odoo-community-docker.zip  odoo-demo/
  220  dir 
  221  cd odoo-demo/
  222  dir 
  223  git clone https://github.com/Hortenziya/technical-training-sandbox.git
  224  dir 
  225  cd odoo-14.0/
  226  code .
  227  curl https://pyenv.run | bash
  228  echo 'export PATH="/home/odoo/.pyenv/bin:$PATH"' >> ~/.bashrc
  229  echo 'eval "$(pyenv init -)"' >> ~/.bashrc
  230  echo 'eval "$(pyenv virtualenv-init -)"' >> ~/.bashrc
  231  exec $SHELL
  232  python3 --version 
  233  cd ..
  234  mkdir test-venv
  235  cd test-venv/
  236  pyenv virtualenv 3.9.2 odoo-14-env
  237  pyenv
  238  cat ~/.bashrc
  239  fit 
  240  dir 
  241  pyenv
  242  dir /home/odoo/
  243  curl https://pyenv.run | bash
  244  echo 'export PATH="/home/adi/.pyenv/bin:$PATH"' >> ~/.bashrc
  245  echo 'eval "$(pyenv init -)"' >> ~/.bashrc
  246  echo 'eval "$(pyenv virtualenv-init -)"' >> ~/.bashrc
  247  nano ~/.bashrc 
  248  exec $SHELL
  249  pyenv virtualenv 3.10.12 odoo-14-env
  250  pyenv
  251  dir 
  252  pyenv virtualenv 3.9.2 odoo-14-env
  253  python3 --version 
  254  pyenv virtualenv 3.10.12 odoo-14-env
  255  pyenv install 3.10.12
  256  pyenv virtualenv 3.9.2 odoo-14-env
  257  pyenv virtualenv 3.10.12 odoo-14-env
  258  pyenv install 3.10.12
  259  pyenv virtualenv 3.10.12 odoo-14-env 
  260  pyenv install 3.9.2
  261  sudo apt-get install libbz2-dev
  262  pyenv install 3.9.2
  263  sudo apt-get install libncurses5 libncurses5-dev libncursesw5
  264  pyenv install 3.9.2
  265  pyenv install -f
  266  pyenv install -f 3.10.12
  267  python3 --version 
  268  py
  269  pyenv
  270  docker ps 
  271  service
  272  pip --version 
  273  cd ..
  274  dir 
  275  cd odoo-community-docker/
  276  dir 
  277  docker-compose up -d
  278  docker ps 
  279  wget https://github.com/wkhtmltopdf/packaging/releases/download/0.12.6-1/wkhtmltox_0.12.6-1.bionic_amd64.deb
  280  apt install ./wkhtmltox_0.12.6-1.bionic_amd64.deb
  281  dir 
  282  apt install ./wkhtmltox_0.12.6-1.bionic_amd64.deb
  283  sudo apt install ./wkhtmltox_0.12.6-1.bionic_amd64.deb
  284  whoami
  285  sudo apt update && sudo apt install wget
  286  sudo apt install ./wkhtmltox_0.12.6-1.bionic_amd64.deb
  287  dir
  288  rm -rf wkhtmltox_0.12.6-1.bionic_amd64.deb 
  289  cd ..
  290  wget https://github.com/wkhtmltopdf/packaging/releases/download/0.12.6-1/wkhtmltox_0.12.6-1.focal_amd64.deb
  291  sudo apt install -f ./wkhtmltox_0.12.6-1.focal_amd64.deb
  292  wget http://archive.ubuntu.com/ubuntu/pool/main/o/openssl/libssl1.1_1.1.1-1ubuntu2.1\~18.04.20_amd64.deb
  293  wget http://archive.ubuntu.com/ubuntu/pool/main/o/openssl/libssl1.1_1.1.1f-1ubuntu2_amd64.deb
  294  sudo dpkg -i libssl1.1_1.1.1f-1ubuntu2_amd64.deb
  295  sudo apt install -f ./wkhtmltox_0.12.6-1.focal_amd64.deb
  296  sudo apt-get install -f ./wkhtmltox_0.12.6-1.focal_amd64.deb
  297  Skip to content
  298  DEV Community
  299  Search...
  300  Log in
  301  Create account
  302  0
  303  Jump to Comments
  304  7
  305  Save
  306  Coding Dodo
  307  Posted on Apr 19, 2021 • Originally published at codingdodo.com on Apr 4, 2021
  308  3
  309  1
  310  Install and Deploy Odoo 14 from source on DigitalOcean
  311  #
  312  odoo
  313  #
  314  odoo14
  315  #
  316  ubuntu20
  317  #
  318  deployment
  319  Install and Deploy Odoo 14 from source on DigitalOcean
  320  In this tutorial, we will deploy a production-ready Odoo 14 instance. Install it from GitHub source on a brand new DigitalOcean Droplet Ubuntu 20.04 (LTS) x64. What we will do:
  321  Going through DigitalOcean registration
  322  Installing all the Ubuntu 20.4 requirements necessary to install Odoo from the source
  323  Using Pyenv to prepare our server for multiple python versions and virtualenvs in case you want to host other versions of Odoo
  324  Creating odoo user and making Odoo run as a service
  325  Install Let's Encrypt SSL Certificate
  326  Making Odoo multiprocess and using Nginx as a reverse proxy
  327  Basic security with ufw
  328  DigitalOcean offers you 100€ credit to use in 6 months since you can create machines and destroy them quickly it's a great place to experiment with Odoo installs or to choose it as your production server!
  329  Creating a DigitalOcean account
  330  First of all, go to DigitalOcean and create an account using the link
  331  Install and Deploy Odoo 14 from source on DigitalOcean
  332  DigitalOcean Register
  333  Create your credentials, validate your email and follow the steps until you arrive on that page
  334  Install and Deploy Odoo 14 from source on DigitalOcean
  335  DigitalOcean Register Choose Control panel
  336  Here it can get a bit confusing because most of the links direct you to the DigitalOcean platform but we want the regular dashboard so click on Explore our control panel
  337  When on the Control Panel click on Get Started with a Droplet or Create / Droplet to arrive on this screen
  338  Install and Deploy Odoo 14 from source on DigitalOcean
  339  Create Ubuntu Droplet
  340  Choose Ubuntu 20.04 and choose the right machine based on your needs. Remember that you are only billed for the time that the machine is up so you can choose a good machine and destroy it later. Choose at least 2 CPUs or everything will feel very slow.
  341  Scrolling down you will see a space to add your ssh-key
  342  Install and Deploy Odoo 14 from source on DigitalOcean
  343  Adding the SSH KEY
  344  Adding SSH Key
  345  If you don't have an SSH Key yet you have to generate it with the command. You probably already have an id_rsa.pub file in your .ssh folder. For this example, we will create a new SSH key that will be used to connect to our DigitalOcean Droplets. Feel free to skip that part or read it to create your first key or handle multiple ssh keys.
  346  ssh-keygen -C "contact@codingdodo.com"
  347  When prompted for the name of the file we choose that
  348  /Users/codingdodo/.ssh/id_rsa_codingdodo
  349  Show the content of the newly generated key:
  350  cat ~/.ssh/id_rsa_codingdodo.pub
  351  On DigitalOcean, click on New SSH Key and copy/paste the content printed out. Scroll down more and click on Create Droplet. It will take a minute then your Droplet will be ready
  352  Install and Deploy Odoo 14 from source on DigitalOcean
  353  Droplet is Ready
  354  Copy the IP Address , we will add it to our SSH config file to make things easier for us. If you handle multiple SSH Keys this is a nice way to handle with which SSH Key you connect to each server.
  355  vim ~/.ssh/config
  356  Add this section with your IP address and the name of the public key you created.
  357   Host testingdodo
  358     Hostname 143.198.123.151
  359     User root
  360     IdentityFile ~/.ssh/id_rsa_codingdodo
  361     IdentitiesOnly yes
  362  We name our Host testingdodo so in our shell, we can type this shortcut to ssh into the machine.
  363  ssh testingdodo
  364  And answer yes to the security prompt, and you will be logged in
  365  Welcome to Ubuntu 20.04.1 LTS (GNU/Linux 5.4.0-51-generic x86_64)
  366  ...
  367  root@ubuntu-s-1vcpu-1gb-intel-nyc1-01:~#
  368  Ubuntu 20.4 Prerequesites
  369  We start by updating our packages
  370  apt update
  371  Installing PostgreSQL
  372  apt install postgresql postgresql-contrib
  373  We will later create a Unix user named Odoo, so we will create a PostgreSQL user with the same name. If you would prefer a different name, remember to keep that consistency to make things easier when you come back later to your environment.
  374  su - postgres
  375  createuser --interactive -P odoo
  376  With the --interactive flag, PostgreSQL will ask us for a password and the privileges that will be given to our odoo PostgreSQL user.
  377  Enter password for new role:
  378  Enter it again:
  379  Shall the new role be a superuser? (y/n) n
  380  Shall the new role be allowed to create databases? (y/n) y
  381  Shall the new role be allowed to create more new roles? (y/n) n
  382  Next, we will already create that database that will hold our Odoo 14 instance. In this example, it's gonna be named coding_dodo.
  383  createdb -O odoo codingdodo_demo
  384  exit
  385  cd ~
  386  dir 
  387  cd odoo-demo/
  388  apt install -y build-essential libssl-dev zlib1g-dev libbz2-dev libreadline-dev libsqlite3-dev wget curl llvm libncurses5-dev libncursesw5-dev xz-utils tk-dev libffi-dev liblzma-dev python-openssl git libpq-dev libsasl2-dev libldap2-dev ccze node-less
  389  sudo apt install -y build-essential libssl-dev zlib1g-dev libbz2-dev libreadline-dev libsqlite3-dev wget curl llvm libncurses5-dev libncursesw5-dev xz-utils tk-dev libffi-dev liblzma-dev python-openssl git libpq-dev libsasl2-dev libldap2-dev ccze node-less
  390  lsb_release -a
  391  wget https://github.com/wkhtmltopdf/packaging/releases/download/0.12.6.1-2/wkhtmltox_0.12.6.1-2.jammy_amd64.deb
  392  sudo apt install -f ./wkhtmltox_0.12.6.1-2.jammy_amd64.deb
  393  sudo chown _apt /var/lib/update-notifier/package-data-downloads/partial/
  394  sudo chown -R _apt:root /var/lib/apt/lists
  395  sudo apt install -f ./wkhtmltox_0.12.6.1-2.jammy_amd64.deb
  396  wkhtmltopdf --version
  397  wkhtmltopdf https://computingforgeeks.com computingforgeeks.pdf
  398  pyenv
  399  cd odoo-14.0/
  400  pyenv local odoo-14-env
  401  pyenv virtualenv 3.9.2 odoo-14-env
  402  dir /home/odoo/.pyenv/bin
  403  pyenv install 3.9.2
  404  clra
  405  clear
  406  pip
  407  pip -v
  408  pip --version 
  409  dir 
  410  ls -la
  411  git status 
  412  ls odd
  413  ls odoo
  414  sudo apt install python3-venv
  415  python3 -m venv .
  416  ls 
  417  ls -la
  418  mv pyvenv.cfg pyvenv.cfg-test
  419  python3 -m venv .
  420  ls -la
  421  rm -rf  pyvenv.cfg-test
  422  cat pyvenv.cfg 
  423  sudo apt install python3-dev libxml2-dev libxslt1-dev libldap2-dev libssl-dev libsasl2-dev libpq-dev libjpeg8-dev
  424  sourc ./bin/activate
  425  source ./bin/activate
  426  pip install -U pip
  427  ls -la
  428  pip install -r requirements.txt
  429  ls 
  430  nan odoo.conf
  431  nano odoo.conf
  432  ls -la
  433  ls addons/
  434  ./odoo-bin -c odoo.conf
  435  sudo ./odoo-bin -c odoo.conf
  436  odoo-bin -c odoo.conf
  437  ./odoo-bin -c odoo.conf
  438  ls -la
  439  chmod 777 odoo-bin 
  440  ./odoo-bin -c odoo.conf
  441  echo "./odoo-bin -c odoo.conf "> run.hs
  442  cat run.hs 
  443  mv run.hs  run.sh
  444  cat run.sh 
  445  chmod 77y run.sh 
  446  chmod 77t run.sh 
  447  chmod 777 run.sh 
  448  pwd
  449  ./run.sh 
  450  touch ../../history-command.md
  451  history > ../../history-command.md
  452  cat ../../history-command.md
  453  cd .
  454  cd ..
  455  dir 
  456  py
  457  python3 
  458  dir 
  459  cd te
  460  exit
  461  cd ~
  462  cd odoo-demo/
  463  dir 
  464  cd odoo-14.0/
  465  dir 
  466  ./run.sh 
  467  python3 -m venv.
  468  python3 -m venv .
  469  ./run.sh 
  470  python3 -m venv .
  471  source ./bin/activate
  472  exit
  473  cd ~
  474  cd odoo-demo/
  475  dir 
  476  cd odoo-
  477  cd odoo-14.0/
  478  source .venv/bin/activate
  479  source ./bin/activate
  480  exit
  481  cd ~/
  482  cd odoo-demo/
  483  dir 
  484  cd odoo-14.0/
  485  dir 
  486  source ./bin/activate
  487  exit 
  488  cd ~?
  489  cd ~/
  490  dir 
  491  cd odoo-demo/
  492  dir 
  493  rm -rf  wkhtmltox_0.12.6-1.focal_amd64.deb
  494  rm -rf  ./*.deb
  495  ls 
  496  git clone https://github.com/odoo/documentation.git --branch 14.0 --single-branch
  497  dir 
  498  git clone https://github.com/odoo/documentation.git --branch 14.0 --single-branch documentations-odoo-14
  499  cd documentations-odoo-14/
  500  make help .
  501  make html .
  502  make 
  503  git branch -l
  504  dir 
  505  pip install -r requirements.txt
  506  make html .
  507  cd ..
  508  git clone https://github.com/odoo/technical-training-solutions.git --branch 14.0-core --single-branch technical-training-solutions-14
  509  cd technical-training-solutions-14'
  510  cd technical-training-solutions-14
  511  dir 
  512  ls -la
  513  dir 
  514  exit
  515  make
  516  cd ~/
  517  cd odoo-demo/
  518  source /home/adi/odoo-demo/odoo-14.0/bin/activate
  519  '/home/adi/odoo-demo/odoo-14.0/odoo.conf'
  520  db_sslmode = prefer
  521  source /home/adi/odoo-demo/odoo-14.0/bin/activate
  522  ./run.sh 
  523  export "PATH=/home/adi/.vscode-server/data/User/globalStorage/donjayamanne.python-environment-manager/symlinksV1/python_9f28825f8ae4bbef6e8b34b16c046dac010eae74da55a9636e78b93ff60c9c15794841f82a540b135ec20524992a93179f9fcc80149c1ea9da362b95dd4b7376:$PATH" && clear
  524  export "PATH=/home/adi/.vscode-server/data/User/globalStorage/donjayamanne.python-environment-manager/symlinksV1/python_a304198fa501aed78c624fff01c9031acfdbd78cd238e4e23ea00a28a70e1b02af57b949f568a6ca5e92570c2db21e5857ea9aa68a8feda1e33bf1393575ce61:$PATH" && clear
  525  export "PATH=/home/adi/.vscode-server/data/User/globalStorage/donjayamanne.python-environment-manager/symlinksV1/python_a304198fa501aed78c624fff01c9031acfdbd78cd238e4e23ea00a28a70e1b02af57b949f568a6ca5e92570c2db21e5857ea9aa68a8feda1e33bf1393575ce61:$PATH" && clear
  526  source /home/adi/odoo-demo/odoo-14.0/bin/activate
  527  cd ~
  528  dir 
  529  cd odoo-demo/
  530  dir 
  531  cd odoo-14.0/
  532  ls 
  533  ./venv-activate.sh 
  534  cat venv-activate.sh 
  535  source ./bin/activate
  536  ./run.sh 
  537  exit
  538  cd ~?
  539  cd ~/
  540  cd odoo-demo/
  541  dir 
  542  cd odoo-14.0/
  543  dir 
  544  ./venv-activate.sh 
  545  cat venv-activate.sh 
  546  source ./bin/activate
  547  ./run.sh 
  548  docker ps 
  549  dir 
  550  ca test.py 
  551  cat test.py 
  552  cd ..
  553  dir 
  554  ls -la
  555  cd odoo-14.0-test/
  556  git status 
  557  exit
  558  cd ~/odoo-demo/odoo-14.0-test/
  559  ls -la
  560  git init 
  561  git status 
  562  ls -la
  563  git add .
  564  git status 
  565  git commit -m "init odoo project"
  566  git push 
  567  git remote add origin https://github.com/achmadiportofolio/odoo-14-test.git
  568  git status
  569  git git commit -m "init project"
  570  git push 
  571  git push --set-upstream origin master
  572  dir 
  573  cd ..
  574  python3 -m venv odoo-14.0-test
  575  cd odoo-14.0-test/
  576  dir 
  577  git status 
  578  git add .
  579  git status 
  580  git commit -m " create venv" 
  581  git push 
  582  git log 
  583  source ./bin/activate
  584  pip install -U pip
  585  ls -la
  586  git status 
  587  git add .
  588  git commit -m "update pip"
  589  git push 
  590  git status 
  591  git add odoo.conf 
  592  git commit -m "odoo.conf init"
  593  ./odoo-bin -c odoo.conf
  594  chmod 777 odoo-bin 
  595  ./odoo-bin -c odoo.conf
  596  pip install -r requirements.txt
  597  git status 
  598  git add odoo-bin
  599  git commit -m "odoo-bin make executable mode"
  600  git status 
  601  git add .
  602  git status 
  603  git commit -m "pip install -r requirements.txt"
  604  git push 
  605  git log 
  606  git status 
  607  git log 
  608  git reset --hard
  609  git status 
  610  git log 
  611  ./odoo-bin -c odoo.conf
  612  docker ps 
  613  ./odoo-bin -c odoo.conf
  614  cd ..
  615  cd odoo-14.0
  616  ./odoo-bin -c odoo.conf
  617  cd ..
  618  cd odoo-14.0-test/
  619  ./odoo-bin -c odoo.conf
  620  git status 
  621  git checkout -- odoo.conf
  622  git status 
  623  ./odoo-bin -c odoo.conf
  624  git checkout -- odoo.conf
  625  ./odoo-bin -c odoo.conf
  626  git stash 
  627  git status 
  628  git reset --hard
  629  ./odoo-bin -c odoo.conf
  630  git status 
  631  rm -rf addons/account/__pycache__/
  632  git status 
  633  ./odoo-bin -c odoo.conf
  634  exit 
  635  cd :~/odoo-demo/odoo-14.0-test
  636  cd ~/odoo-demo/odoo-14.0-test
  637  ./odoo-bin -c odoo.conf 
  638  source ./bin/activate
  639  ./odoo-bin -c odoo.conf 
  640  cd ../
  641  cd odoo-14.0
  642  ./odoo-bin -c odoo.conf 
  643  cd ../
  644  cd odoo-14.0-test/
  645  ./odoo-bin -c odoo.conf 
  646  history 
  647  history > history.md
