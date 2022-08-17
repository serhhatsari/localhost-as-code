# localhost-as-code

**Running Command**  
**To apply whole roles to the local machine:**   
`ansible-playbook main.yml -i ./inventory/hosts --ask-become-pass`   

**To apply only tech role to the local machine:**   
`ansible-playbook tech.yml -i ./inventory/hosts --ask-become-pass`   

**To apply only common role:**  
`ansible-playbook common.yml -i ./inventory/hosts --ask-become-pass`    

**Current Roles:**  
*tech* **role**:  
*social* **role**:  
*edu* **role**:  
*fun* **role**:  
*common* **role**:  
*clean* **role**:  

**To be added:**    
- Kubernetes (kubectl, minikube vs)   
