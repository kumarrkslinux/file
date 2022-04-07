
pssh -h ser.txt --inline-stdout -x "-o StrictHostKeyChecking=no -i /root/.ssh/ansible_ssh_key" -I<./array_controller_firmware.sh > array_firmware.csv
