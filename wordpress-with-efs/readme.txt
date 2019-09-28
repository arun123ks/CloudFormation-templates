How to use this template 


1. first run wordpressvpcinfra.yaml . it will create vpc all component, except asg and servers.
2. Run wordpressbootstrapserver.yaml, it will create ASG with1 serer and do wordpress installation and move it to EFS.
3. wordpressfinalserver.yaml, it will create final ASG and servers 
