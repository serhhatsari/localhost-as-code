# localhost-as-code

**Running Command**  
**To apply whole roles:** 
`ansible-playbook main.yml -i ./inventory/hosts --ask-become-pass`  

**To apply only tech role:**  
`ansible-playbook tech.yml -i ./inventory/hosts --ask-become-pass`  

**To apply only common role:**  
`ansible-playbook common.yml -i ./inventory/hosts --ask-become-pass`  

**Current Roles:**  
[*tech* **role**](https://github.com/serhhatsari/localhost-as-code/tree/master/roles/tech)   
[*social* **role**](https://github.com/serhhatsari/localhost-as-code/tree/master/roles/social)    
[edu* **role**](https://github.com/serhhatsari/localhost-as-code/tree/master/roles/edu)  
[fun* **role**](https://github.com/serhhatsari/localhost-as-code/tree/master/roles/fun)  
[common* **role**](https://github.com/serhhatsari/localhost-as-code/tree/master/roles/common)   
[clean* **role**](https://github.com/serhhatsari/localhost-as-code/tree/master/roles/clean)   

**To be added:**    
- Kubernetes (kubectl, minikube vs)   