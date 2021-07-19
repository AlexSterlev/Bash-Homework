 box.vm.provision "shell", inline: <<-SHELL
            mkdir -p ~root/.ssh; cp ~vagrant/.ssh/auth* ~root/.ssh
            mkdir /var/log/parser && chown vagrant /var/log/parser
            yum install vim mailx -y
            sudo mkdir /var/log/parser && sudo chown vagrant /var/log/parser
            sudo yum install vim mailx -y
          SHELL

      end
