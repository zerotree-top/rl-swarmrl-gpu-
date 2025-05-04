# rl-swarmrl--安装教程

📥 安装
1.安装 sudo

apt update && apt install -y sudo


2.安装其他依赖项

sudo apt update && sudo apt install -y python3 python3-venv python3-pip curl wget screen git lsof nano unzip iproute2



3.安装 Node.js 和 npm

curl -sSL https://raw.githubusercontent.com/zunxbt/installation/main/node.sh | bash


4.创建屏幕会话

screen -S gensyn



5.运行 swarm

cd $HOME && rm -rf rl-swarm-cpu && git clone https://github.com/zerotree-top/rl-swarm-cpu.git && cd rl-swarm-cpu && ./run_rl_swarm.sh
